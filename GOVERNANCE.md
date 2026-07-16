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

Anyone who opens an issue, submits a pull request, joins a discussion, attends a call, or otherwise participates. No approval needed. Influence comes from the work, not from titles. Contributors remain external by default until they have earned project access through trust, sustained quality contributions, and willingness to help others.

### Maintainer

A trusted Contributor who has earned responsibility for maintaining part of DDS by demonstrating sustained, quality contributions and a willingness to help others, not just advance their own interests. Maintenance can include code, specifications support, documentation, community operations, events, websites, issue triage, review, infrastructure, or official project tools. A Maintainer has access to at least one DDS repository or official project tool in a non-admin or otherwise scoped role needed for their maintenance responsibilities. Without such project access, a participant remains a Contributor. Joining the W3C DDS Community Group on w3.org does not automatically make someone a Maintainer.

Maintainers help keep the project operating: triaging issues, reviewing and merging pull requests where they have repository access, maintaining CI, keeping documentation usable, stewarding website and proof-of-concept work, supporting meetings, helping with official tools, and assisting with community operations. Maintainer authority does not by itself determine W3C Community Group consensus, Community Group report publication, or W3C process questions.

To appoint a Maintainer with broad project access, DDS GitHub organization membership, publishing access, financial-tool access, or access to official public-facing tools, one Chair or the BDFL must ask all Chairs and the BDFL for approval in a public GitHub issue or on the public mailing list. Chairs and the BDFL have one month to refuse publicly. If nobody refuses within one month, the request is deemed accepted. A reasoned refusal from any Chair or the BDFL blocks the appointment.

For narrowly scoped Maintainer access, such as a specific repository, documentation area, issue triage role, or non-sensitive tool role, approval by one Chair or the BDFL is enough. The appointment must be documented publicly in a GitHub issue or on the public mailing list and may be reviewed and vetoed by the Chairs or the BDFL within one month.

A Maintainer inactive for a year may be removed after being given a chance to return.

### W3C DDS Community Group Chairs

The W3C DDS Community Group chairs coordinate and facilitate the W3C Community Group process, including group participation, specification consensus, report publication, and W3C process alignment. The Chairs are responsible for ensuring the group follows W3C requirements and this public operational agreement. They are the primary contacts for W3C Community Group process matters.

Chairs are co-owners of the DDS GitHub organization associated with the W3C DDS Community Group. Chairs review Maintainer appointments as described above.

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

## Branding, Marketing, Funding, and Conflicts

Use of the W3C name, W3C logos, W3C trademarks, W3C Community Group branding, or any fundraising activity that presents itself as being on behalf of W3C is governed by applicable W3C policies, including the [W3C trademark and service mark license](https://www.w3.org/trademark-license/), [W3C logos and icons policy](https://www.w3.org/policies/logos/), [W3C fundraising policy](https://www.w3.org/policies/fundraising-policy/), [W3C Antitrust and Competition Policy](https://www.w3.org/policies/antitrust-2024/), and [W3C Community and Business Group Process](https://www.w3.org/community/about/process/). DDS participants must not imply W3C endorsement, W3C Recommendation status, official W3C status, or authority to fundraise on behalf of W3C unless W3C has granted that authority.

Factual references to DDS are allowed, including statements that a person or organization contributes to DDS, implements DDS work, or is funded to work on DDS, provided those statements are accurate. Use of the DDS name, branding, logos, marketing language, or other project marks must not misrepresent the user's relationship to DDS, the W3C DDS Community Group, the Chairs, the BDFL, or the status of the work. DDS branding or marketing must not be used to imply endorsement, official project status, control over the project, sponsorship, certification, or standardization status beyond what is actually true.

Funding efforts are plural. Participants and their organizations may independently seek funding for their own DDS-related work, subject to applicable W3C policies and conflict-of-interest expectations. They must not present that fundraising as being on behalf of DDS, the W3C DDS Community Group, W3C, the Chairs, or the BDFL unless authorized through the Community Group's documented process or an official shared funding tool. Any participant or organization that receives a public grant, public donation, crowdfunding contribution, or other public funding for DDS Community Group activities must publicly disclose the source, purpose, amount, and how the funds are distributed or used. For private employment, consulting, sponsorship, or internal organization funding related to DDS work, participants must disclose relevant affiliations, sponsors, and conflicts of interest, but are not expected to publish confidential compensation or contract terms. Funding must not distort technical consensus, Community Group participation, or publication decisions.

Funds raised using the DDS name, DDS branding, or the identity of the W3C DDS Community Group must be used to serve the development, participation, documentation, implementation, or operation of the Community Group. Raising funds in the name of DDS or the W3C DDS Community Group and then failing to use them for that purpose is a serious violation of this operational agreement. DDS may remove DDS-controlled project access, repository access, official tool access, or Maintainer status from associated participants. If an associated participant is a Chair, the violation is grounds to seek removal of their Chair status under applicable W3C process and this operational agreement. Removal from W3C Community Group participation is governed by W3C process; the Chairs may escalate serious violations to W3C for review, including participant sanctions available under applicable W3C process.

The Community Group may create a shared funding tool to support DDS Community Group work. Any such tool is an official DDS project tool and must follow the access rules in [Official Project Tools](#official-project-tools), with the BDFL and Chairs as administrators to the extent supported by the tool.

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
