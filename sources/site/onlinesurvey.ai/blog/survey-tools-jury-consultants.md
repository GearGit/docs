# Source: https://onlinesurvey.ai/blog/survey-tools-jury-consultants

ON THIS PAGE

[What Survey Research Is Used for in Litigation](https://onlinesurvey.ai/blog/survey-tools-jury-consultants#what-survey-research-is-used-for-in-litigation) [Why Standard Consumer Survey Tools Fall Short for Jury Research](https://onlinesurvey.ai/blog/survey-tools-jury-consultants#why-standard-consumer-survey-tools-fall-short-for-jury-resea) [8 Required Features in Litigation Survey Software](https://onlinesurvey.ai/blog/survey-tools-jury-consultants#8-required-features-in-litigation-survey-software) [Questions to Ask a Vendor Before Using Their Platform for Litigation Research](https://onlinesurvey.ai/blog/survey-tools-jury-consultants#questions-to-ask-a-vendor-before-using-their-platform-for-li) [How onlinesurvey.ai Supports Litigation Research](https://onlinesurvey.ai/blog/survey-tools-jury-consultants#how-onlinesurvey-ai-supports-litigation-research) [Frequently Asked Questions](https://onlinesurvey.ai/blog/survey-tools-jury-consultants#frequently-asked-questions)

## What Survey Research Is Used for in Litigation

Trial consultants and litigation support professionals use survey research across several distinct phases of case preparation:

**Change of venue motions.** A community attitude survey documents that pretrial publicity or local bias has so permeated the venue that seating an impartial jury is unlikely. The survey becomes an exhibit, and the methodology must withstand cross-examination.

**Pre-trial bias assessment.** Before jury selection, consultants assess whether the local population holds prior attitudes, toward the parties, the alleged conduct, or the type of case, that would be difficult to rehabilitate through voir dire alone.

**Community attitude surveys.** Broader attitudinal surveys capture how a defined geographic community perceives an industry, a company, or a type of plaintiff or defendant. These inform voir dire strategy even when a formal venue motion is not sought.

**Mock jury and focus group research.** While typically smaller in scale, mock jury studies require the same rigor in screener design, quota controls, and data documentation as large-scale community surveys.

**Juror profiling and demographic analysis.** Survey instruments that gather eligible juror profiles (values, media consumption, occupation, prior experience with legal proceedings) feed directly into jury selection strategy.

In every one of these applications, the research may ultimately be presented to a court. That context sets a different standard than a product feedback survey or employee engagement poll.

## Why Standard Consumer Survey Tools Fall Short for Jury Research

General-purpose survey platforms are engineered for volume, ease of use, and marketing workflows. They are not designed for the precision requirements of litigation support research. The gaps are significant:

**Methodological defensibility.** Courts and opposing counsel evaluate the research instrument itself. A platform that does not support randomization controls, quota management, or proper screener sequencing makes it harder to demonstrate that the methodology was sound, independent of the consultant's expertise.

**Chain of custody and data integrity.** In legal proceedings, data provenance matters. Who collected the data? When? Were responses altered? Platforms that do not maintain timestamped response-level logs, access audit trails, or immutable exports create evidentiary vulnerabilities.

**Security and confidentiality.** Litigation data can include sensitive information about case strategy, community bias, and potential jurors. Platforms that use survey response data for product improvement or model training introduce confidentiality and work-product concerns.

**Complex logic requirements.** A well-designed jury eligibility screener involves multi-stage branching: initial demographic filters, then jurisdictional eligibility questions, then case-specific awareness probes, then attitudinal batteries, with routing logic that differs depending on prior answers. Platforms with limited branching quickly hit their ceiling.

**Response capacity.** Community attitude surveys for large metropolitan venues may require 600 to 1,000 or more completed responses to achieve statistically defensible margins of error by key demographic subgroups. Platforms with response caps or throttling make this impractical.

**Neutral presentation.** Any visual branding that associates the survey with a law firm, corporation, or identifiable party undermines the claimed neutrality of the instrument. Litigation surveys require fully custom or unbranded presentation.

:::cta heading: Litigation-grade survey research, _defensible_ by design. primary: Start free :::

## 8 Required Features in Litigation Survey Software

### 1\. Advanced Branching and Skip Logic for Complex Screeners

Jury research instruments are rarely linear. A qualified respondent who reports prior knowledge of a case, a relationship with counsel, or a prior jury service record must be routed differently than one without those characteristics. The platform must support:

- Multi-level conditional branching (branch on one or more prior answers)
- Nested logic (conditions within conditions)
- Early termination with screener-out routing
- Ability to preview and test logic paths before deployment

Platforms that cap branching depth or require workarounds for nested conditions create risk: screener failures allow unqualified respondents into the dataset, which damages the sample's integrity.

### 2\. Quota Management for Demographic Representativeness

Courts are more receptive to survey evidence when the sample mirrors the eligible juror population of the venue. That means controlling representation by age, gender, race/ethnicity, education, and sometimes political affiliation or occupational category, simultaneously.

The platform should support:

- Multiple concurrent quotas (not just one at a time)
- Soft and hard quota caps
- Real-time quota tracking during data collection
- Automatic disqualification of respondents once a cell is filled

Without quota controls, the consultant is left managing representativeness manually, which is error-prone and difficult to document.

### 3\. Screening Question Support

Jury eligibility criteria (citizenship, age, county of residence, absence of felony conviction, English-language comprehension) must be established before the substantive survey begins. The platform must allow:

- Placement of screener questions at the start of the instrument
- Immediate routing out of ineligible respondents without exposing them to substantive questions
- Documentation of screener criteria in the exported dataset

Some platforms randomize question order by default or delay screener routing. Both are problematic in litigation survey design.

### 4\. Secure Data Storage with Access Controls

Data security requirements for litigation research are more demanding than for typical market research:

- **Encryption in transit and at rest**: a baseline requirement, not a differentiator
- **Access controls**: the ability to restrict who within your organization can view or export response data
- **Data residency**: clarity on where response data is stored and under what legal jurisdiction
- **No use of response data for AI training or product improvement**: this is a work-product and confidentiality issue; confirm it explicitly with the vendor

On enterprise-tier platforms, role-based access control (RBAC) allows the account administrator to define precisely who can view raw responses versus summary reports.

### 5\. Response-Level Data Export for Expert Report Preparation

An expert witness preparing a declaration or report in support of a venue motion needs access to response-level data, not just aggregate charts. The platform must export:

- Individual response records with timestamps
- Respondent ID, geographic identifier, and demographic battery responses
- All branching paths taken (i.e., which questions were shown to which respondent)
- Exportable in formats usable in statistical analysis software (CSV, SPSS-compatible formats)

Aggregate-only exports are insufficient for independent statistical analysis and cross-tabulation.

### 6\. High Response Capacity

The sample size required for statistical defensibility in community attitude surveys depends on the venue population and the precision required by subgroup. In large metros, achieving defensible margins of error for multiple demographic cross-tabs can require 600 to 1,200 completed responses.

Before selecting a platform:

- Confirm the per-survey response cap on your plan tier
- Confirm whether response collection can be throttled by time period (to avoid clustering effects)
- Confirm there is no artificial throttling that would prevent rapid data collection for time-sensitive filings

### 7\. Custom Branding for Neutral Presentation

Survey respondents should not be able to identify the sponsoring party from the survey's visual design. This is both a methodological requirement (to minimize demand characteristics) and, in some courts, a legal one.

The platform must allow:

- Removal of all platform-level branding (logo, taglines, footer links)
- Custom survey URL or neutral subdomain
- Neutral header and color scheme that cannot be associated with any party
- No survey completion pages that reveal the platform identity

Consumer platforms frequently inject their own branding into survey footer elements or completion pages. Confirm this can be fully suppressed.

### 8\. Audit Trail and Data Integrity

For research that will be submitted to a court, you need to be able to demonstrate that the data was collected cleanly and has not been altered:

- **Timestamped response records**: each completion logged with collection time
- **IP address logging** (where legally permissible), to document geographic distribution and identify duplicate submissions
- **Duplicate detection and removal**: automatic flagging of multiple responses from the same device or IP
- **Immutable data export**: the ability to produce a data file and attest that it has not been modified since collection

Some platforms overwrite or aggregate response records on a rolling basis. Confirm that the platform maintains full response-level records for a period sufficient to cover potential litigation timelines.

## Questions to Ask a Vendor Before Using Their Platform for Litigation Research

Before committing a platform to a jury research project, work through these questions with the vendor, in writing:

1. **Does your platform use survey response data for any purpose other than delivering it to the account holder?** (Specifically: AI model training, product analytics, or third-party sharing.)
2. **What data residency options are available, and under what law is the data governed?**
3. **What access control options exist at the account and survey level?** Can I restrict which team members can view raw response data?
4. **What is the maximum number of responses per survey on my plan tier, and is throttling possible?**
5. **Can all platform branding be removed from the survey interface and completion pages?**
6. **What audit trail documentation can you produce for a specific survey?** (Timestamps, IP records, access logs.)
7. **What is your data retention policy?** How long are response-level records maintained?
8. **Have you supported litigation research before, and can you describe your data security certification stack?** (SOC 2, ISO 27001, etc.)

A vendor that cannot answer these questions in writing is not positioned to support litigation-grade research, regardless of their platform's technical capabilities.

## How onlinesurvey.ai Supports Litigation Research

onlinesurvey.ai is an AI-native survey platform designed for researchers who need to move from a research objective to clean, analyzable data, not just from a form to a response count.

For trial consultants and litigation support professionals, the platform supports:

**Advanced branching and quota management.** The platform handles multi-level conditional logic and multiple concurrent demographic quotas, allowing complex jury eligibility screeners and representative sampling controls to be implemented without workarounds.

**Secure data handling.** All response data is encrypted in transit and at rest. onlinesurvey.ai does not use survey response data for AI model training, a critical assurance for work-product-sensitive litigation research.

**Advanced access controls.** The Custom plan includes advanced role-based access control (RBAC) and SSO, allowing account administrators to define exactly which team members can access raw response data and which can only view summary outputs. Custom plans also cover multi-region data hosting, HIPAA, a GDPR DPA, SOC 2, and dedicated support with an SLA.

**Response-level data export.** Respondent-level data is exportable in formats suitable for expert report preparation and independent statistical analysis.

**AI-powered pattern analysis.** The platform's AI analysis layer can identify patterns in community attitude data (recurring themes, correlated opinions, demographic clusters) that surface during open-ended response review. This does not replace the consultant's expert analysis; it accelerates the first-pass identification of bias themes worth pursuing in cross-tabs.

**Neutral branding.** Custom survey presentation and neutral branding are available, ensuring the survey instrument cannot be visually associated with any party.

**Predictable response capacity.** The free plan includes 250 responses a month, and paid plans scale from there on flat, predictable pricing rather than per-completion billing, so sizing a community attitude survey is a plan decision made up front, not a per-response invoice discovered afterwards.

## Frequently Asked Questions

### What is jury research survey software?

Jury research survey software is a survey platform used by trial consultants and litigation support professionals to conduct community attitude surveys, pre-trial bias assessments, change of venue studies, and mock jury research. Unlike general survey tools, litigation-grade platforms must support complex screener logic, quota controls for demographic representativeness, secure data handling with access controls, and response-level exports for expert report preparation.

### What sample size is needed for a community attitude survey?

Sample size depends on the venue population, the margin of error required, and the level of cross-tabulation the analysis will involve. For a straightforward community attitude survey, a minimum of 300 to 400 completed responses is often cited as a baseline threshold. When the analysis requires cross-tabs by multiple demographic subgroups, which courts increasingly expect, 600 to 1,200 completed responses may be necessary to achieve statistically defensible precision at the subgroup level. A statistician should be involved in the sample size determination before data collection begins.

### Why can't I use a standard survey tool for jury research?

Standard survey tools are designed for marketing and HR use cases. They typically lack the multi-level branching required for jury eligibility screeners, the concurrent quota management needed for representative sampling, the audit trails required to document data integrity, and the security controls needed to protect work-product-sensitive data. Many also use response data for internal product purposes, which creates a confidentiality concern. Platforms used for litigation research should be evaluated explicitly against each of these criteria.

### Does the survey platform need to remove its branding for litigation surveys?

Yes. Any visual element that identifies the sponsoring party, or could be associated with one, can introduce demand characteristics that undermine the claimed neutrality of the instrument. A respondent who identifies the survey as being conducted on behalf of a law firm or corporation may answer differently than one who cannot. Most consumer platforms inject their branding into survey interfaces and completion pages. Before using any platform for litigation research, confirm in writing that all platform-level branding can be fully suppressed.

### What data security features should litigation survey software have?

At minimum: encryption in transit and at rest, explicit confirmation that response data is not used for AI training or third-party purposes, response-level audit logs with timestamps, and the ability to restrict data access by user role. For matters involving sensitive case strategy, top-tier plans with RBAC and SSO provide the additional access controls and documentation needed to demonstrate data governance. Confirm data residency and retention policy before beginning data collection.

### Can AI analysis be used in litigation survey research?

AI analysis tools can be used to accelerate first-pass identification of patterns in community attitude data, particularly in open-ended responses, where manual review of hundreds of verbatim answers is time-intensive. AI-surfaced themes and clusters can inform the consultant's own analysis and help identify which cross-tabulations are most worth pursuing. However, AI analysis does not replace the expert's independent analysis, statistical methodology, or declaration. The expert report must be grounded in the consultant's own methodology, with AI serving as a research efficiency tool, not the analytical engine of record.

## Put your research into practice, _fast._

Free to start. No credit card. Every plan has the intelligence built in.

[Create a survey](https://app.onlinesurvey.ai/signup) [Book a demo](https://cal.com/sales-team-y7ofqn/30min)

RELATED ARTICLES

[![Research Methods: A Complete Guide for 2026](https://ik.imagekit.io/somanshu/onlinesurvey.ai/blog/research-methods-complete-guide.svg?updatedAt=1780351659543)\\ \\ GUIDES\\ \\ Research Methods: A Complete Guide for 2026\\ \\ Learn the main types of research methods (experimental, observational, qualitative, quantitative, and more) with plain-English explanations and examples.\\ \\ JUN 2 2026 · 13 MIN READ→](https://onlinesurvey.ai/blog/research-methods-complete-guide) [![Marketing Research: The Definitive Framework](https://ik.imagekit.io/somanshu/onlinesurvey.ai/blog/marketing-research-definitive-framework.svg?updatedAt=1780351659475)\\ \\ GUIDES\\ \\ Marketing Research: The Definitive Framework\\ \\ A practical framework for marketing research, from defining your question to collecting data, analysing findings, and acting on results.\\ \\ MAY 19 2026 · 15 MIN READ→](https://onlinesurvey.ai/blog/marketing-research-definitive-framework) [![Data Collection Methods: How to Choose the Right One](https://ik.imagekit.io/somanshu/onlinesurvey.ai/blog/data-collection-methods.svg?updatedAt=1780351659111)\\ \\ GUIDES\\ \\ Data Collection Methods: How to Choose the Right One\\ \\ From surveys and interviews to observation and experiments, a plain-English guide to data collection methods and how to pick the right one for your study.\\ \\ MAY 17 2026 · 12 MIN READ→](https://onlinesurvey.ai/blog/data-collection-methods)