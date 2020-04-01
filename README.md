# Invenio RFCs

The Invenio RFC process (Request For Comments) is a communication tool with the
purpose to:

- coordinate the design process
- document design decisions
- produce consensus among Invenio stakeholders

### RFC process

1. [Open a new issue](https://github.com/inveniosoftware/rfcs/issues/new) -
  documenting,


### When to write a RFC?

You need to write a RFC to make substantial changes to Invenio. A substantial
change could be:

- Adding/removing larger features and/or modules.
- Changing existing features/APIs.
- Changes of design patterns, idiomatic usage or conventions.

You do not need a RFC for:

- Modules/features you develop privately (you only need it, if you want it as
  an official Invenio module).

If in doubt, just ask on [Gitter](http://gitter.im/inveniosoftware/invenio).


RFCs are per product:

- [Invenio Framework](framework/)
- [Invenio RDM](rdm/)
- [Invenio ILS](ils/)

The RFCs are not meant to be a heavy long process, but rather as an aid to
communicate between geographically dispersed teams as well as to document
Invenio development so that we can avoid knowledge loss when people leaves and
ease knowledge transfer when people joins.



### How to submit a RFC?

- Fork this repository.
- Copy ``0000-template.md`` to ``<product>/0000-<my-title>.md``.
- Fill in the RFC.
- Submit a pull request
- Update your pull request:
    - Rename your ``<product>/0000-<my-title>.md`` to ``<product>/<pull request id with leading zeros>-<my-title>.md`` (e.g. ``rdm/0012-persistent-identifiers.md``).
    - Add a link to the pull request inside the pull request.

### Process (WIP)

The decision process on RFCs have not yet been decided. The plan is to gain
practical experience from the Invenio RDM project and decide on a process by
latest July 2020.

Ideas is very welcome (write them on
https://github.com/inveniosoftware/rfcs/issues/1).

---

The Invenio RFC process owes it's inspiration to the
[Ember RFC process](https://github.com/emberjs/rfcs).
