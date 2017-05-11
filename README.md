# Placeholders
A reference for placeholder data. These are data that are designed to be used in tests or examples, which are "obviously invalid" or do not work in production scenarios.

## Domain names

[RFC2606](https://tools.ietf.org/html/rfc2606#page-2) guarantees that the following TLDs will not be registered:

* `.example`: for use in documentation or examples
* `.test`: for use in tests
* `.invalid`: catch-all invalid TLD

`.localhost` is also guaranteed to never be registered.

## IP Addresses

[RFC 5737](https://tools.ietf.org/html/rfc5737#section-3) reserves the following IPv4 blocks for test or documentation purposes:

* `192.0.2.0/24` ("TEST-NET-1")
* `198.51.100.0/24` ("TEST-NET-2")
* `203.0.113.0/24` ("TEST-NET-3")

[RFC 3849](https://tools.ietf.org/html/rfc3849#section-2) reserves the following IPv6 block for test or documentation purposes:

* `2001:db8::/32`
