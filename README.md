# proof

![License](https://img.shields.io/badge/license-Apache--2.0-blue)
![Role](https://img.shields.io/badge/role-proof%20publication%20surface-111111)
![Deploy](https://github.com/Verifrax/proof/actions/workflows/pages.yml/badge.svg?branch=main)
![Host](https://img.shields.io/badge/host-proof.verifrax.net-1f6feb)

Public proof-publication repository for `https://proof.verifrax.net/`, responsible for publishing inspectable proof material and certificate-facing retrieval surfaces without becoming the verifier, authority issuer, governed execution runtime, intake surface, archive surface, documentation root, or evidence-root chain authority.

## Proof artifacts

This repository is part of the VERIFRAX proof perimeter.

- **ARTIFACT-0006**
- **ARTIFACT-0005**
- **ARTIFACT-0004**
- **ARTIFACT-0003**
- **ARTIFACT-0002**
- **ARTIFACT-0001**

**Canonical public proof surface:** https://proof.verifrax.net  
**Canonical proof publication repository:** https://github.com/Verifrax/proof  
**Canonical evidence root:** https://github.com/Verifrax/VERIFRAX

## Terminal planes

- **[ANAGNORIUM](https://github.com/Verifrax/ANAGNORIUM)** — terminal recognition
- **[REGRESSORIUM](https://github.com/Verifrax/REGRESSORIUM)** — terminal recourse

## Status

* Repository role: public proof publication surface only
* Public host ownership: `proof.verifrax.net`
* Surface class: public-facing proof and certificate publication boundary
* Deployment model: proof publication surface owned only by this repository
* Package status: repository surface only unless package metadata explicitly proves otherwise
* Stack position: publication surface downstream of authored source and governed execution, separate from verifier tooling
* Artifact-chain relation: publication-facing perimeter aligned with the broader chain, but not the authority issuer, receipt emitter, or root artifact registry
* License: Apache License Version 2.0

## One-sentence role

`proof` owns `https://proof.verifrax.net/` and publishes public proof material, certificate-facing retrieval paths, and stable proof-publication semantics while remaining separate from verification tooling, authority issuance, governed execution, archive/catalog history, intake, and evidence-root chain registration.

## What this repository is

This repository is the public proof publication boundary.

Its job is to make proof material publicly retrievable under one dedicated host.

It exists so a reader can:

* open `https://proof.verifrax.net/`
* access public proof-facing material under a dedicated proof surface
* inspect certificate-facing or proof-facing publication paths
* retrieve public proof material without converting the verifier into the publisher
* keep proof publication separate from authority issuance
* keep proof publication separate from governed execution
* keep proof publication separate from archive/catalog history

This repository owns publication only.

Publication is not verification. Publication is not authority. Publication is not execution. Publication is not archive truth.

That means the correct system split is:

* authority comes from `AUCTORISEAL`
* execution and receipts come from `CORPIFORM`
* authored source and evidence-root chain truth live in `VERIFRAX`
* public proof publication lives here
* public verification lives in `VERIFRAX-verify`
* seal/archive reference lives in `SIGILLARIUM`

## What this repository is not

`proof` is not:

* the public verifier repository
* the authority layer
* the governed execution runtime
* the intake surface
* the commercial surface
* the archive/catalog repository
* the docs repository
* the status repository
* the evidence-root artifact registry
* the issuer of authority objects
* the emitter of CORPIFORM receipts
* the canonical authored source repository

It does not:

* own `https://verify.verifrax.net/`
* own `https://api.verifrax.net/`
* own `https://auctoriseal.verifrax.net/`
* own `https://corpiform.verifrax.net/`
* own `https://sigillarium.verifrax.net/`
* own `https://apply.verifrax.net/`
* verify proof material as the main verifier surface
* execute governed actions
* issue authority objects
* archive seal history as the archive surface
* register artifact-0005 in the evidence root

Publication is not verification.
Publication is not authority.
Publication is not execution.
Publication is not archive truth.

If any of those collapse together, the README is wrong.

## Verifrax system path labels

The governed Verifrax path that this README must stay compatible with is:

1. `.github` — organization governance and governed repository boundary
2. `AUCTORISEAL` — authority issuance and public authority reference
3. `CORPIFORM` — governed execution and receipt emission
4. `VERIFRAX` — authored protocol, evidence root, and artifact-chain registration boundary
5. `VERIFRAX-SPEC` — derived specification publication surface
6. `VERIFRAX-PROFILES` — deterministic profile-constraint surface
7. `VERIFRAX-SAMPLES` — pinned sample and reproducibility surface
8. `VERIFRAX-verify` — public verification repository and UI boundary
9. `VERIFRAX-DOCS` — explanatory documentation surface
10. `cicullis` — enforcement boundary
11. `proof` — proof publication surface
12. `SIGILLARIUM` — seal and archive reference surface
13. `apply` — intake surface

The live host-label map that must remain explicit and non-contradictory is:

* `https://api.verifrax.net/` — execution surface
* `https://proof.verifrax.net/` — proof publication surface
* `https://auctoriseal.verifrax.net/` — authority issuance and authority reference surface
* `https://corpiform.verifrax.net/` — runtime and receipt reference surface
* `https://cicullis.verifrax.net/` — enforcement reference surface
* `https://verify.verifrax.net/` — public verification surface
* `https://sigillarium.verifrax.net/` — seal and archive reference surface
* `https://apply.verifrax.net/` — intake surface
* `https://docs.verifrax.net/` — documentation surface

This README must remain compatible with `artifact-0005` as the load-bearing authority → execution → verification → evidence boundary without claiming that this repository alone authors, proves, seals, or registers `artifact-0005` unless that role is actually true for this repository.

## Public host ownership

This repository owns exactly this public host:

* `https://proof.verifrax.net/`

It does not own:

* `https://verify.verifrax.net/`
* `https://api.verifrax.net/`
* `https://auctoriseal.verifrax.net/`
* `https://corpiform.verifrax.net/`
* `https://sigillarium.verifrax.net/`
* `https://apply.verifrax.net/`
* `https://docs.verifrax.net/`
* `https://status.verifrax.net/`

A proof README must state this bluntly so no second host is silently claimed.

## Position in the Verifrax system

The main perimeter is intentionally split:

* [`.github`](https://github.com/Verifrax/.github) — governance root
* [`VERIFRAX`](https://github.com/Verifrax/VERIFRAX) — authored source, maintained implementation surface, and evidence-root chain record
* [`AUCTORISEAL`](https://github.com/Verifrax/AUCTORISEAL) — authority issuance and authority reference
* [`CORPIFORM`](https://github.com/Verifrax/CORPIFORM) — governed execution and receipt boundary
* [`proof`](https://github.com/Verifrax/proof) — public proof publication repository
* [`VERIFRAX-verify`](https://github.com/Verifrax/VERIFRAX-verify) — public verifier repository
* [`SIGILLARIUM`](https://github.com/Verifrax/SIGILLARIUM) — seal/archive reference repository

This repository occupies the proof-publication slot only.

## Proof versus verify

This line must remain hard.

### `proof.verifrax.net`

* publishes proof material
* exposes proof retrieval semantics
* is the public publication surface

### `verify.verifrax.net`

* verifies or inspects proof-shaped material
* is the public verification tooling surface
* must remain distinct from publication

A limiting case makes the boundary obvious:

A proof page can publish a certificate perfectly and still not be the verifier.
A verifier can inspect a proof perfectly and still not be the proof publisher.

If both repos claim both jobs, there are two canonical surfaces for one function. That is immediate drift.

## Proof versus archive

This repository is not the archive/catalog boundary.

That belongs to `SIGILLARIUM`.

So this repository may publish active proof-facing material, but it must not rewrite itself into the historical seal/archive reference surface.

Another limiting case:

A live proof page is not automatically the permanent archive of all seals, all historical bundles, or all archive-grade records.

If the README starts implying that, it is stealing the archive role.

## Proof versus authority

Proof publication does not issue authority.

This repository can publish material that points to or depends on authority, but it cannot mint authority state, repair authority state, or replace `AUCTORISEAL`.

Authority remains upstream.
Proof publication remains downstream.

## Proof versus execution

This repository does not execute governed commands.

It does not:

* authorize an action
* run the governed runtime
* emit a CORPIFORM receipt
* enforce replay resistance
* become the execution API

Execution belongs to `CORPIFORM` and the governed runtime boundary.

A proof page may display a result of execution.
It is not the system that executed it.

## Artifact-0005 relationship

`artifact-0005` must remain visible across the repo perimeter because it is load-bearing chain context in the wider Verifrax system.

But the relationship here must stay precise.

This repository is relevant to artifact-0005 because public proof publication is part of the outward inspection path around the chain.

This repository is not relevant in these false ways:

* it does not author artifact-0005
* it does not issue the authority object for artifact-0005
* it does not emit the governed receipt for artifact-0005
* it does not register artifact-0005 in the evidence root
* it must not claim artifact-0005 is sealed unless the evidence-root chain truth actually says so

The truthful sentence is narrower:

this repository is part of the public proof-facing perimeter that must remain aligned with artifact-0005 and its inspectable publication path where applicable.

## What problem this repository solves

Without a dedicated proof-publication repository, systems usually fail in one of two ways:

* proof material is scattered through an execution host that should not be serving publication bodies
* proof publication and verification collapse into one ambiguous surface

This repository solves that by giving proof publication one dedicated home.

It keeps publication visible without turning the verifier into the publisher, the runtime into the public proof site, or the archive into the live proof surface.

## Surface contract

This repository should describe only publication surfaces that are really present.

A truthful proof-publication contract can include surfaces such as:

* proof landing material
* certificate-facing routes
* machine-readable proof retrieval routes where intentionally published
* stable public proof paths
* public publication semantics for inspectable proof material

It must not claim:

* governed execution ownership
* verifier ownership
* archive/catalog ownership
* authority issuance ownership
* evidence-root registration ownership

## Inputs and outputs

### Inputs

This repository publishes proof-facing material derived from the wider Verifrax system boundary.

### Outputs

This repository emits publication-facing proof outputs only.

It does not emit:

* authority objects
* governed execution receipts
* verifier verdicts as the verifier surface of record
* archive/catalog records as the archive surface of record
* root artifact registrations

## Package truth boundary

This README must not imply a public package surface unless metadata proves one exists.

So the safe boundary is:

* repository surface: yes
* public proof host: yes
* package claim: only if mechanically proven elsewhere in package metadata

That rule matters because surface repositories often drift into fake package claims.

## Why this repository must stay visually and mechanically distinct

A proof publication surface should never feel like:

* the verifier UI
* the execution API
* the authority host
* the intake site
* the docs root
* the archive/catalog host

The reader must know within seconds:

this is the proof publication surface.
Nothing else.

## Canonical related repositories and surfaces

* [`.github`](https://github.com/Verifrax/.github) — governance root
* [`VERIFRAX`](https://github.com/Verifrax/VERIFRAX) — authored source and evidence-root chain record
* [`AUCTORISEAL`](https://github.com/Verifrax/AUCTORISEAL) — authority issuance/reference
* [`CORPIFORM`](https://github.com/Verifrax/CORPIFORM) — governed execution and receipt boundary
* [`VERIFRAX-verify`](https://github.com/Verifrax/VERIFRAX-verify) — public verifier repository
* [`https://proof.verifrax.net/`](https://proof.verifrax.net/) — public proof publication surface
* [`https://verify.verifrax.net/`](https://verify.verifrax.net/) — public verifier surface
* [`SIGILLARIUM`](https://github.com/Verifrax/SIGILLARIUM) — seal/archive reference repository

## Reader contract

A reader landing here must be able to answer immediately:

1. Is this the proof publication repository? Yes.
2. Does it own `proof.verifrax.net`? Yes.
3. Is it the verifier repository? No.
4. Is it the authority repository? No.
5. Is it the execution runtime repository? No.
6. Is it the archive/catalog repository? No.
7. Is it part of the public proof-facing perimeter around artifact-0005? Yes.

If any of those answers are blurry, the README is still weak.

## CI and governance expectations

If CI exists here, it should validate publication-surface properties only, such as:

* deployment alignment with `proof.verifrax.net`
* build integrity for proof-facing assets
* route and host consistency
* no drift between claimed proof host and deployed proof host
* no accidental collision with verifier or archive roles

A green build here does not prove authority truth, execution truth, or chain registration truth.

## Contributing

A contribution here is wrong if it:

* turns the proof repository into the verifier repository
* turns the proof repository into the archive repository
* turns the proof repository into the authority surface
* turns the proof repository into the execution runtime
* adds package claims not backed by metadata
* claims artifact-0005 is sealed without evidence-root backing
* blurs proof-versus-verify
* blurs proof-versus-archive
* blurs proof-versus-execution
* blurs proof-versus-authority

## Security

Treat this repository as a public proof-publication surface.

Do not introduce:

* hidden authority logic
* hidden execution behavior
* secret-dependent publication semantics
* silent verifier coupling that makes proof and verify indistinguishable

## License

Apache License Version 2.0. See `LICENSE`.

## Adjacent sovereign surfaces

This repository is part of the Verifrax sovereign stack and remains bounded relative to:

- **[ANAGNORIUM](https://github.com/Verifrax/ANAGNORIUM)** for terminal recognition
- **[REGRESSORIUM](https://github.com/Verifrax/REGRESSORIUM)** for terminal recourse
