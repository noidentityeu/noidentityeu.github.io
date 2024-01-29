---
layout: article
title: IP addresses
permalink: /ip
---

An **Internet Protocol (IP) address** is an identifier assigned to a network interface. It *can be* unique, but usually it *is not*.

There are two widespread versions of IP addresses: IPv4 and IPv6. The main difference of IPv6 compared to IPv4 is an increased length: the longer the better. While IPv6 has this and other benefits, it is not as widespread as IPv4. We'll review IPv4 for now.

Normal IPv4 addresses consist of a few numbers separated by dot: ``a.b.c.d``. For example: ``10.20.30.40``.

## IP distribution

IPs are usually given to Internet Service Providers (ISP) in blocks: *this range belongs to ISP #1 in Country X*, and *this range belongs to ISP #2 in Country Y*.

There are a few reserved IPs:

1. Loopback IPs: 127.0.0.1 and alike. It literally directs you back to your own device.
2. Private IPs: 192.168.1.1 and alike. These IPs are reserved for private networks, for example, created by WiFi routers.

> **Note**
> 
> It means that it is possible to geolocate the IP by checking the range.

## Types of IPs

When a smartphone, laptop or any other device connects to Internet, it gets the IP address. There a few options which IP would your device get:

1. It is unique in case you:
	1. Opted for a **fixed IP** at your Internet Service Provider's office.
	2. Connect directly to ISP (not via WiFi-router or anything like that).
2. It is not unique in other cases. In that case, you *share* your IP with other users. If you connect to WiFi router, you share it with all other users of that WiFi network, so they can't be reliably distinguished by IP. Also, it is likely that your WiFi router also shares its own IP with other customers of your Internet Service Provider.

> **Note**
> 
> From privacy point of view, it is better to have non-fixed IP. But it is not the only thing that matters.

### Most common real-world practice

If you connect your phone to Internet Service Provider, most likely your IP is not unique.

If you connect your phone or laptop to WiFi router, most likely IP of your device is private (inside WiFi router network) and thus not unique, and the WiFi router has non-unique IP shared between Internet Service Provider users.

## Privacy concerns

If you visit a website, the external IP assigned to your device or to your WiFi router is visible to server administrators.

**Fixed IP** can be directly associated with you and your device. 

Finding the person behind the IP might be problematic unless **you tell the website directly who you are**.
However, as the IP is constant, it is possible to find interconnections between different sites. For example, you're authorized on ``Site A``, ``Site A`` sees your IP. ``Site B`` sees your IP, and if it has an agreement with ``Site A``, it might associate your IP with you.

That might happen with advertisement trackers.

**Non-fixed IP** can be associated with you and your device for a short while. If you enter not so popular website, the IP can be attributed to you.

