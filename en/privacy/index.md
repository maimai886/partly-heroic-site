---
layout: doc
lang: en
key: "privacy/"
legal: true
title: "Privacy Policy | Partly Heroic"
heading: "Partly Heroic Privacy Policy"
description: "Privacy policy for Partly Heroic (iOS): the game does not collect any personal data."
---
{% comment %}
Source: game repo docs/store/privacy.md, English part (draft 2026-10-08; not lawyer-reviewed, not native-speaker reviewed).
Website changes vs. the source: §7 covers the GitHub Issues support page (no support email yet), new §8 covers this website.
{% endcomment %}
This policy explains how the iOS app "Partly Heroic" (the "Game") handles your data. The Game is operated by {{ site.operator[page.lang] }} ("we", "us").

## 1. Summary

**The Game does not collect any personal data.** There is no account, no internet connection, no advertising and no analytics or tracking. Your progress is stored only on your own device. We cannot see it or access it.

## 2. Data we do not collect

The Game does not collect, transmit or share any of the following: name, email address, phone number, date of birth, location, contacts, photos, device identifiers, the advertising identifier (IDFA), IP address, usage data, purchase history or crash logs.

The Game uses no third-party analytics, advertising, sign-in or tracking services, and it does not track you across other companies' apps or websites.

## 3. Data stored on your device

- **Game save:** your progress (stages, hero levels, gear, gold and so on) is stored in the Game's own storage on your device. It is never sent to us or to anyone else.
- **Device backups:** if you use iCloud Backup or back up to a computer, Apple's backup may include the save. That is a service provided by Apple under Apple's privacy policy, and we have no access to it.
- **Deleting it:** deleting the Game deletes the save from your device. We keep no copy, so it cannot be restored.

## 4. Picture in Picture

The Game uses iOS Picture in Picture to show the game. Everything shown in the Picture in Picture window is generated live on your device. It does not use the internet, does not record anything and does not read content from other apps.

## 5. Data provided by Apple

If you choose to share analytics with app developers in your device settings, Apple may provide us with anonymous crash reports and usage statistics. You control this in iOS Settings and can turn it off at any time (Settings > Privacy & Security > Analytics & Improvements). We use this information only to fix bugs.

## 6. Children

The Game does not collect personal data from anyone, including children.

## 7. When you contact us

- **Issue page (GitHub Issues):** support currently runs through this website's issue page on GitHub. What you submit there is **public** on GitHub, including your GitHub username and what you write, and GitHub's privacy statement applies. Please do not include your name, email address, phone number, address or other personal details. We use your report only to deal with your question. If you want your report removed, leave a comment on it and we will delete it.
{%- if site.support_email != "" %}
- **Email:** if you email our support address, we receive your email address and your message. We use them only to answer you and delete them within 12 months after your request is resolved. You do not need to include your name or other personal details.
{%- endif %}

## 8. This website

This website is hosted on GitHub Pages. It uses no cookies and no analytics, advertising or tracking tools, and it loads no fonts or scripts from other sites. As the host, GitHub may log technical data such as visitors' IP addresses for security and operations, under the [GitHub General Privacy Statement](https://docs.github.com/site-policy/privacy-policies/github-general-privacy-statement).

## 9. Changes to this policy

If a future version of the Game adds features that process data (for example accounts or cloud saves), we will update this policy before that version is released, show the new effective date on this page and notify you in the Game. Data that existed before the new feature is not affected.

## 10. Contact

- Support: [support page]({{ '/en/support/' | relative_url }}) ([issue page]({{ site.issues_url }}))
{%- if site.support_email != "" %}
- Support email: <{{ site.support_email }}>
{%- endif %}
- Website: <{{ site.url }}{{ site.baseurl }}/en/>

If the Traditional Chinese, Japanese and English versions differ, the version in the language of your App Store storefront applies (Taiwan: Traditional Chinese; Japan: Japanese; other storefronts: English).
