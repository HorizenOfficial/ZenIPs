# ZenIP Template

*If this is your first time writing a ZenIP, the structure and format may look intimidating. But really, it's just meant to reflect common-sense practice and some technical conventions. This template is meant to be a starting point for you to structure your ideas. It might help to sort the different aspects of your proposal into the structure below in order get your idea across efficiently. The community and ZenIP editors will help you figure things out and get your proposal into a proper shape later.*

## Header Preamble

    ZenIP: Unassigned (numbers are assigned by ZenIP editors)
    Title: *Something Short and To the Point*
    Owners: First Owner <email>
    ...
    Status: Draft
    Category: (Consensus | Standards Track |Informational | Process)
    Created: yyyy-mm-dd
    License: MIT (see the licensing section of ZenIP-42000)

## Table of Contents

*Please always include a table of contents, e.g.*

## Terminology

The key words "MUST", "MUST NOT", "SHOULD", and "MAY" in this document are to
be interpreted as described in [RFC 2119](#references).

The terms below are to be interpreted as follows:

- Term to be defined
  - definition
- Another term
  - another definition

## Abstract

*Describe what this proposal does, typically in a few paragraphs.*

The Abstract should only provide a summary of the ZenIP; the ZenIP should remain complete without the Abstract.
Use links where applicable, e.g. [[3]](#references).

## Motivation

*Why is this proposal needed?*

This is one of the most important sections of the ZenIP, and should be detailed
and comprehensive. It shouldn't include any of the actual specification -
don't put conformance requirements in this section.

Explain the status quo, why the status quo is in need of improvement,
and if applicable, the history of how this area has changed. Then describe
*at a high level* why this proposed solution addresses the perceived issues.
It is ok if this is somewhat redundant with the abstract, but here you can
go into a lot more detail.

## Requirements

*Describe design constraints on, or goals for the solution -- typically one paragraph for each constraint or goal.*

Again, don't actually specify anything here; this section is primarily for use as a consistency check that what is specified meets the requirements.

## Non-requirements

*This section is entirely optional. If it is present, it describes issues that the proposal is **not** attempting to address, that someone might otherwise think it does or should.*

## Specification

*This section describes what should change, using precise language and conformance key words.*

Anything that is *required in order to implement the ZenIP* (or follow its
process, in the case of a Process ZenIP) should be in this section.

Avoid overspecification! Also avoid underspecification. Specification is hard.
Don't be afraid to ask for help.
Unless the specification is particularly simple, you will need to organise it under
subheadings.

### Example Subheading

At least while the ZenIP is in Draft, we encourage writing open questions and TODOs.

#### Open Questions

- What do hackers do on a boat?

TODO: define byte encoding for the phishing trip.

Feel free to copy from other ZenIPs doing similar things.

## Reference Implementation

This section is entirely optional; if present, it usually gives links to PRs.

## References

[1] ZenIP-42000 - https://github.com/HorizenOfficial/zenips/blob/master/zenip-42000.md/#zenip-licensing

[2] RFC2119 - Key words for use in RFCs to Indicate Requirement Levels https://tools.ietf.org/html/rfc2119

[3] Example reference
