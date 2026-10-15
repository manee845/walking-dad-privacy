# The Walking Dad – Privacy Page (draft)

This repository is reserved for the eventual public privacy notice for the Garmin Connect IQ app **The Walking Dad**.

## Status

- Draft German page: `index.html`; draft English page: `en/index.html`, both on `draft/privacy-page`.
- The default branch `main` remains unchanged.
- Do **not** enable GitHub Pages or merge this draft until the privacy checks are complete.
- The repository is public. Branch content can still be viewed via GitHub even before Pages is enabled.

## Release checklist

- [x] Perform a read-only code audit of the actual Garmin Connect IQ project and `manifest.xml` (15 Oct 2026; final release-build mapping outstanding).
- [ ] Verify the initial GPS-access flow and user information/consent, including GPS fix before recording begins.
- [ ] Inventory sensor, activity recording, storage and communication API access, along with any dependencies.
- [ ] Verify local checkpoint and preference storage, cleanup after save/discard, and limitations on uninstall.
- [ ] Verify if any data is sent directly to third parties and differentiate app transmission from Garmin's native synchronization.
- [ ] Verify Garmin FIT fields, data exported to Garmin Connect, and limitations of recovered partial activities.
- [ ] Confirm current Garmin Connect IQ publishing/privacy requirements and applicable Swiss data-protection requirements.
- [x] Add the responsible individual's legal name and the dedicated support email address.
- [ ] Revise the privacy page to reflect only verified production behavior; remove draft banners and unresolved placeholders.
- [ ] Review and approve the final public wording before merging and enabling GitHub Pages.
- [ ] Configure GitHub Pages from the main branch and validate the resulting HTTPS URL on mobile.
- [ ] Place that stable URL in the Connect IQ Store submission.

No app code, FIT files, API tokens, signing keys or other private material belong in this repository.

## Internal project decisions

- Publisher: individual developer; no studio or company required for the MVP.
- Responsible developer: Manuel von Allmen (Switzerland).
- Support contact: support.thewalkingdad@gmail.com (free Gmail account; setup confirmed, send/receive test not yet evidenced).
- Hosting: GitHub Pages at this public repository.
- Current source basis: MVP specification v1.2, hardware Test 05 (15 October 2026), C02 technical privacy audit and C02 privacy corrections (15 October 2026). Privacy changes: verified-save checkpoint cleanup and data-minimized diagnostic output (159 simulator PASS, hardware/release validation pending). Consent, legal review and release-build mapping remain open.

## C02 follow-up (15 October 2026)

- [x] Record the approved support-email retention policy in German and English drafts.
- [x] Prepare an English draft in the existing repository; no separate site, merge, or Pages activation.

- [x] Update the existing draft privacy text to reflect the reported C02 code corrections; retain draft notice and publication block.
- [ ] Verify the final Garmin Store installation and consent flow (including denial/cancellation as applicable).
- [ ] Validate revised checkpoint cleanup and release logs on the Fenix 6 Pro; confirm FIT/Connect export after the revised build.
- [x] Decide support-email retention: keep as needed to handle requests; review inbox at least every six months and delete unneeded messages unless justified retention applies.
- [ ] Complete legal review for Swiss FADP, possible GDPR applicability, international support/hosting data transfers, and Garmin consent requirements (preliminary review completed 15 Oct 2026).
- [ ] Reconcile final release-build identity with audited source before approval.

## Legal draft amendments (15 October 2026)

- [x] Add privacy-rights and GitHub Pages hosting sections to both language versions.
- [x] Name Google for Gmail support and flag potential processing outside Switzerland; link to Google's privacy notice.
- [ ] Determine EU/EEA targeting and GDPR territorial scope before launch; no automatic GDPR non-applicability claim.
- [ ] Confirm cross-border transfer countries/safeguards and any additional required controller contact details with qualified legal review before public approval.

## Cross-border processing and GDPR review – 15 October 2026

- [x] Review EDÖB information and foreign-disclosure guidance, Google consumer terms and transfer frameworks, GitHub privacy statement and Pages logging, and the EDPB's final Article 3 territorial-scope guidelines.
- [x] Name the verified core jurisdictions (Google Ireland; GitHub Netherlands / US) and possible US/other-country processing in both language drafts; do not assert complete transfer mapping or guaranteed safeguards.
- [ ] Confirm whether the actual support Gmail account falls under the expected Swiss consumer terms and verify relevant onward-transfer countries and safeguards for the data actually handled.
- [ ] Verify GitHub Pages hosting recipient countries and applicable transfer mechanism for the actual setup; do not imply a complete country list from provider documentation alone.
- [ ] Assess planned EU-directed marketing and whether this app's wearable location/activity functionality constitutes behavioural monitoring under GDPR Art. 3(2)(b). International availability alone does not settle either question; ask qualified legal counsel if uncertainty remains material.
- [ ] If GDPR applies, confirm appropriate lawful bases and Art. 13 disclosures, Art. 27 representative/exemption, and any additional rights and contact information before approval.
- [ ] Before launch, verify the final Store install/consent sequence against Garmin Exhibit A and the production build, separately from this written notice.

No change to central roadmap v1.5 priorities. Public release remains blocked.

## Source verification supplement – 15 October 2026

- [x] Confirm Swiss FADP information duties: controller identity/contact, purposes, recipients and, for cross-border disclosure, recipient states and applicable safeguards (EDÖB: https://www.edoeb.admin.ch/de/informationspflicht and https://www.edoeb.admin.ch/de/bekanntgabe-von-personendaten-ins-ausland).
- [x] Confirm Google generally identifies Google Ireland Limited for Switzerland-based consumer accounts (https://policies.google.com/faq); Google LLC publicly states Swiss–US DPF participation and an active Swiss–US certification is listed by the US Department of Commerce (https://policies.google.com/privacy/frameworks). These facts do NOT establish that a particular consumer Gmail processing chain or transfer is covered end to end.
- [x] Confirm GitHub Pages logs visitor IP addresses for security (https://docs.github.com/en/pages/getting-started-with-github-pages/what-is-github-pages) and GitHub's privacy statement describes worldwide locations, SCCs, and Swiss–US DPF certification (https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement). Service-specific role and guarantees remain to be verified.
- [x] Review EDPB final territorial-scope Guidelines 3/2018 and GDPR Arts. 3, 9, 13 and 27: mere EU accessibility alone is insufficient to establish EU targeting, but processing of activity/location/possible health data requires a contextual assessment. No EU representative has been appointed or deemed necessary solely from the present evidence.
- [ ] Record intended Store audience/territorial marketing and confirm whether EU data subjects are specifically targeted or behaviour is monitored in the EU; seek legal review before launching into the EU if uncertainty is material.
- [ ] Verify whether Garmin developer clauses plus installation consent are sufficient for position, activity data and local retention on actual Store installation; no premature waiver.
- [ ] Verify correspondence address / contact sufficiency and whether the free Gmail service model meets the controller's intended support-data handling obligations; avoid soliciting FIT files with sensitive details as routine support.

These are research/checklist findings, not a declaration of legal conformity or permission to publish.
