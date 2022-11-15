[![Build Status][nlfsm-github-action-svg]][nlfsm-github-action]
[![Coverage Status][nlfsm-codecov-svg]][nlfsm-codecov]

[nlfsm-github]: https://github.com/nuovations/nlfsm
[nlfsm-github-action]: https://github.com/nuovations/nlfsm/actions?query=workflow%3Abuild+branch%3Amaster+event%3Apush
[nlfsm-github-action-svg]: https://github.com/nuovations/nlfsm/actions/workflows/build.yml/badge.svg?branch=master&event=push
[nlfsm-codecov]: https://codecov.io/gh/nestlabs/nlfsm
[nlfsm-codecov-svg]: https://codecov.io/gh/nestlabs/nlfsm/branch/master/graph/badge.svg

Nest Labs Finite State Machine
==============================

# Introduction

Nest Labs Finite State Machine (FSM) is designed to provide a
lightweight, simple C++ abstraction useful for implementing FSMs.

The implementer need only define a read-only transition table
consisting of starting state, ending state, and excitation input event
tuples and a delegate to handle upcalls on various transition table
events.

# Interact

There are numerous avenues for nlfsm support:

  * Bugs and feature requests — [submit to the Issue Tracker](https://github.com/nestlabs/nlfsm/issues)
  * Google Groups — discussion and announcements
    * [nlfsm-announce](https://groups.google.com/forum/#!forum/nlfsm-announce) — release notes and new updates on nlfsm
    * [nlfsm-users](https://groups.google.com/forum/#!forum/nlfsm-users) — discuss use of and enhancements to nlfsm

# Versioning

nlfsm follows the [Semantic Versioning guidelines](http://semver.org/) 
for release cycle transparency and to maintain backwards compatibility.

# License

nlfsm is released under the [Apache License, Version 2.0 license](https://opensource.org/licenses/Apache-2.0). 
See the `LICENSE` file for more information.
