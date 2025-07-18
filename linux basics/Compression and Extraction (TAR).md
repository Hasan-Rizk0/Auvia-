
tar is an archiving utility   (compression and extraction)

to compress:

		tar -cf the_name_of_the_new_compressed_file  the_directory_or_file_that_you want_to_compress

to extract:

		tar -xf the_name_of_the_compressed_file  the_directory_or_file_that_you want_to_compress


you can also compress as gzip by:

tar -czf .....

and extract the gzip compressed file or directory by:

tar -xzf .....