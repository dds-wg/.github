# Governance

## The Project

DDS, the Decentralized Deliberation Stack, is an open project and W3C Community Group for sovereign, verifiable, interoperable, and resilient deliberation. Work happens in public in the [DDS GitHub organization](https://github.com/dds-wg) and through the [W3C DDS Community Group](https://www.w3.org/community/dds/).

DDS is not covered by a single licence. Specification work follows the W3C Community Group contribution process. The website and proof-of-concept software are licensed under MPL-2.0 unless another licence is explicitly stated. See the [`dds` licence map](https://github.com/dds-wg/dds/blob/main/COPYING-README.md).

The project is designed to be interoperable and modular. We actively try to accommodate the diverse use-cases of individuals and teams, and that flexibility is what makes it flourish. When conflicts arise between competing needs, however, decisions must be made that preserve consistency and the project's core objectives.

This document is the project's public operational agreement for governance, GitHub access, and official project tool administration. It does not replace the [W3C Community and Business Group Process](https://www.w3.org/community/about/process/), the [W3C Code of Conduct](https://www.w3.org/policies/code-of-conduct/), the [W3C Community Contributor License Agreement](https://www.w3.org/community/about/process/cla/), the [W3C Community Final Specification Agreement](https://www.w3.org/community/about/process/final/), or applicable [W3C report requirements](https://www.w3.org/community/reports/reqs/).

## Governance Philosophy

DDS stands for Decentralized Deliberation Stack. The W3C DDS Community Group stewards DDS, whose scope is intentionally broad and meta: it tries to connect protocols, products, and communities across different deliberation use-cases. That openness is important, but it also means the work needs a clear and coherent vision to hold the pieces together.

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

For narrowly scoped Maintainer access, such as a specific repository, documentation area, issue triage role, or non-sensitive tool role, one Chair or the BDFL may appoint a Maintainer or remove that access. Either decision may be reviewed and vetoed by the Chairs or the BDFL within one month. An appointment must be documented publicly in a GitHub issue or on the public mailing list.

A Maintainer may be removed for inactivity, loss of trust, misuse of project access, repeated failure to perform their maintenance responsibilities, violation of this operational agreement, or conduct that harms the project or Community Group. Removal should be documented publicly in a GitHub issue or on the public mailing list unless privacy, safety, or security concerns require a more limited process.

For broad project access, DDS GitHub organization membership, publishing access, financial-tool access, or access to official public-facing tools, all Chairs and the BDFL should be notified, and removal proceeds unless a Chair or the BDFL raises a reasoned objection within one month. Urgent access removal may happen immediately when needed to protect the project, participants, funds, credentials, or infrastructure, but must be reviewed afterward.

### W3C DDS Community Group Chairs

The W3C DDS Community Group chairs coordinate and facilitate the W3C Community Group process, including group participation, specification consensus, report publication, and W3C process alignment. The Chairs are responsible for ensuring the group follows W3C requirements and this public operational agreement. They are the primary contacts for W3C Community Group process matters.

Chairs may contribute substantive views, but when acting as Chairs they are expected to facilitate the Community Group process rather than own consensus. They should help participants understand the process, surface disagreement, keep discussions focused, encourage broad participation, document decisions, and ensure that meetings, agendas, minutes, and material process changes are handled publicly as required by W3C process.

A Chair who repeatedly fails to facilitate fairly, blocks participation without process, misrepresents group consensus, fails to document material decisions, or uses Chair status to advance personal, organizational, financial, or factional interests may be challenged by participants. Concerns should first be raised publicly with the Chairs and BDFL where appropriate. If unresolved, or if direct public discussion would be unsafe or inappropriate, Chairs or participants may escalate the issue through the applicable W3C Community Group process, including the Community Development Lead or [W3C Code of Conduct](https://www.w3.org/policies/code-of-conduct/) process where relevant. Persistent failure to meet these expectations is grounds to seek removal of Chair status under applicable W3C process and this operational agreement.

Chairs share responsibility with the BDFL for Maintainer appointment and removal processes, as described above, and for official project tool administration, as described in [Official Project Tools](#official-project-tools).

Current chairs:

- **Simone Vagnoni** ([@Stocastico96](https://github.com/Stocastico96))
- **Nicolas Gimenez** ([@nicobao](https://github.com/nicobao)), current BDFL
- **Lee DeSota** ([@salteelee](https://github.com/salteelee))
- **Puja Ohlhaver** ([personal website](https://www.pujaohlhaver.com/))

### BDFL

The BDFL initiated the W3C DDS Community Group, set the project's initial vision and goals, and is responsible for the project's overall vision, continuity, and coherence. The project expects the BDFL to serve as a W3C DDS Community Group Chair whenever W3C requirements and process allow it. That expectation supports continuity between project governance and Community Group facilitation, but it does not define the BDFL role. If W3C rules or process prevent the BDFL from serving as a Community Group Chair, the BDFL role remains unchanged.

The BDFL role is defined by this project's operational agreement, not by the W3C Community Group Process. The BDFL cannot override the W3C Community Group Process, the W3C Code of Conduct, the W3C Community Contributor License Agreement, the W3C Community Final Specification Agreement, applicable W3C report requirements, or this operational agreement. For specification work, Community Group reports, and publication decisions, the BDFL defers to the W3C DDS Community Group process and applicable W3C requirements.

The BDFL may make final calls on project operational decisions outside the W3C Community Group process when broad consensus cannot be reached, as facilitated by the Chairs. The BDFL may also oppose or reject proposals that would conflict with the project's core objectives. BDFL decisions should be documented publicly with their rationale.

The BDFL role is a founding governance role of the project and has no default expiry.

Currently: **Nicolas Gimenez** ([@nicobao](https://github.com/nicobao))

#### BDFL Succession

The BDFL may appoint their own successor. If the BDFL has not appointed a successor and cannot be reached for one year despite reasonable public and private attempts, the Chairs facilitate a public succession process. In that case, Chairs and Maintainers select the successor after considering input from active participants and seeking broad consensus.

## Official Project Tools

Official DDS project tools include, at minimum, the [DDS GitHub organization](https://github.com/dds-wg), the [DDS Matrix room](SUPPORT.md#group-chat), the [DDS W3C Community Group calendar](SUPPORT.md#open-calls), the [W3C-hosted public mailing list](SUPPORT.md#mailing-list), any shared funding tool, and any future official coordination, moderation, funding, or publication tools.

The official DDS website, blog, and specification publication pipeline at [https://www.dds.xyz](https://www.dds.xyz) are official publication surfaces. While their domain, hosting, billing, or accounts are paid for or owned by the BDFL, the BDFL may remain their sole owner and administrator. If those assets move to shared project control, that must include shared responsibility for operations and appropriate participation in costs. They then become official DDS project tools subject to the access rules below.

DDS should use neutral W3C tools where they are available and fit the project's needs. When W3C tools are unavailable, outdated, missing important functionality, or would limit reach, usability, or effective participation, DDS may use external tools, including current technologies that help the Community Group work well. External tools must remain neutral project infrastructure. Where possible, they should use project-owned accounts, shared administrative access, public documentation, and exportable or migratable data. The access rules below are the minimum safeguard for that neutrality.

Only the BDFL and Chairs may hold administrative control over official DDS project tools. Others may have non-admin access, repository permissions, organization membership, or tool membership as needed for contribution and operations. The BDFL and every Chair must have administrative access to official DDS project tools to the extent supported by each tool. When someone holds neither the BDFL role nor a Chair role, their administrative access to those tools must be removed. If a tool requires admins to remove their own admin status, the outgoing BDFL or Chair must remove themselves.

## Branding, Marketing, Funding, and Conflicts

Use of the W3C name, W3C logos, W3C trademarks, W3C Community Group branding, or any fundraising activity that presents itself as being on behalf of W3C is governed by applicable W3C policies, including the [W3C trademark and service mark license](https://www.w3.org/trademark-license/), [W3C logos and icons policy](https://www.w3.org/policies/logos/), [W3C fundraising policy](https://www.w3.org/policies/fundraising-policy/), [W3C Antitrust and Competition Policy](https://www.w3.org/policies/antitrust-2024/), and [W3C Community and Business Group Process](https://www.w3.org/community/about/process/). DDS participants must not imply W3C endorsement, W3C Recommendation status, official W3C status, or authority to fundraise on behalf of W3C unless W3C has granted that authority.

Factual references to DDS are allowed, including statements that a person or organization contributes to DDS, implements DDS work, or is funded to work on DDS, provided those statements are accurate. Use of the DDS name, branding, logos, marketing language, or other project marks must not misrepresent the user's relationship to DDS, the W3C DDS Community Group, the Chairs, the BDFL, or the status of the work. DDS branding or marketing must not be used to imply endorsement, official project status, control over the project, sponsorship, certification, or standardization status beyond what is actually true.

Funding efforts are plural. Participants and their organizations may independently seek funding for their own DDS-related work, subject to applicable W3C policies and conflict-of-interest expectations. They must not present that fundraising as being on behalf of DDS, the W3C DDS Community Group, W3C, the Chairs, or the BDFL unless authorized through the Community Group's documented process or an official shared funding tool. Any participant or organization that receives a public grant, public donation, crowdfunding contribution, or other public funding for DDS Community Group activities must publicly disclose the source, purpose, amount, and how the funds are distributed or used. For private employment, consulting, sponsorship, or internal organization funding related to DDS work, participants must disclose relevant affiliations, sponsors, and conflicts of interest, but are not expected to publish confidential compensation or contract terms. Funding must not distort technical consensus, Community Group participation, or publication decisions.

Funds raised using the DDS name, DDS branding, or the identity of the W3C DDS Community Group must be used to serve the development, participation, documentation, implementation, or operation of the Community Group. Raising funds in the name of DDS or the W3C DDS Community Group and then failing to use them for that purpose is a serious violation of this operational agreement. DDS may remove DDS-controlled project access, repository access, official tool access, or Maintainer status from associated participants. If an associated participant is a Chair, the violation is grounds to seek removal of their Chair status under applicable W3C process and this operational agreement. Removal from W3C Community Group participation is governed by W3C process; the Chairs may escalate serious violations to W3C for review, including participant sanctions available under applicable W3C process.

The Community Group may create a shared funding tool to support DDS Community Group work. Any such tool is an official DDS project tool and must follow the access rules in [Official Project Tools](#official-project-tools), with the BDFL and Chairs as administrators to the extent supported by the tool.

## Decision Making

Consensus comes first. We prefer rough agreement reached through open discussion over top-down decisions. Decisions should be discussed and documented in public GitHub issues, pull requests, the public mailing list, or other official public project tools as appropriate. Consensus means broad agreement among active participants, not only agreement among the BDFL, Chairs, or Maintainers.

As described in [Governance Philosophy](#governance-philosophy), DDS should remain open to a plurality of contributors, communities, and use-cases. Decision-making should be welcoming and benevolent toward new participants, should respond quickly to new contributors so the community can grow, and should try to accommodate specific use-cases where doing so does not make the project incoherent or undermine its core objectives.

Default is lazy consensus for routine operational and editorial work: if nobody objects, it passes. Maintainers may act within their scoped responsibilities and access, including triage, review, pull-request merges, documentation, CI, website or proof-of-concept work, and official tool operations, when the change is routine and does not affect governance, funding, branding, official tool administration, participant rights, W3C process, Community Group reports, or publication decisions.

For specification work, Community Group reports, and publication decisions, the project follows the W3C DDS Community Group process and applicable W3C requirements. Chairs coordinate and facilitate that process, help surface disagreement, document decisions, and help determine whether there is sufficient consensus to proceed.

If broad consensus cannot be reached on a project operational decision outside the W3C Community Group process after public discussion facilitated by the Chairs, the BDFL may make the final call. The BDFL may also oppose or reject proposals that would conflict with the project's core objectives. If the decision affects specification content, Community Group reports, publication, or mandatory W3C requirements, the decision must still comply with the W3C Community Group process and applicable W3C requirements. The BDFL should document the rationale publicly.

## Changing This Document

Submit a pull request. Maintainers review changes for repository impact. The BDFL and Chairs review changes that affect governance, official project tools, funding, branding, the W3C Community Group process, group participation, specification consensus, Community Group reports, publication, or this operational agreement.

Changes to this document should be adopted by broad consensus, facilitated by the Chairs. If broad consensus cannot be reached, the current text remains in effect unless a change is required to comply with mandatory W3C Community Group requirements.

The BDFL role is a founding governance role of the project. It cannot be removed, replaced, or materially redefined without the consent of the current BDFL. Any such change must be proposed explicitly, discussed publicly, supported by broad consensus among active participants, approved by the Chairs, and ultimately approved by the current BDFL. This does not prevent BDFL succession under [BDFL Succession](#bdfl-succession).

No change to this document may conflict with mandatory W3C Community Group requirements, including the W3C Community and Business Group Process, the W3C Code of Conduct, the W3C Community Contributor License Agreement, the W3C Community Final Specification Agreement, or applicable W3C report requirements.

Material changes to this operational agreement must be documented publicly. The Chairs are responsible for giving actual notice to Community Group participants when W3C Community Group operational agreements materially change.
