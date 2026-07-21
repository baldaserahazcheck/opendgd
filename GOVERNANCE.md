# OpenDGD Governance

## Steward

OpenDGD is published and stewarded by the **OpenDGD maintainers**. It generalises a production IMDG
classification and declaration engine into an open standard. The maintainers keep the specification,
the reference implementation and this repository.

## Principles

1. **Open by construction.** The specification, JSON Schema, rendering algorithm and conformance suite
   are openly licensed (see [`LICENSE`](LICENSE)). Anyone may implement OpenDGD, free of charge, without
   permission or licensing a commercial engine.
2. **Vendor-neutral format, competitive validation.** The *data format* and *rendering* are the shared,
   open commons. How deeply an implementation *validates* a declaration against the IMDG Code is where
   products differ.
3. **The IMDG Code governs.** Where OpenDGD and the IMDG Code disagree, the Code wins. OpenDGD tracks
   IMDG amendments via `regulation.edition` and never contradicts them.
4. **Backward compatibility.** Changes are additive within a MAJOR version. Breaking changes ship with a
   migration note and a MAJOR bump.
5. **Public process.** Changes happen in the open (see [`CONTRIBUTING.md`](CONTRIBUTING.md)).

## Decision-making (v0.x)

While the standard is young, the maintainers act as editors. Every substantive change is proposed as a
public issue/PR with a rationale, given a comment period, and recorded in the changelog. The maintainers
will not merge a breaking change without a migration path.

## Path to neutral governance (→ v1.0)

OpenDGD is intended to outlast any single vendor. As independent implementations and industry adopters
(carriers, forwarders, terminals, authorities) come on board, the maintainers will convene an **OpenDGD
Steering Group** with representation beyond the founding maintainers, and transfer editorial control of
the specification to it before declaring v1.0.

## Conformance mark

A future "OpenDGD Conformant" mark (for renderers and servers that pass the conformance suite) may be
administered by the Steering Group. Until then, conformance is self-declared against the public
conformance suite.

## Contact

- Web: [opendgd.org](https://opendgd.org)
- Issues & proposals: this repository
