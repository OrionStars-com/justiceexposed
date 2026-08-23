# Public Evidence Integrity Ledger

This directory is the public, version-controlled integrity ledger for **The Public Record** documentary archive.

## Permitted content

Only the **Public Integrity Manifest** exported from the protected evidence administrator may be committed here. A public manifest may contain:

- permanent exhibit identifiers;
- public-facing titles and descriptions;
- producing source and case or request reference;
- verification, certification, privacy, and publication status;
- the SHA-256 fingerprint of the approved public copy;
- public-copy filename, format, size, and publication date; and
- non-private publication events.

## Never commit here

This repository is public. Do **not** commit:

- untouched originals that have not been cleared for public release;
- unredacted records or protected personal information;
- private intake or review notes;
- administrator identities or access information;
- internal storage keys;
- the Protected Custody Ledger export;
- confidential, sealed, privileged, or legally restricted material; or
- any document whose provenance and privacy review are incomplete.

## Publication workflow

1. Upload the untouched original through the protected administrator at The Public Record.
2. Record the source, acquisition method, relevant date, and case or request number.
3. Allow the system to calculate the original file's SHA-256 fingerprint and preserve its intake event.
4. Prepare a separate properly redacted public copy when necessary.
5. Review verification, certification, privacy, and publication status.
6. Publish the approved public copy through the administrator.
7. Export the **Public Integrity Manifest** and commit that manifest to this directory.

Replacing a public copy creates a new preserved version and a new fingerprint. Prior public manifests should remain in repository history so changes remain reviewable.

## Important limitation

A cryptographic fingerprint and Git history help demonstrate file integrity and change history. They do not, by themselves, establish every legal requirement for authentication, admissibility, source certification, or chain-of-custody foundation.
