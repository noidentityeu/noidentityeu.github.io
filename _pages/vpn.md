---
layout: article
title: Virtual Private Networks (VPN)
permalink: /vpn
---

Virtual Private Networks (VPN) are generally used for one purpose: *establish virtual presence in a different location*. 

But, practically, it is one of ways to **change the IP address**.


## How it works

Normally, the client (phone, laptop or any other devices) connects to **VPN server**, establishes a secure communication channel, and after that it sends all the traffic via that encrypted channel. The VPN server sends the traffic elsewhere and puts responses back to encrypted channels.

## Why is it secure

Of course, every VPN protocol is different and we can't speak about all protocols altogether. But there are shared principles:

1. There is a secure cryptographic key exchange between the client and server. Keys are **not** transferred over network. Alice and Bob guarantee that.

2. The communication itself lies on modern cryptographic methods, usually requiring **vast** amount of time to bruteforce keys used.

## Best practices

### Known protocols

 * Wireguard
 * IPSec v2 (see **strongswan** and **libreswan**)
 * OpenVPN

All of these protocols have a good support in all operating systems.

### How to set it up

We recommend **not to use free services**. They are not safe, they can sniff traffic and sell the metadata of your accesses.

Paid services of known providers are better, but **still not encouraged for sensitive things**.

The best way is to set up your VPN server. It might take a while and won't be free, however, it will be secure and you can be assured in the privacy of your server.

TODO: add manuals
