---
title: Specs
linkTitle: Specification
menu: { main: { weight: 35 } }
cascade:
  type: docs
---

## Overview

The Update Framework provides a set of libraries, file formats, and utilities
that can be used to secure new and existing software update systems.

The framework enables applications to be secure from all known attacks on the
software update process. It is not concerned with exposing information about
what software is being updated (and thus what software the client may be
running) or the contents of updates.

The framework provides means to minimize the impact of key compromise. To do so,
it must support roles with multiple keys and threshold/quorum trust (with the
exception of minimally trusted roles designed to use a single key).

The compromise of roles using highly vulnerable keys should have minimal impact.
Therefore, online keys (keys which are used in an automated fashion) must not be
used for any role that clients ultimately trust for files they may install.

The framework is flexible enough to meet the needs of a wide variety of software
update systems.The framework must be easy to integrate with software update
systems.

Learn more about the spec from our latest
[specification](https://theupdateframework.github.io/specification/latest/)
docs.
