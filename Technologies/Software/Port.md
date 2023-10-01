In computer networking, a port or port number is a number assigned to uniquely identify a connection endpoint and to direct data to a specific service. At the software level, within an operating system, a port is a logical construct that identifies a specific process or a type of network service. 

A port at the software level is identified for each transport protocol and address combination by the port number assigned to it. The most common transport protocols that use port numbers are the Transmission Control Protocol ([[TCP]]) and the User Datagram Protocol ([[UDP]]); those port numbers are 16-bit unsigned numbers.

A port number is **always** associated with a network address of a host, such as an IP address, and the type of transport protocol used for communication. 

It completes the destination or origination address of a message. Specific port numbers are reserved to identify specific services so that an arriving packet can be easily forwarded to a running application. For this purpose, port numbers lower than 1024 identify the historically most commonly used services and are called the well-known port numbers. 

Higher-numbered ports are available for general use by applications and are known as ephemeral ports.

Ports provide a multiplexing service for multiple services or multiple communication sessions at one network address. In the client–server model of application architecture, multiple simultaneous communication sessions may be initiated for the same service. 

#Port numbers and common services associated with them:

|Number|TCP/UDP/Both|Assignment   |
|---|---|---|
|7|Both|Echo Protocol|
|11|Both|Active Users ([[systat]] service)|
|20|TCP|[File Transfer Protocol](https://en.wikipedia.org/wiki/File_Transfer_Protocol "File Transfer Protocol") ([[Cybersecurity/Technologies/Internet/FTP|FTP]]) Data Transfer|
|21|TCP|[File Transfer Protocol](https://en.wikipedia.org/wiki/File_Transfer_Protocol "File Transfer Protocol") ([[Cybersecurity/Technologies/Internet/FTP|FTP]]) Command Control|
|22|TCP|[Secure Shell](https://en.wikipedia.org/wiki/Secure_Shell "Secure Shell") (SSH) Secure Login|
|23|TCP|[Telnet](https://en.wikipedia.org/wiki/Telnet "Telnet") remote login service, unencrypted text messages|
|25|TCP|[Simple Mail Transfer Protocol](https://en.wikipedia.org/wiki/Simple_Mail_Transfer_Protocol "Simple Mail Transfer Protocol") (SMTP) email delivery|
|53|Both|[Domain Name System](https://en.wikipedia.org/wiki/Domain_Name_System "Domain Name System") (DNS) service|
|67, 68|UDP|[Dynamic Host Configuration Protocol](https://en.wikipedia.org/wiki/Dynamic_Host_Configuration_Protocol "Dynamic Host Configuration Protocol") (DHCP)|
|80||[Hypertext Transfer Protocol](https://en.wikipedia.org/wiki/Hypertext_Transfer_Protocol "Hypertext Transfer Protocol") (HTTP) used in the [World Wide Web](https://en.wikipedia.org/wiki/World_Wide_Web "World Wide Web")|
|110||[Post Office Protocol](https://en.wikipedia.org/wiki/Post_Office_Protocol "Post Office Protocol") (POP3)|
|119||[Network News Transfer Protocol](https://en.wikipedia.org/wiki/Network_News_Transfer_Protocol "Network News Transfer Protocol") (NNTP)|
|123||[Network Time Protocol](https://en.wikipedia.org/wiki/Network_Time_Protocol "Network Time Protocol") (NTP)|
|143||[Internet Message Access Protocol](https://en.wikipedia.org/wiki/Internet_Message_Access_Protocol "Internet Message Access Protocol") (IMAP) Management of digital mail|
|161||[Simple Network Management Protocol](https://en.wikipedia.org/wiki/Simple_Network_Management_Protocol "Simple Network Management Protocol") (SNMP)|
|194||[Internet Relay Chat](https://en.wikipedia.org/wiki/Internet_Relay_Chat "Internet Relay Chat") (IRC)|
|443||[HTTP Secure](https://en.wikipedia.org/wiki/HTTP_Secure "HTTP Secure") (HTTPS) HTTP over TLS/SSL|
|546, 547||[DHCPv6](https://en.wikipedia.org/wiki/DHCPv6 "DHCPv6") IPv6 version of DHCP|

Port 587 (Secure SMTP)
Port 3306 (MySQL, MariaDB), 
Port 1433 (MS-SQL), 
Port 1521 (Oracle DB)
Port 8080 Web Proxy servers
Port 8888 Web Proxy servers