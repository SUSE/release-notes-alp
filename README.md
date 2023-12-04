== SUSE ALP 1.0 (ALP 1.0) Release Notes

This repository contains release notes for all ALP versions in a single branch.

== How to contribute

For a comprehensive overview, see https://confluence.suse.com/display/documentation/Contributing+to+release+notes.

. Create a new branch with name that includes: your username, the original branch name, and descriptive suffix (e.g. `lkucharczyk-alp10-newfeature`).
. Submit the changes as a pull request.
. Write one sentence per line.
. If there is a related issue, use its Jira or Bugzilla identifier as the section ID (`[#jsc-SLE-1234]`), or if that is not possible, add it as a comment (`// jsc#SLE-1234`).

== Where to add note

. Determine type of note and add it to the appropriate file in the `adoc` folder.
. Determine what variant (Dolomite, Marble etc.) and version (1.0, 1.1 etc.) does your note apply to.
. Surround your note with these tags based on the above, for example:
```adoc
# tag::dolomite-10[]
MY NOTE TEXT HERE
# end::dolomite-10[]
````
This note will only show up in ALP Dolomite 1.0 release notes document.

== Available tags

The currently available tags are the following:

- `dolomite-10`


