---
layout: article
title: HTTPS
permalink: /https
---

Hypertext Transfer Protocol **Secure** (HTTP**S**) is an important part of modern security in the Internet.

## HTTP is not secure

The default (and outdated) protocol is HTTP. It is not secure by any means. All the data you send over it is not encrypted. Practically anyone with an access to the wire between you and the target website may see what you send and what you receive.


## HTTPS is secure

HTTPS is an extension over HTTP. First of all, you may determine it by ``https://`` protocol in the URL bar. Second, there might be some image of lock. If you press on it, you might find the information about the certificate.

Security of HTTPS lies on the framework of asymmetrical encryption. The website owner has the private key, and the user gets the public certificate for it so that user might decrypt the data.

All certificates are issued by the upstream Certificate Authority. Root certificate authorities are trusted organizations that have their certificates in certificate stores of major operating systems. They have built their trust. If private key is compromised, they revoke the certificate completely.

## Practical moments

1. Prefer HTTPS to HTTP at least for critical data, but better for all uses.
2. If you see certificate warnings, don't visit the website unless you know what's happening.
3. If the certificate has expired, don't visit the website unless you know that it is not important.
