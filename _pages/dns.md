---
layout: article
title: Domain Name System
permalink: /dns
---

Domain Name System (DNS) is used to convert domain name to IP address.

For example, if you want to reach ``http://no-identity-awesome-example-site.com``, normally your phone or laptop would contact DNS server of your ISP with a question "What it is the IP address of ``no-identity-awesome-example-site.com``?"

The response would contain the IP address and DNS response validity time. That makes it possible to *cache the IP address* locally for this validity time.

## What is in the request

The request to DNS server contains just the domain part:

1. ``http://no-identity-awesome-example-site.com`` would request just ask about ``no-identity-awesome-example-site.com``.
2. ``http://no-identity-awesome-example-site.com/example`` would request just ask about ``no-identity-awesome-example-site.com``, too.
3. ``http://test.no-identity-awesome-example-site.com/example`` would request just ask about ``test.no-identity-awesome-example-site.com``.

## Problems with Virtual Private Networks

When you opt for VPNs, then you might have a few problems:

1. Some DNS server you have no control of might still record the domain names you request. However, if this traffic goes through VPN, it is more or less safe.
2. DNS traffic might go **outside of a tunnel**, making your requests visible to your Internet Service Provider or other owner of DNS server.

## What to do with it

TODO
