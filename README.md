# SUSE ALP 1.0 (ALP 1.0) Release Notes

This repository contains release notes for SUSE ALP written in [AsciiDoc](https://docs.asciidoctor.org/asciidoc/latest/).


## How to contribute

See [CONTRIBUTING.md](CONTRIBUTING.md).

## Where to add note

1. Determine type of note and add it to the appropriate file in the `adoc` folder.
2. Determine what variant (ALP, Micro) and version (1.0, 1.1 etc.) does your note apply to.
    1. If ALP: surround your note with these tags based on the above, for example:
    ```adoc
    # tag::alp-10[]
    MY NOTE TEXT HERE
    # end::alp-10[]
    ```
    This note will only show up in ALP Dolomite 1.0 release notes document.
    
    2. If Micro: add the note to the relevant document with `-micro` suffix and include it in `release-notes-micro.adoc`

## Available tags

The currently available tags are the following:

- `dolomite-10`