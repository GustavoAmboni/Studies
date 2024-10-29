# UDP

UDP is a connectionless model with a minimum of protocol mechanism. Being connectionless means that messages are sent without negotiating a connection and that UDP doesn't keep track of what it has sent. However, because the UDP protocol is a connectionless protocol, UDP datagrams sent to the remote endpoint are not guaranteed to arrive, nor are

they guaranteed to arrive in the same sequence in which they are sent.

UDP is suitable for purposes where error checking and correction are either not necessary or are performed in the application. These applications must be prepared to handle missing, duplicate, and out-of-sequence datagrams.

## References

1. [User Datagram Protocol (UDP) at Wikipedia](https://en.wikipedia.org/wiki/User_Datagram_Protocol)
2. [UDP (User Datagram Protocol) at MDN Web Docs](https://developer.mozilla.org/en-US/docs/Glossary/UDP)
3. [Using UDP Services .NET Framework at Microsoft Learn](https://learn.microsoft.com/en-us/dotnet/framework/network-programming/using-udp-services)
