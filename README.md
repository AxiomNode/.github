# org-porfile

Last updated: 2026-05-03.

## Responsibility

`org-porfile` stores organization-level public profile material for AxiomNode.

It exists to keep profile and presentation assets separate from runtime, infrastructure, and cross-repository engineering documentation.

## Runtime role

This repository is a low-coupling content repository, not a runtime or deployment repository.

Its main role is to hold profile-facing content under `profile/` without mixing that material into the platform codebase.

## Runtime surface

- `profile/README.md`: current public-facing organization profile content
- `LICENSE`: repository license terms

## Documentation

- `profile/README.md`

## Local setup

No build or runtime setup is required for normal maintenance of this repository.

## Dependencies and contracts

- content should stay consistent with the current platform naming and repository map
- engineering and architecture truth remains owned by the central `docs` repository, not by this profile repository

## Deployment and operations notes

- this repository is not part of the automated runtime delivery chain
- changes are content-oriented and should avoid exposing internal operational detail or stale architecture claims
- the repository name is intentionally preserved as-is even though it contains a spelling inconsistency

## References

- `profile/README.md`
- `../docs/guides/capabilities/platform/organization-profile-publishing.md`
- `../docs/README.md`