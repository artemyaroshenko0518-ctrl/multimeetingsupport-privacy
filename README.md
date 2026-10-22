# MultiMeetingSupport — Privacy Policy

Last updated: October 22, 2026

## Purpose

The extension transfers visible captions from Microsoft Teams and Zoom web meetings to the MultiMeetingSupport companion application on the same computer.

## Data processed

Caption text, displayed speaker names, caption timestamps, meeting session identifiers and the selected meeting provider. A random installation identifier and a per-source local pairing token connect this browser profile to the companion application. Account labels are chosen by the user. The extension does not request microphone access or record meeting audio or video, and does not read unrelated browser tabs or browsing history.

## Local storage and transfer

Pairing settings and a retry queue are stored using chrome.storage.local in the browser profile. The retry queue is capped at 3,000 caption events. Successfully delivered events are removed from the queue. The extension sends captions only to http://127.0.0.1:5187, the local companion application. It contains no developer-operated analytics, advertising or cloud-upload endpoint and no remotely executed code.

## Companion app and AI

The separately installed companion application stores meeting transcripts, context summaries, notes, answers and settings on the user's computer. If the user connects ChatGPT and enables background updates or requests an answer, the companion application sends the relevant meeting text and supplied context to OpenAI. This is not an entirely offline product when AI features are enabled. OpenAI's applicable terms and privacy information apply to that processing. The extension itself does not hold the user's ChatGPT credentials.

## Control and retention

Disable caption capture by turning off meeting captions or disabling the extension. Disconnect/revoke a source by removing or disabling its profile in the companion app. Removing the browser extension removes its extension-local storage; it does not erase data already delivered to the companion application. Uninstalling the companion application intentionally preserves its local data. Users must separately delete local meeting files if they want to erase that history.

## Use and disclosure

The publisher does not sell meeting data or use it for advertising. Processing is limited to the stated meeting-caption and assistance functionality. Transfers initiated by the companion app are limited to the configured AI functionality. Use of information received from Google APIs will adhere to the Chrome Web Store User Data Policy, including Limited Use requirements.

## Contact

For questions about privacy, local data or support, contact artem.yaroshenko0518@gmail.com. Do not email meeting transcripts, account tokens or passwords.

## Policy website

This policy is hosted using GitHub Pages. GitHub may process standard request and technical information when you visit this website under its own privacy statement. The page includes no publisher analytics or advertising.

