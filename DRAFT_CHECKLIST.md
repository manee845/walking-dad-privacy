# The Walking Dad – Privacy Page (draft)

This repository is reserved for the eventual public privacy notice for the Garmin Connect IQ app **The Walking Dad**.

## Status

- The draft page is stored in `index.html` on the branch `draft/privacy-page`.
- The default branch `main` remains unchanged.
- Do **not** enable GitHub Pages or merge this draft until the privacy checks are complete.
- The repository is public. Branch content can still be viewed via GitHub even before Pages is enabled.

## Release checklist

- [ ] Perform a read-only code audit of the actual Garmin Connect IQ project and `manifest.xml`.
- [ ] Verify the initial GPS-access flow and user information/consent, including GPS fix before recording begins.
- [ ] Inventory sensor, activity recording, storage and communication API access, along with any dependencies.
- [ ] Verify local checkpoint and preference storage, cleanup after save/discard, and limitations on uninstall.
- [ ] Verify if any data is sent directly to third parties and differentiate app transmission from Garmin's native synchronization.
- [ ] Verify Garmin FIT fields, data exported to Garmin Connect, and limitations of recovered partial activities.
- [ ] Confirm current Garmin Connect IQ publishing/privacy requirements and applicable Swiss data-protection requirements.
- [ ] Add the responsible individual's legal name and the dedicated support email address.
- [ ] Revise the privacy page to reflect only verified production behavior; remove draft banners and unresolved placeholders.
- [ ] Review and approve the final public wording before merging and enabling GitHub Pages.
- [ ] Configure GitHub Pages from the main branch and validate the resulting HTTPS URL on mobile.
- [ ] Place that stable URL in the Connect IQ Store submission.

No app code, FIT files, API tokens, signing keys or other private material belong in this repository.

## Internal project decisions

- Publisher: individual developer; no studio or company required for the MVP.
- Support contact: a separate free email address (provider/address pending).
- Hosting: GitHub Pages at this public repository.
- Current source basis: documented Garmin MVP simulator tests through Test 04 (11 October 2026); not a complete source-code audit or hardware/Connect verification.
