[![Build Status](https://travis-ci.org/WebAssembly/reference-types.svg?branch=master)](https://travis-ci.org/WebAssembly/reference-types)

# Reference Types Proposal for WebAssembly

This repository is a clone of [github.com/WebAssembly/spec/](https://github.com/WebAssembly/spec/).
It is meant for discussion, prototype specification and implementation of a proposal to add support for basic reference types to WebAssembly.

* See the [overview](proposals/reference-types/Overview.md) for a summary of the proposal.

* See the [modified spec](https://webassembly.github.io/reference-types/core/) for details.

Original `README` from upstream repository follows...

# Bulk Memory Operations Proposal for WebAssembly

This repository is a clone of github.com/WebAssembly/spec/. It is meant for
discussion, prototype specification and implementation of a proposal to add
bulk memory operations (e.g. instructions with behavior similar to `memmove`
and `memset`) to WebAssembly.

See the [overview](proposals/bulk-memory-operations/Overview.md) for a summary of the
proposal.

Original README from upstream repository follows...

# spec

This repository holds a prototypical reference implementation for WebAssembly,
which is currently serving as the official specification. Eventually, we expect
to produce a specification either written in human-readable prose or in a formal
specification language.

It also holds the WebAssembly testsuite, which tests numerous aspects of
conformance to the spec.

View the work-in-progress spec at [webassembly.github.io/spec](https://webassembly.github.io/spec/).

At this time, the contents of this repository are under development and known
to be "incomplet and inkorrect".

Participation is welcome. Discussions about new features, significant semantic
changes, or any specification change likely to generate substantial discussion
should take place in
[the WebAssembly design repository](https://github.com/WebAssembly/design)
first, so that this spec repository can remain focused. And please follow the
[guidelines for contributing](Contributing.md).
