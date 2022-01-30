# GET_next_line @ Hive Helsinki

The get_next_line function returns a line read from a file descriptor. Like 
previous projects, the challenge is the limit of exsisting functions allowed
to be used. In this particular project, the only Libc functions that are
allowed are read, malloc and free. We were able to use functions freely from our
previosuly made Libft. 

The return value can be 1, 0 or -1 depending on whether a line has been read (1),
when the reading has been completed (0), or if an error has happened respectively
(-1).

For bonus points on this project, the get_next_line function must be able to 
manage multiple file descriptors and only one static variable is to be used to 
obtain bonus points. This function does this.
