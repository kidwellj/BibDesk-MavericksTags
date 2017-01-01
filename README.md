BibDesk-OMTags
=====================

An applescript for embedding a lightweight version of bibdesk citation information in the relevant PDF attachments, especially designed for a bibdesk/devonthink workflow. This script is just a lightly hacked version of [Derick Fay's bibdesk-maverickstags scripts][https://github.com/derickfay/BibDesk-MavericksTags]

### Dependencies

Install https://github.com/jdberry/tag first

## keywords2tags

Adds the Keywords from the current selection in BibDesk to all linked files as Mavericks tags.

limitations:
- fails ungracefully if there is a broken link to a file in BibDesk

to do:
- two way sync to add any existing Mavericks tags back to BibDesk
- could update to use jdberry's tag rather than kludgy Applescript
