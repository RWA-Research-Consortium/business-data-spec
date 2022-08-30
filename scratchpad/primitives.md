This document is my initial thoughts on how to develop primitives, what they should look like and why.

- Standards comprise a layer that others can build on top of (composability)
  - `[ [ Unique Asset ] [ Digital Representation ] [ Conflict Resolution] ]`
  - => Legal Recognition => Market Adoption

- What atomic primitives are necessary to represent real property ownership?

- real thing =>
  - unique characteristics: **what** makes it non-fungible?
  - who is the steward of the asset?
    - structure is discrete
    - provenance = chronologically ascending sorted list of stewardship structures
    - linguistically: don't call it ownership => make as few assumptions here as possible
      - private ownership
      - public ownership
      - no ownership
      - partial common ownership
      - enables creativity for new forms of ownership
- digital representation
  - unique hash of the **what**
- conflict resolution
  - each title *should* be unique
    - only 1 valid representation of the unique characteristics (by definition)
    - may be multiple valid representations of ownership
  - enforcement: finding and resolving conflicts
  - finding
    - easiest but complex: standard that all applications use
      - why use it?
        - to ensure their titles are legally clear of title disputes
        - "standards & database as the legal authority i.e. the final word as far as the law is concerned"

