# asolaria-record-231-canonical

The photographic record of Jesse Daniel Brown, in his own numbering.

## What is here

| path | what it is |
|---|---|
| `photos/` | 231 photographs, numbered `001`–`231`, each keeping its original camera filename after the number |
| `MAPPING.tsv` | the canonical index: number, path, original filename, byte size, SHA-256 |
| `CHECKSUMS-231.sha256` | machine-checkable form of the same, for `sha256sum -c` |
| `OBSERVATION.md` | the written observation document, 8,194 lines |
| `sections/` | 59 written section files |

## Provenance of the numbering

The numbering is not assigned here. Every photograph was placed by matching its
SHA-256 against the hash already recorded in `MAPPING.tsv`, which predates this
upload. No frame was selected, judged, cropped, reordered or opened in the
course of assembling this repository. A hash matched a row, and the file took
that row's number.

`230-1785779142945.jpeg` agrees byte-for-byte with the same frame in the
owner's separate three-photograph standalone.

## Verifying

    sha256sum -c CHECKSUMS-231.sha256

231 lines, all OK.

## Status of the written observations

    PRESENT   sections 42-57, 97-125, 132-149      59 files
    ABSENT    all other numbers in 1-231          172 numbers

The absent sections were never written. They are not missing from this
repository; they do not exist yet.

## Ownership

The owner names and organizes this repository as he chooses.
