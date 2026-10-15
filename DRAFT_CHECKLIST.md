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
- [ ] Confirm applicable legal information requirements, including international offering and hosting/support data processing.
- [ ] Reconcile final release-build identity with audited source before approval.
