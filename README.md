## mirage-protocols — MirageOS signatures for network protocols

mirage-protocols provides a set of module types which libraries intended to be used as MirageOS network implementations should implement.

The set of protocols defined is:

[Mirage_protocols.ETHERNET](ethernet) and [Mirage_protocols_lwt.ETHERNET](ethernet-lwt)
[Mirage_protocols.ARP](arp) and [Mirage_protocols_lwt.ARP](arp-lwt)
[Mirage_protocols.IP](ip) and [Mirage_protocols_lwt.IP](ip-lwt), via [Mirage_protocols_lwt.IPV4](ipv4-lwt) and [Mirage_protocols_lwt.IPV6](ipv6-lwt)
[Mirage_protocols.ICMP](icmp) and [Mirage_protocols_lwt.ICMP](icmp-lwt), via [Mirage_protocols_lwt.ICMPV4](icmpv4-lwt)
[Mirage_protocols.UDP](udp) and [Mirage_protocols_lwt.UDP](udp-lwt), via [Mirage_protocols_lwt.UDPV4](udpv4-lwt) and [Mirage_protocols_lwt.UDPV6](udpv6-lwt)
[Mirage_protocols.TCP](tcp) and [Mirage_protocols_lwt.TCP](tcp-lwt), via [Mirage_protocols_lwt.TCPV4](tcpv4-lwt) and [Mirage_protocols_lwt.TCPV6](tcpv6-lwt)

mirage-protocols is distributed under the ISC license.

## Installation

mirage-protocols can be installed with `opam`:

    opam install mirage-protocols

If you don't use `opam` consult the [`opam`](opam) file for build
instructions.

## Documentation

The documentation and API reference is generated from the source
interfaces. It can be consulted [online][doc] or via `odig doc
mirage-protocols`.

[doc]: https://mirage.github.io/mirage-protocols/
