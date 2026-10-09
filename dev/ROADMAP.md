# git-io - Roadmap

> Path from scaffold to a stable 1.0. Hard parts are front-loaded; each phase has hard exit criteria.
> Master plan: C:/Dev/libraries/Rust/lang-collection/_lexersketch/ROADMAP.md and NEW-LIBS.md
>
> **Anti-deferral rule:** no listed hard task moves to a later phase unless this file records the move and the reason.

## v0.1.0 - Scaffold (DONE)
Compiles, CI green, structure correct, no domain logic.
- [x] Manifest, README, CHANGELOG, REPS, dual license, CI, deny, clippy, rustfmt, DIRECTIVES, ROADMAP.

## v0.2.0 - Foundation
- [ ] Object model, SHA-1/SHA-256 object ids, loose objects, packfile writer and reader, refs; offline tests with git as a dev-only oracle. Blocked on the owner's SHA and DEFLATE libraries for the shipping build (TLS-CRYPTO handoff); record the interim.

## v0.5.0 - Implementation
- [ ] Smart-HTTP fetch and push over the owner's HTTP/TLS client; GitHub authentication via key-vault.

## v0.9.0 - Hardening
- [ ] Fuzzing readers; interop matrix.

## v1.0.0 - Stable
- [ ] Frozen after LexerSketch publishes a language with it (D18).
