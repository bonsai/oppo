# `oppp://` URI Scheme

## Status

Draft / project-private scheme.

`oppp` is the URI scheme for the **oppo / Dial P2** project.

> Strictly speaking, `oppp://` is a URI scheme, not a transport protocol. The URI identifies an object, person, scene, work, or interaction in the oppo world; an implementation may later define the protocol used to resolve or execute it.

## Concept

**oppp = OPPO / Person ↔ Person / Dial P2**

The scheme provides a machine-readable namespace for the fictional and experimental world built around *Dial P2*.

## URI examples

```text
oppp://p2
oppp://person/anonymous
oppp://person/you
oppp://call/p2
oppp://story/dial-p2
oppp://scene/001
oppp://pv/dial-p2
```

## Initial syntax

```text
oppp://<authority>/<path>?<query>#<fragment>
```

The authority and path are intentionally lightweight at this stage. Semantics will be defined as the project develops.

## Design principles

1. `oppp://` is the canonical identifier namespace for the oppo project.
2. Human-readable identifiers are preferred.
3. The URI should remain useful even when no network service exists.
4. Resolution and execution are separate concerns.
5. Fictional resources and real implementation resources should be distinguishable through the path namespace.

## Future

- URI parser
- resolver / router
- browser or desktop handler
- `oppp://` → Web / API / local file mapping
- Dial P2 story-world links
- Remotion PV scene references
- IANA provisional registration, if the scheme becomes sufficiently useful beyond this project

## Standards note

RFC 7595 defines guidelines and registration procedures for URI schemes. A new scheme needs a defined syntax and semantics; provisional registration is available for schemes intended for use beyond a single private environment. For now `oppp` is explicitly a project-private draft and is not claimed to be an IANA-registered scheme.
