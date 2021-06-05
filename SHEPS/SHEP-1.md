---
shep: 1
title: SHEP Purpose and Guidelines
status: Living
type: Meta
author: masashi-shib <masashi.shib@outlook.com>
created: 2021-06-06
---

## What is an SHEP?

SHEP stands for SHIB Ecosystem Proposal. An SHEP is a design document, decision document providing information to the SHIB community, or describing a new initiative for SHIB Ecosystem. The SHEP should provide a concise technical specification of the feature (if possible) and a rationale for the feature. The SHEP author is responsible for building consensus within the community and documenting dissenting opinions.

## SHEP Rationale

We intend SHEPs to be the primary mechanisms for proposing new features, for collecting community input on an issue, and for documenting the design, decisions etc that have gone and will go on into SHIB Ecosystem. Because the SHEPs are maintained as text files in a versioned repository, their revision history is the historical record of the feature proposal.

## SHEP Work Flow

### Shepherding an SHEP

Parties involved in the process are you, the champion or *SHEP author*, the [*SHEP editors*](#shep-editors), and the *SHIB ARMY DEVs*.

Before you begin writing a formal SHEP, you should vet your idea. Ask the SHIB community first if an idea is original to avoid wasting time on something that will be rejected based on prior research. It is thus recommended to open a discussion thread on [SHIB Discor Server] to do this, but you can also use [the SHIB subreddit] or [the Issues section of this repository]. 

Once the idea has been vetted, your next responsibility will be to present (by means of an SHEP) the idea to the reviewers and all interested parties, invite editors, developers, and the community to give feedback on the aforementioned channels. You should try and gauge whether the interest in your SHEP is commensurate with both the work involved in implementing it and how many parties will have to conform to it. Negative community feedback will be taken into consideration and may prevent your SHEP from moving past the Draft stage.

### SHEP Process 

The following is the standardization process for all SHEPs:

**Idea** - An idea that is pre-draft. This is not tracked within the SHEP Repository.

**Draft** - The first formally tracked stage of an SHEP in development. An SHEP is merged by an SHEP Editor into the SHEP repository when properly formatted.

**Review** - An SHEP Author marks an SHEP as ready for and requesting Peer Review.

**Last Call** - This is the final review window for an SHEP before moving to `FINAL`. An SHEP editor will assign `Last Call` status and set a review end date (review-period-end), typically 14 days later.

If this period results in necessary normative changes it will revert the SHEP to `REVIEW`.

**Final** - This SHEP represents the final standard. A Final SHEP exists in a state of finality and should only be updated to correct errata and add non-normative clarifications.

**Stagnant** - Any SHEP in `DRAFT` or `REVIEW` if inactive for a period of 6 months or greater is moved to `STAGNANT`. An SHEP may be resurrected from this state by Authors or SHEP Editors through moving it back to `DRAFT`.

**Withdrawn** - The SHEP Author(s) have withdrawn the proposed SHEP. This state has finality and can no longer be resurrected using this SHEP number. If the idea is pursued at later date it is considered a new proposal.

**Living** - A special status for SHEPs that are designed to be continually updated and not reach a state of finality. This includes most notably SHEP-1. Any changes to these SHEPs will move between `REVIEW` and `LIVING` states.

## What belongs in a successful SHEP?

Each SHEP should have the following parts:

- Abstract - A short (~200 word) description of the issue being addressed.
- Motivation (*optional) - A motivation section is critical for SHEPs that want to change the SHIB Ecosystem. It should clearly explain the problem in a why and the solution in a what form. SHEPs submissions without sufficient motivation may be rejected outright.
- Specification - The technical specification should describe what will be used and how. It is not a must part before reaching the FINAL stage. .

## SHEP Formats and Templates

SHEPs should be written in [markdown] format. There is a [template](../shep-template.md) to follow.

## Linking to other SHEPs

References to other SHEPs should follow the format `SHEP-N` where `N` is the SHEP number you are referring to.  Each SHEP that is referenced in an SHEP **MUST** be accompanied by a relative markdown link the first time it is referenced, and **MAY** be accompanied by a link on subsequent references.  The link **MUST** always be done via relative paths. For example, you would link to this SHEP with `[SHEP-1](./shep-1.md)`.

## Auxiliary Files

Images, diagrams and auxiliary files should be included in a subdirectory of the `assets` folder for that SHEP as follows: `assets/shep-N` (where **N** is to be replaced with the SHEP number). When linking to an image in the EIP, use relative links such as `../assets/shep-1/image.png`.

## SHEP Editors

Names of SHEP Editors still tbdf.

## SHEP Editor Responsibilities

For each new SHEP that comes in, an editor does the following:

- Read the SHEP to check if it is ready: sound and complete. The ideas must make sense, even if they don't seem likely to get to final status.
- The title should accurately describe the content.
- Check the SHEP for language (spelling, grammar, sentence structure, etc.), markup (GitHub flavored Markdown), code style

If the SHEP isn't ready, the editor will send it back to the author for revision, with specific instructions.

Once the SHEP is ready for the repository, the SHEP editor will:

- Assign an SHEP number (generally the PR number or, if preferred by the author, the Issue # if there was discussion in the Issues section of this repository about this SHEP)

- Merge the corresponding pull request

- Send a message back to the SHEP author with the next step.

The editors don't pass judgment on SHEPs. We merely do the administrative & editorial part.

## Style Guide

When referring to an SHEP by number, it should be written in the hyphenated form `SHEP-X` where `X` is the SHEP's assigned number.

## History

This document was derived heavily from [Etherum's BIP-1] which in turn derived from [Bitcoin's BIP-0001] written by Amir Taaki which in turn was derived from [Python's PEP-0001]. In many places text was simply copied and modified. Although the PEP-0001 text was written by Barry Warsaw, Jeremy Hylton, and David Goodger, they are not responsible for its use in the SHIB Ecosystem Improvements.