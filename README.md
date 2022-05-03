![SSO version](https://img.shields.io/badge/SSO-REC--2.0-yellow)

# Single-Sign-On

[![PDF-Preview](https://img.shields.io/badge/Preview-PDF-blue)](../../releases/download/auto-pdf-preview/SSO-draft.pdf)

## What is it?

SSO: **S**ingle **S**ign **O**n

The [IVOA](http://www.ivoa.net/) single-sign-on architecture is a system in
which users assign cryptographic credentials to user agents so that the agents
may act with the user's identity and access rights. This standard describes how
agents use those credentials to authenticate the user's identity in requests to services.
This standard describes also the authentication mechanism of an application or a service making a call (on behalf of someone or something else) to an API or to another service.
This document is essentially a profile against existing security standards; that is, it describes how an existing standard should be applied in an IVOA application to support single sign-on capabilities in the IVOA. In the following sections, we make specific references to details spelled out in these standards. For the purposes of validating against this standard, those referenced documents should be consulted for a full explanation of those details.

## Status?

The last stable version is
**[REC-2.0](http://www.ivoa.net/documents/SSO/20170524/index.html)**.

Next version will be 2.1. A [Working Draft ] is under discussion. _It is not yet finalized and so, should not be considered yet as stable for operational implementation._

See also the section
[Releases](https://github.com/ivoa-std/SSO/releases) of this GitHub Repository.

## What about this repository?

This GitHub repository contains the sources of the IVOA document describing
 SSO profiles.

Only the LaTeX version is available here. No output version (e.g. PDF, HTML,
DOC) should be stored in this repository.


## Want to contribute?

1. [Raise a GitHub Issue](https://github.com/ivoa-std/SSO/issues/new) on this
   repository

2. Fork this repository _(eventually clone it on your machine if you want to)_

3. Create a branch in your forked repository ; this branch should be named after the issue(s) to fix (for instance: `issue-7-add-license`)

4. Commit suggested changes inside this branch

5. Create a Pull Request on the official repository _(note: a `git push` is needed first, if you are working on a clone)_

6. Wait for someone to review your Pull Request and accept it

_This process has been described and demonstrated during the IVOA Interoperability Meeting of Oct. 2019 in Groningen ; see [slides](https://wiki.ivoa.net/internal/IVOA/InterOpOct2019GitHub/IVOA_Github.pdf))_

## License

[![Creative Commons License](https://i.creativecommons.org/l/by-sa/4.0/88x31.png)](http://creativecommons.org/licenses/by-sa/4.0/)
This work is licensed under a
[Creative Commons Attribution-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-sa/4.0/).
