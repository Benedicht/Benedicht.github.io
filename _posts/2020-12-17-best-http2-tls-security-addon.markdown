---
layout: post
title: Best HTTP/2 - TLS Security Addon (2020 - present)
description: Implementing a good certification validatation isn't an easy task, but this addon aims even higher. It implements the same steps a browser does to ensure the communication over the negotiated connection is safe and secure. Additionally provides a management window to easily manage trusted certificates, update and test them.
img: posts/tlssecurity/IconImage_160x160.jpg
---

# About

Implementing a good certification validatation isn't an easy task, but this addon aims even higher. It implements the same steps a browser does to ensure the communication over the negotiated connection is safe and secure. Additionally provides a management window to easily manage trusted certificates, update and test them.
This addon implements all certification verification steps a browser normally do and additionally provides a management window to easily manage trusted certificates, update and test them.

Take a step further to improve the security of all protocols connecting through a TLS connection with a one line setup. Works with **all** protocols Best HTTP/2 supports.

All source code included. Requires the latest version of [Best HTTP/2](https://assetstore.unity.com/packages/tools/network/best-http-2-155981?aid=1101lfX8E).

## Features

- Certificate Chain Verification as described in [RFC 3280](https://tools.ietf.org/html/rfc3280)
- Revocation checking of leaf certificates using OCSP with optional soft and hard fail
- Caching OCSP responses
- Support for [OCSP Must-Staple](https://casecurity.org/2014/06/18/ocsp-must-staple/)
- Trusted Root CA, Trusted Intermediate and Client Credentials management through an easy to use [Certification Manager Window](CertificationManagerWindow.md) to
	1. Update all certificates from a trusted source
	2. Add custom certificates
	3. Delete non-needed certificates
- Domain Name Matching
- [Client Authentication](https://comodosslstore.com/blog/what-is-ssl-tls-client-authentication-how-does-it-work.html)
- Wide variety of options to configure almost every bits of the addon

## Links

- [Asset Store Page](https://assetstore.unity.com/packages/tools/network/best-http-2-tls-security-addon-184441?aid=1101lfX8E)
- [Online Documentation](https://besthttp-documentation.readthedocs.io/en/latest/#8.Addons/TLSSecurity/)