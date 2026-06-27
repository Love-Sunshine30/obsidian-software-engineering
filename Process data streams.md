
Every process in linux has at least three data streams. They are just file under the hood. The STDIN which has file descriptor(fd) 0, STDOUT has fd 1 and STDERR has fd 2. 

with '>' this command this stream can be redirected to any other file.