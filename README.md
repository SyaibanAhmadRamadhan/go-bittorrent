# Building a BitTorrent client from the ground up in Go

## BitTorrent explanation
### BitTorrent is a protocol for downloading and distributing files across the Internet. In contrast with the traditional client/server relationship, in which downloaders connect to a central server (for example: watching a movie on Netflix, or loading the web page you’re reading now), participants in the BitTorrent network, called peers, download pieces (chunked) of files from each other—this is what makes it a peer-to-peer protocol. We’ll investigate how this works, and build our own client that can find peers and exchange data between them.
