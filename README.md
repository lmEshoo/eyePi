# eyePi
test3

    def _get_push_info(self, proc, progress):
        # read progress information from stderr
        # we hope stdout can hold all the data, it should ...
        # read the lines manually as it will use carriage returns between the messages
        # to override the previous one. This is why we read the bytes manually
        progress_handler = progress.new_message_handler()
        output = IterableList('name')

        def stdout_handler(line):
            try:
                output.append(PushInfo._from_line(self, line))
            except ValueError:
                # if an error happens, additional info is given which we cannot parse
                pass
            # END exception handling
        # END for each line
