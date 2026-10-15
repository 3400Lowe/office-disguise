---
layout: default
title: Privacy policy
---

# Privacy policy

Last updated: 15 October 2026. Covers Office Disguise version 1.0.0.

Publisher: **3400lowe**, an individual based in the United Kingdom. Privacy contact: **[info@quotesbytrades.co.uk](mailto:info@quotesbytrades.co.uk)**.

Office Disguise has no server, analytics, advertising, account registration, payment processing or cloud sync. It does not collect or transmit your posts, credentials, cookies or browsing history to its developer.

## What it reads

The extension reads Reddit and X content that the site has already loaded in your tab, to display it in its inbox layout. The extension does not send this content to its developer. Displaying media, navigating and using native site controls can make normal requests to the sites and their media providers.

To show a post's comments or replies, it uses the site's own pages in your normal session:

- **Reddit:** it loads the selected post's own page in a hidden frame within the same tab. This is one ordinary page view per post you select.
- **X:** it opens the selected post within X's own app.

Videos you play are shown from the site's own player within the page.

## What it stores

| Data                                                                                                                                                     | Where                                                                                           | How long                                                           |
| -------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------- | ------------------------------------------------------------------ |
| Your settings: on/off switches, header name, tab titles, theme, display preferences, keyboard shortcuts                                                  | Chrome's local extension storage, on this device only                                           | Until you change them or uninstall                                 |
| Which feed and post each tab was showing (page addresses and a post ID), so a refresh can restore the view                                               | Chrome's session extension storage                                                              | Removed when the tab closes; cleared when the browser session ends |
| A marker that a tab was opened with "Open original post" (tab ID only)                                                                                   | Chrome's session extension storage                                                              | Removed when the tab closes                                        |
| The search results page you opened a community or profile from (its address and query), and the message list's scroll position for up to 20 recent pages | The site tab's own session storage (`sessionStorage`), readable by that site like any page data | Cleared when the tab closes                                        |
| The chosen theme name (`outlook` or `gmail`), so the loading frame matches before settings load                                                          | The site's own `localStorage`, readable by that site                                            | Until site data is cleared                                         |
| Up to 200 loaded posts per page, plus read/unread state                                                                                                  | Page memory only                                                                                | Gone when the tab navigates or closes                              |

## Permissions

The only extension permission is `storage`. Content scripts run only on `reddit.com`, `www.reddit.com`, `x.com`, `www.x.com`, `twitter.com` and `www.twitter.com`. The extension does not request Chrome permissions to read cookies, browser history or downloads. It reads page content and addresses on the supported sites as described above. There is no remote code.

## The sites themselves

Reddit and X continue to control your account, login, feeds, advertising and social actions. Native controls you use have their ordinary effects on those sites. Viewing images and videos loads media the site already supplies, and links, searches and "Open original post" navigate normally.

## Turning it off

Disable a site or the whole inbox view in the extension's settings, or use **Show original site**. Uninstalling removes the extension's stored settings. Developer test profiles and screenshots are not part of the extension package.

Uninstalling does not necessarily remove values in the sites' own localStorage or sessionStorage. Close site tabs and clear the relevant Reddit/X site data to remove those values; doing so may sign you out.

## Support enquiries and public issues

If you contact the publisher, the publisher receives the information you choose to send, such as your email address, GitHub username, message and attachments. This is separate from the extension: it does not automatically send diagnostic reports. Support information is used to reply, investigate problems and maintain the extension, not for marketing or sale. The lawful basis for this support processing is legitimate interests in answering enquiries, resolving faults and keeping the product secure.

Email is processed by the publisher's email provider. GitHub hosts this documentation and public issues. Information posted to GitHub Issues is public and may remain accessible after an issue is closed. Do not include passwords, private content, cookies or tokens. For private concerns, email instead.

Support correspondence is retained only as long as needed to resolve the enquiry, follow up on related faults, or meet applicable legal obligations. Public technical issue records may remain useful as a project history; contact the publisher to request removal of personal details. The publisher does not control independent copies or the hosting providers' own retention.

## Hosting and other services

The documentation uses GitHub Pages without publisher-added analytics or tracking scripts. GitHub may process visitor connection information such as IP addresses under its own privacy statement. GitHub, email providers, Reddit, X and Chrome Web Store operate their own services; their processing is separate from local extension storage. This policy does not promise that those services store information only in the UK. See [GitHub's privacy statement](https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement).

## Your rights and contact

For personal information held by the publisher through support, you may request access, correction, deletion or restriction, and portability where applicable, by emailing info@quotesbytrades.co.uk. Rights depend on the circumstances. The publisher cannot retrieve or remotely delete settings and posts that remain only in your browser.

**You may object to support processing based on legitimate interests.** Contact the same address to exercise this right.

You can also raise a concern with the UK Information Commissioner's Office at [ico.org.uk/make-a-complaint](https://ico.org.uk/make-a-complaint/). There is no developer-run profiling or automated decision-making about you.

## Changes

Updates to this policy will be published here with a revised date. Any future account, paid-feature or data-handling changes will require corresponding disclosures; they are not part of this version.
