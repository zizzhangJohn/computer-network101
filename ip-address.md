# IP address

An Internet Protocol address (IP address) is a numerial label such as 192.0.2.1 that is connected to a computer network that uses the Interet Protocol for communication.

## Commands to check your IP

**On Unix terminal**

```bash
~$ ifconfig
# or if you don't have ifconfig
~$ ip a
```

**On Windows CMD**

```cmd
ipconfig
```

## IP versions

**IPv4**
<div style="background-color:white;padding:1rem">
<img src="./assets/ip-address/IPv4_structure.svg" alt="IPv4 structure"/>
</div>

<br/>

IPv4 defines an IP address as 32-bit number. For a human-readable form, it is usually shown in dot-decimal notation, or sometimes known as "dotted quads"

<br />

With an 8-bit number, the maximun value it can represent is 255, hence the address space of IPv4 is from `0.0.0.0` to `255.255.255.255`

> 2<sup>32</sup> = 4,294,967,296

Not all IPv4 addresses can be allocated for pubic use(access from the internet), some addresses are reserved for special purpose such as private networks (~18 million addresses) and multicast addressing (~270 million addresses).

**IPv6**
<div style="background-color:white;">
<img src="./assets/ip-address/IPv6_structure.svg" alt="IPv6 structure"/>
</div>
<br/>
IPv6 defines addresses in 128 bits, and the addresses are showed in hexdecimal form. Compared to IPv4, IPv6 has much larger address space.<br/>


> 2<sup>128</sup>=340,282,366,920,938,463,463,374,607,431,768,211,456

<br/>

Most IPv6 addresses do not occupy all of their possible 128 bits. This condition results in fields that are padded with zeros or contain only zeros. So the address

`2001:0db8:3c4d:0015:0000:0000:1a2f:1a2b`
can be abbreviated as
`2001:db8:3c4d:15::1a2f:1a2b`.

# Useful articles and videos

<a href="https://www.youtube.com/watch?v=L6bDA5FK6gs" target="_blank">
 <img src="https://img.youtube.com/vi/L6bDA5FK6gs/0.jpg" alt="IP Addresses and the Internet - ComputerphileWatch the video" />
</a>

* [IPv6 overview](https://docs.oracle.com/cd/E18752_01/html/816-4554/ipv6-overview-10.html)
