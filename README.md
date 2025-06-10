A simple CLI AI agent that:

* accepts a coding task
* chooses a set of predefined functions to work on the given task:
  * scan all files in a directory
  * read contents of a file
  * overwrite the contents of a file
  * execute the Python interpreter on a file
* repeats until task completes or fails
