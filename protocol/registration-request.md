# `oppp` URI Scheme Registration Draft

This document is a future registration draft, not an IANA submission.

| Field | Value |
|---|---|
| Scheme name | `oppp` |
| Status | Provisional candidate / project-private draft |
| Applications/protocols | OPPO / Dial P2 world identifiers |
| Contact | bonsai |
| Change controller | bonsai / oppo project |
| Reference | `https://github.com/bonsai/oppo` |

## Scheme semantics

`oppp` identifies resources, entities, scenes, calls, stories, and other objects belonging to the OPPO / Dial P2 namespace.

Example:

```text
oppp://p2
oppp://person/anonymous
oppp://call/p2
oppp://story/dial-p2
```

The scheme does not itself specify a transport. A resolver MAY map an `oppp` URI to a local application, Web resource, API operation, file, or fictional world object.

## Rationale

`oppp://` is intended to turn the Dial P2 fictional concept into an addressable namespace. It can therefore become the connective layer between the novel, research corpus, PV scenes, Remotion compositions, and future interactive implementations.

## Registration path

RFC 7595 recommends checking the IANA URI Schemes registry, defining syntax and semantics, and using the provisional registration path for schemes intended for broader use. If `oppp` matures beyond the private project, this document can be expanded into an IANA provisional registration request.
