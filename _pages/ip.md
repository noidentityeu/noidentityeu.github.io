---
layout: article
title: IP addresses
permalink: /ip
---

An Internet Protocol (IP) address is an identifier assigned to a network interface. It *can be* unique, but usually it *is not*.

There are two widespread versions of IP addresses: IPv4 and IPv6. The main difference of IPv6 compared to IPv4 is an increased length: the longer the better. While IPv6 has this and other benefits, it is not as widespread as IPv4. We'll review IPv4 for now.

Normal IPv4 addresses consist of a few numbers separate by dot: ``a.b.c.d``.

## IP distribution

IPs are usually given to Internet Service Providers (ISP) in blocks: *this range belongs to ISP in Country X*.

There are a few reserved IPs:

1. Loopback IPs: 127.0.0.1 and alike. It literally leads back to your own device.
2. Private IPs: 192.168.1.1 and alike. These IPs are reserved for private networks, for example, created by WiFi routers.

## Types of IPs

When a smartphone, laptop or any other device connects to Internet, it gets the IP address. There a few options which IP would your device get:

1. It is unique in case you opted for a **fixed IP** at your Internet Service Provider's office and you connect directly to ISP (not via WiFi-router or anything like that).

2. It is not unique in other cases.

## Privacy concerns

If you visit a website, **fixed IP** is directly associated with you and your device. While finding the person behind the IP might be problematic unless **you tell the website directly who you are**, such an IP is constant, therefore it is possible to find interconnections between different sites. For example, you're authorized on Site A, Site A sees your IP. Site B sees your IP, and if it has an agreement with Site A, it might associate your IP with you.

TODO: add about non-fixed IPs

