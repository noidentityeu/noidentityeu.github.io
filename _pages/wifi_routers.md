---
layout: article
title: WiFi routers
permalink: /wifi_routers
---

WiFi routers are evil. Really evil. Let us explain.

### They are everywhere

They are in every house. They are in every cafe. They are in your university. They are in your gym. They are everywhere.

### They have access to all the traffic

Routers practically transit all your traffic through themselves in direction of the wide web and get responses back. They **can** access all your data.

Good news:
1. [HTTPS](/https.html) traffic is encrypted, therere router might catch only source IP and destination IP.
2. Routers have too slow hardware to sniff all your traffic. They can pass it, but they can't record **all of it**.

Therefore, prefer [HTTPS-](/https.html)encrypted channels. If you don't trust the router, use [VPN](/vpn.html).

### They can alter routing of your traffic

Practically routers may send your traffic elsewhere in a way that you're not aware of it.

Good news:
1. [HTTPS](/https.html) connection procedure easily detects unauthorized interventions unless they are protected by trusted certificates.
2. Trusted certificates are not easy to get for domains not belonging to you.

### They might have outdated software

With outdated software, they might pose risk to your home network. Update it as often as you can!

### Routers provided by Internet Service Provider are accessible by ISP

If your router was given by ISP, it has a few issues:
1. It can be reconfigured remotely by ISP.
2. It can be software-updated by ISP.

While it is convenient, consider the country/ISP: **there are many countries in the world that don't deserve trust**.

### Even if just walking around, the router may record your presence

If WiFi router is configured at the same wireless channel as your device resides on currently, router might notice the device and record its MAC. **Effectively, recording that you were there**.

If you care about security, disable WiFi (and even Bluetooth for similar reasons) completely.

## Choose WiFi router you trust

Simple as that. Choose the vendor wisely, considering the country it was built in (due to laws and security services involved!).
