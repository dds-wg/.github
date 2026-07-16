# Governance

## The Project

DDS, the Decentralized Deliberation Stack, is an open project and W3C Community Group for sovereign, verifiable, interoperable, and resilient deliberation. Work happens in public in the [DDS GitHub organization](https://github.com/dds-wg) and through the [W3C DDS Community Group](https://www.w3.org/community/dds/).

DDS is not covered by a single licence. Specification work follows the W3C Community Group contribution process. The website and proof-of-concept software are licensed under MPL-2.0 unless another licence is explicitly stated. See the [`dds` licence map](https://github.com/dds-wg/dds/blob/main/COPYING-README.md).

The project is designed to be interoperable and modular. We actively try to accommodate the diverse use-cases of individuals and teams, and that flexibility is what makes it flourish. When conflicts arise between competing needs, however, decisions must be made that preserve consistency and the project's core objectives.

This document is the project's public operational agreement for governance, GitHub access, and official project tool administration. It does not replace the [W3C Community and Business Group Process](https://www.w3.org/community/about/process/), the [W3C Code of Conduct](https://www.w3.org/policies/code-of-conduct/), the [W3C Community Contributor License Agreement](https://www.w3.org/community/about/process/cla/), the [W3C Community Final Specification Agreement](https://www.w3.org/community/about/process/final/), or applicable [W3C report requirements](https://www.w3.org/community/reports/reqs/).

## Governance Philosophy

DDS is both a project and a Community Group. It stewards the Decentralized Deliberation Stack, whose scope is intentionally broad and meta: it tries to connect protocols, products, and communities across different deliberation use-cases. That openness is important, but it also means the work needs a clear and coherent vision to hold the pieces together.

When use-cases conflict, we try first to make room for all of them rather than choosing one too early. The goal is to find shared abstractions, sometimes surprising ones, that let different teams benefit from the stack to the greatest extent possible, including niche or emerging use-cases. This flexibility has a limit: accommodating a use-case should not make the project incoherent or prevent others from building on the shared foundation.

We value broad participation and rough consensus. At the same time, some deadlocks are inevitable in a project with this scope and level of abstraction. The BDFL role exists to preserve continuity and coherence when consensus cannot produce a clear direction. This is not a substitute for public discussion, W3C Community Group process, or contributor influence. It is a guardrail against fragmentation and against decisions that would undermine the project's core objectives.

The BDFL and Chairs are expected to act as facilitators for the Community Group. Their role is to help participants surface disagreement, clarify trade-offs, and move toward decisions that remain coherent with the project's goals. This mirrors the deliberative practice DDS aims to support: facilitation should make collective reasoning easier, not replace it.

## Roles

### Contributor

Anyone who opens an issue or submits a pull request. No approval needed. Influence comes from the work, not from titles. Contributors remain external by default until they have earned repository access through trust, sustained quality contributions, and willingness to help others.

### Maintainer

A Contributor who has earned write or maintain access to one or more DDS GitHub repositories by demonstrating sustained, quality contributions and a willingness to help others, not just advance their own interests. Maintainers may be members of the DDS GitHub organization or may have access only to specific repositories. Joining the W3C DDS Community Group on w3.org does not automatically make someone a Maintainer.

Maintainers manage repository operations: triaging issues, reviewing and merging pull requests, maintaining CI, keeping documentation usable, and stewarding website and proof-of-concept work. Maintainer authority does not by itself determine W3C Community Group consensus, Community Group report publication, or W3C process questions. Chairs and the BDFL appoint Maintainers; a Maintainer inactive for a year may be removed after being given a chance to return.

### W3C DDS Community Group Chairs

The W3C DDS Community Group chairs coordinate and facilitate the W3C Community Group process, including group participation, specification consensus, report publication, and W3C process alignment. The Chairs are responsible for ensuring the group follows W3C requirements and this public operational agreement. They are the primary contacts for W3C Community Group process matters.

Chairs are co-owners of the DDS GitHub organization associated with the W3C DDS Community Group. Chairs and the BDFL may appoint Maintainers.

Current chairs:

- **Simone Vagnoni** ([@Stocastico96](https://github.com/Stocastico96))
- **Nicolas Gimenez** ([@nicobao](https://github.com/nicobao)), current BDFL
- **Lee DeSota** ([@salteelee](https://github.com/salteelee))

### BDFL

Initiated the W3C DDS Community Group and set the project's initial vision and goals. Responsible for the project's overall vision, project goals, and continuity. The project expects the BDFL to serve as a W3C DDS Community Group Chair whenever permitted by mandatory W3C requirements and W3C process. This expectation does not define the BDFL role. If W3C rules or process prevent the BDFL from being a W3C Chair, the BDFL role remains unchanged. The BDFL role is defined by this project's operational agreement, not by the W3C Community Group Process. The BDFL may make final calls on project operational decisions outside the W3C Community Group process when broad consensus cannot be reached, as facilitated by the Chairs. The BDFL may also oppose or reject proposals that would conflict with the project's core objectives.

The BDFL cannot override the W3C Community Group Process, the W3C Code of Conduct, the W3C Community Contributor License Agreement, the W3C Community Final Specification Agreement, applicable W3C report requirements, or this operational agreement. For specification work, Community Group reports, and publication decisions, the BDFL defers to the W3C DDS Community Group process and applicable W3C requirements. BDFL decisions should be documented publicly with their rationale. The BDFL may appoint their own successor. If unable, the Chairs facilitate a public succession process. Chairs and Maintainers select the successor after considering input from active participants and seeking broad consensus.

The BDFL role is a founding governance role of the project.

Currently: **Nicolas Gimenez** ([@nicobao](https://github.com/nicobao))

## Official Project Tools

Official DDS project tools include GitHub, the DDS Matrix room, the DDS W3C Community Group calendar, and any future official coordination or publication tools.

DDS should use neutral W3C tools where they are available and fit the project's needs. When W3C tools are unavailable, outdated, missing important functionality, or would limit reach, usability, or effective participation, DDS may use external tools, including current technologies that help the Community Group work well. External tools must remain neutral project infrastructure. Where possible, they should use project-owned accounts, shared administrative access, public documentation, and exportable or migratable data. The access rules below are the minimum safeguard for that neutrality.

Only the BDFL and Chairs may hold administrative control over official DDS project tools. Others may have non-admin access, repository permissions, organization membership, or tool membership as needed for contribution and operations. The BDFL and every Chair must have administrative access to official DDS project tools to the extent supported by each tool. When someone holds neither the BDFL role nor a Chair role, their administrative access to those tools must be removed. If a tool requires admins to remove their own admin status, the outgoing BDFL or Chair must remove themselves.

## Decision Making

Consensus comes first. We prefer rough agreement reached through open discussion over top-down decisions. Decisions happen in public on GitHub issues and pull requests. Consensus means broad agreement among active participants, not only agreement among Chairs or Maintainers.

Default is lazy consensus: if nobody objects, it passes. Maintainers can merge PRs they judge to be correct for routine repository, documentation, website, proof-of-concept, and editorial work.

For specification work, Community Group reports, and publication decisions, the project follows the W3C DDS Community Group process and applicable W3C requirements. Chairs coordinate and facilitate that process and help determine whether there is sufficient consensus to proceed.

If broad consensus cannot be reached after public discussion facilitated by the Chairs, the BDFL may make the final call. The BDFL may also oppose or reject proposals that would conflict with the project's core objectives. If the decision affects specification content, Community Group reports, or publication, the decision must still comply with the W3C Community Group process and applicable W3C requirements. The BDFL should document the rationale publicly.

## Changing This Document

Submit a pull request. Maintainers review changes for repository impact. Chairs review changes that affect the W3C Community Group process, group participation, specification consensus, Community Group reports, publication, or this operational agreement.

Changes to this document should be adopted by broad consensus, facilitated by the Chairs. If broad consensus cannot be reached, the current text remains in effect unless a change is required to comply with mandatory W3C Community Group requirements.

Ordinary changes to this document cannot remove or redefine the existence of the BDFL role or its distinction from Maintainers and W3C DDS Community Group Chairs.

No change to this document may conflict with mandatory W3C Community Group requirements, including the W3C Community and Business Group Process, the W3C Code of Conduct, the W3C Community Contributor License Agreement, the W3C Community Final Specification Agreement, or applicable W3C report requirements.

Material changes to this operational agreement must be documented publicly. The Chairs are responsible for giving actual notice to Community Group participants when W3C Community Group operational agreements materially change.
