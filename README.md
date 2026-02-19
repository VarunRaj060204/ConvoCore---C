# ConvoCore - C
A multi-client group chat application built in C using POSIX socket APIs. The server supports concurrent client connections and real-time message broadcasting over TCP. Designed and implemented on Linux, the project demonstrates low-level networking, concurrency handling, and system-level programming concepts.

Key features:

TCP socket programming (socket, bind, listen, accept, send, recv)

Multi-client support using select() / pthread (whichever you used)

Real-time message broadcasting

Graceful client disconnection handling

Error handling and resource cleanup

Built with GCC and automated using Makefile

This project showcases practical understanding of networking protocols, operating system concepts, and concurrent system design.
