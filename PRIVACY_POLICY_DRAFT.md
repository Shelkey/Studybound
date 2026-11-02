# Studybound Beta privacy policy

Draft for publisher review. Prepared 2 November 2026 for version 0.10.15. Before publication, replace the publisher, contact and effective-date placeholders, confirm the support and hosting practices below, and review the remaining publisher gates in POLICY_REVIEW.md. No public URL has been created.

Publisher: [PUBLISHER LEGAL OR PUBLIC NAME]

Effective date: [DATE OF PUBLICATION]

Privacy contact: [PUBLISHER PRIVACY CONTACT]

## What Studybound does

Studybound adds a local role-playing game to Japanese study reviews on WaniKani and Bunpro. After you select Enable Studybound in the in-product disclosure, the extension processes review-page information to detect graded answers, update game progress and show optional study-page overlays. It is independently developed and is not affiliated with or endorsed by WaniKani or Bunpro.

## Information processed on your device

Studybound observes review correctness, question or subject identifiers, question modes and available study metadata, such as item level and spaced-repetition stage. It also checks the supported page's path and attachment status. It generates local event and session identifiers to avoid counting the same grade twice and to manage game timing. These are not an account login.

If you enable Study Text Display, Studybound temporarily reads visible Japanese study text on WaniKani and the Japanese answer text you submit in Bunpro's review input. It filters and truncates that text for cosmetic display. These optional text snippets are held in memory with an eight-second expiry window, not saved in the persistent game save. Turning the option off clears the display data. Browser suspension may delay physical cleanup of memory; expired text is filtered before presentation.

The extension stores RPG progress, review-result statistics, recent run summaries, class and skill unlocks, Camp purchases, inventory, achievements, settings and window/overlay positions in browser-local extension storage. It retains a bounded cache of processed event IDs and supported-page status records. Optional grading diagnostics retain recent result metadata, not the typed answer text. Your selected lobby class is also remembered in extension-origin local storage.

Studybound's implementation does not read login passwords, authentication cookies or API keys. It does not require a Studybound account. It does not implement analytics, advertising, telemetry or automatic crash reporting.

## Transmission and sharing

This version contains no extension-operated remote data service and does not automatically send study information, game saves or diagnostics to the publisher or another recipient. Game code and artwork are bundled locally. Information passes between the content script, extension worker and extension views through local browser messaging. Layout messages also pass between the study page and the embedded extension HUD; those messages carry layout and visibility information.

WaniKani and Bunpro remain online services. Your normal use of their websites, including submitting answers, communicates with those services under their own policies. Browser and Chrome Web Store services may independently contact their providers for installation, updates and browser functions. This policy does not promise that the browser or study websites never communicate with the internet.

You can export saves and diagnostics as JSON files. These are local downloads. Sending a file to a support contact or placing it in a synchronized folder is a separate action you control. Saves may contain progress, timestamps, page-status records (including provider paths) and local identifiers; inspect them before sharing. Diagnostic exports contain extension version, export time, provider names, attachment flags, result/correctness, question types, timestamps and event/session identifiers. They exclude provider paths, tab IDs, study-text/typed-answer fields, run IDs and RPG progress. Diagnostic exports are minimized, not anonymous; timing and identifiers can reveal activity. An in-product explanation and confirmation precede download. Studybound does not automatically upload these exports.

## Consent and monitoring

A first-run disclosure appears in the game/settings UI before monitoring is enabled. Select Enable Studybound to give affirmative consent. Declining or closing it leaves monitoring disabled. Existing installations without recorded consent receive the disclosure. Open Settings → Privacy & monitoring to review it, disable monitoring or enable it again. Withdrawal stops observers, pending study delivery and HUDs, and clears transient study evidence; it does not delete saved progress or historical local records. Save import and ordinary settings changes cannot grant consent, and consent is not transferred from an imported file. This additive preference retains save schema 2.

## Retention, access and deletion

Progress and settings remain in the browser profile until replaced, reset or removed. The engine bounds recent run history to 20 entries, processed answer IDs to 3,000 and enabled grading diagnostic entries to 80. Adapter status is pruned during subsequent activity; it is not guaranteed to disappear at an exact wall-clock time. Browser-session checkpoints and window identifiers use session storage. Current cosmetic text and live evidence use memory.

Use Settings → Save data to export or import a save. Importing replaces the destination save after confirmation. Use Settings → Reset all progression to reset game progress and ordinary settings (the current consent choice is retained); the lobby-class preference is separate and may remain. Clearing the extension's browser storage or uninstalling removes browser-held extension data, subject to browser behavior and any backups. Exported files, backup copies and data independently retained by the study websites are outside that reset and must be managed separately.

Browser storage and JSON exports are not encrypted by Studybound. Browser access controls do not provide a Studybound application-encryption guarantee. Full save backups are not privacy-redacted: imported files may retain additional user-supplied fields, so inspect them before sharing. Protect your device, browser profile and exported files. This version does not provide cloud save recovery or automatic progress transfer between extension identities or profiles.

## Use restrictions and updates

Studybound uses the information it handles only to provide its study-game functionality and related local diagnostics. It does not sell data, use it for personalized advertising or transfer it to data brokers. Its use of data adheres to the Chrome Web Store User Data Policy, including the Limited Use requirements.

If the extension's data practices change, this policy and relevant user disclosures must be updated. For questions, contact [PUBLISHER PRIVACY CONTACT].

## Publisher confirmation before hosting

Confirm publisher identity, contact details, jurisdictional obligations, support-file handling and retention, any privacy-policy hosting logs/cookies, and the intended audience. No claim about an unselected support or hosting provider is made here. Resolve the secure-storage policy question in SECURE_STORAGE_REVIEW.md before submission; no product-specific encryption exemption or complete secure-handling certification has been established. Remove this preparation section and the draft banner only after completing that review. Source evidence is in DATA_FLOW_AUDIT.md; do not publish this draft as a final compliance certification.
