A collection of various awesome lists for videos, pentesters, libraries and frameworks.

> **QUIC** is the Quick UDP Internet Connections protocol, developed by Google and currently in IETF workgroups for further development. It is being considered for replacing TCP as a transport protocol for HTTP/3. We are building an Open source project for IoT & Edge Computing atop QUIC called 🦖[YoMo](https://github.com/yomorun/yomo/)

Online Community: 🍖[discord/quic](https://discord.gg/CTH3wv9) 

Maintainer: 🦖[YoMo](https://github.com/yomorun/yomo/)

## QUIC Weekly - 20210414

* [@Daniel Stenberg](https://twitter.com/bagder) 's blog: WHERE IS HTTP/3 RIGHT NOW?, said the specifications are all done. They’re now waiting in queues to get their final edits and approvals before they will get assigned RFC numbers and get published as such – they will not change any further.
* netray.io scans the IPv4 address space weekly and checks how many hosts that speak QUIC. Their latest scan found 2.1 million such hosts.
![](https://daniel.haxx.se/blog/wp-content/uploads/2021/04/ietf-quic-support-in-ipv.png)
* All the major browsers have HTTP/3 implementations and most of them allow you to manually enable it if it isn’t already done so. Chrome and Edge have it enabled by default and Firefox will so very soon
![](https://daniel.haxx.se/blog/wp-content/uploads/2021/04/Screenshot_2021-04-04-Can-I-use-Support-tables-for-HTML5-CSS3-etc.png)
* [@Robin](http://twitter.com/programart) Draw digram and open source the source file: [https://github.com/rmarx/h3-protocol-stack](https://github.com/rmarx/h3-protocol-stack)
![](https://github.com/rmarx/h3-protocol-stack/blob/main/png/protocol-stack-h2-h3-extended.png?raw=true)
* Microsoft's [open-source implementation of the QUIC protocol](https://github.com/microsoft/msquic) that will form the basis of HTTP/3 will be in Windows Server 2022. It's being used for [SMB over QUIC](https://techcommunity.microsoft.com/t5/itops-talk-blog/smb-over-quic-files-without-the-vpn/ba-p/1183449), which is a more secure replacement for WebDAV to deliver SMB access **without the expense and complexity of a VPN**. This uses QUIC as the transport for SMB **instead of TCP/IP** and RDMA, with a tunnel that secures SMB **even if encryption isn't enabled**. "SMB over QUIC will be available with Azure Automanage and Windows Server 2022," Kumar told TechRepublic. "It will also be supported as a client in Windows 10 and on third-party platforms like Android and others." 