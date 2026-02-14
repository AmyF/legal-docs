---
title: QuickNAS Support
description: QuickNAS support and bug reporting guide
permalink: /quicknas/support-en
last_updated: 2026-02-13
---

# QuickNAS Support

Last updated: February 13, 2026

Need help with QuickNAS? This page explains how to contact us and what information helps us resolve issues quickly.

## 1. Contact

- Support email: `support@unko.fun`
- Terms: [QuickNAS Terms of Service](/quicknas/terms-en)
- Privacy: [QuickNAS Privacy Policy](/quicknas/privacy-en)

## 2. Before You Contact Support

Please prepare:

- QuickNAS app version and build
- macOS version
- Login method used (Direct URL or QuickConnect)
- Whether the issue happens in direct upload or upload-and-share mode
- Steps to reproduce
- Expected result vs actual result

## 3. Recommended: Report Bug from the App

In QuickNAS:

1. Open **Settings**
2. Go to **About**
3. Click **Report Bug (support@unko.fun)**

QuickNAS will prepare an email draft and include recent diagnostic information for your review.

Typical attachments may include:

- `support-info.json` (app/environment snapshot)
- `recent-client.log` (recent client logs)
- A ZIP package containing the above files (when packaging succeeds)

You can review and edit everything before sending.

## 4. Manual Email Template

If you prefer manual email, send to `support@unko.fun` with:

- Subject: `[QuickNAS Bug] <version> (<build>)`
- Device/macOS details
- NAS endpoint type (Direct URL or QuickConnect)
- Error message text (full text if possible)
- Reproduction steps
- Screenshots or logs (if available)

## 5. Common Issues

### A. Cannot connect to NAS

Check:

- NAS address/QuickConnect ID is correct
- NAS is reachable from your current network
- Port and protocol configuration are correct for your NAS

### B. Session requires login again

This can happen when:

- NAS session expired
- Password/OTP changed
- Account endpoint settings were edited

Use the account detail page to log in again and re-establish session.

### C. Upload conflict handling not as expected

Check **Settings > General > Duplicate File Handling**:

- **Overwrite**: replace existing file on target path
- **Skip**: skip only the conflicting file; other files should continue

### D. Upload and Share package issues

For multiple files (or folder uploads that require packaging), QuickNAS applies the configured package-size limit.

- Current app limit supports up to 4 GB package size
- If limit is exceeded, adjust settings or split uploads

## 6. Support Scope

We can help with:

- QuickNAS app behavior
- Login/session flow in QuickNAS
- Upload/share workflow and settings behavior
- App log interpretation

We may not be able to provide full support for:

- NAS firmware/internal server issues unrelated to app behavior
- Third-party network infrastructure problems
- Custom scripts/plugins outside QuickNAS

## 7. Response Time

We aim to respond as soon as possible. Actual response time depends on issue complexity and message volume.

Including complete reproduction steps and logs significantly speeds up triage.

