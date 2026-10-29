---
weight: 10
title: "Automation Center Documentation (TrendAI)"
icon: "work"
date: "2025-05-04T20:04:55+08:00"
lastmod: "2025-05-04T20:04:55+08:00"
draft: false
toc: true
images: []
---

![TrendAI Vision One Automation center](https://res.cloudinary.com/dttfzpzjn/image/upload/v1748596811/automation-center_fuu7pa.png)

**Role:** Senior Technical Writer / Documentation Engineer
**Period:** October 2021 – June 2025
**Tools:** OpenAPI (YAML), Git, GitHub, Markdown, Redocly, Swagger UI

## Overview

The [Automation Center](https://automation.trendmicro.com/xdr/home/) is the developer portal for the TrendAI Vision One APIs. It gives developers:

- **Automation guides:** step-by-step instructions for automating endpoint protection and building detection and response flows.
- **An interactive API reference:** every endpoint's request and response schemas, generated from OpenAPI specifications.
- **An API cookbook:** practical examples and templates across API versions (v2.0, v3.0).
- **Quickstart guides and code samples** for first-time integrators.

I wrote and maintained the reference content for **100+ REST endpoints** and owned the style and review standards for the portal's documentation.

## How the docs were built

The API reference was generated from OpenAPI YAML files that the engineering teams kept in their own repositories. I worked directly in those repos, using the same tools and review process as the developers:

1. **Interview.** I met with the engineers who owned each API to understand its behavior, edge cases, and intended use.
2. **Write.** I edited or rewrote the `description` fields in the OpenAPI YAML (endpoints, parameters, and schemas) so that a developer could understand each one without asking for help.
3. **Review.** I committed my changes to a branch and opened them for review. The engineers approved the wording for technical accuracy.
4. **Publish.** Once approved, the engineers merged the branch to master and an automated pipeline rebuilt and published the Redocly site. I never published by hand.

Because documentation changes went through the same pull-request process as code, the reference stayed accurate as the APIs changed, and engineers didn't have to learn a separate documentation system.

## My contributions

### API reference content
I rewrote and maintained the descriptions in the OpenAPI specifications for the TrendAI Vision One REST APIs. The engineers owned the spec structure and I owned the language, so my work was on clarity, accuracy, and consistency of what developers read in the reference.

### Style guide
I defined and implemented the style guide for all Automation Center content, covering voice, terminology, and conventions for API descriptions, guides, and cookbooks.

### Documentation review SOP
I created the review process (SOP) for the portal's documentation. It was designed to:

- match the pace of product development, so documentation could ship alongside releases
- feel familiar to developers, because it used the Git and pull-request workflow they already followed
- let the technical writing team respond quickly when documentation changes were needed

### Guides, cookbooks, and code samples
I reviewed and edited the quickstarts, automation guides, cookbooks, and the explanations around code samples. I focused on the written content: whether the steps were clear, the explanations were accurate, and the language matched the style guide. The engineers owned the code in the samples.

## Samples and confidentiality

My drafts and review work for this project are covered by a non-disclosure agreement, so I can't share them. The [published Automation Center](https://automation.trendmicro.com/xdr/home/) shows the final result, which was a team effort.