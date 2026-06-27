
Go channel works as a pipe between two goroutine. Usually one goroutine sends data to the channel, while another one receives that data from the other end. 

There are two type of go channel. Buffered and unbuffered. Buffered channel has some non-zero capacity. Buffered channel don't block the goroutine as long as it has unused capacity.  Unbuffered channel has zero capacity. It will block the sender until there is receiver and it will block a receiver until there is a receiver. 

[[Use cases of go channel]]