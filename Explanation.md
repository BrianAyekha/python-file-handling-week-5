We define three functions: create_file, read_file, and append_to_file.
In create_file, we open a new file "my_file.txt" in write mode ('w') and write three lines of text to it using the write method. We use a try-except block to catch any potential exceptions, such as PermissionError.
In read_file, we open the existing file "my_file.txt" in read mode ('r') and read its contents using the read method. We print the contents to the console. We use a try-except block to catch any potential exceptions, such as FileNotFoundError.
In append_to_file, we open the existing file "my_file.txt" in append mode ('a') and append three additional lines of text to it using the write method. We use a try-except block to catch any potential exceptions, such as PermissionError.
In the main function, we call each of the three functions in sequence.
We use a try-finally block to ensure that the file is properly closed, regardless of whether an exception occurs.