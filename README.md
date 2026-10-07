# Vont SEO Tools: Releases

Downloads and the update feed for **Vont SEO Tools**, EthosVont's native macOS SEO crawler for site audits.

**[⬇ Download the latest version](https://github.com/VONTWEB/VONT-SEO-Tool-Releases-/releases/latest)**

This repository only holds signed releases (DMGs) and `appcast.xml`, which the app checks for updates. The source
code is private.

## Install

1. Download `VontSEOTools-<version>.dmg` from the [latest release](https://github.com/VONTWEB/VONT-SEO-Tool-Releases-/releases/latest).
2. Open it and drag **Vont SEO Tools** to **Applications**.
3. Launch it from Applications. A short welcome guide walks you through your first crawl.

Releases are signed with a Developer ID and notarized by Apple, so they open without Gatekeeper warnings.

**Requirements:** macOS 14 Sonoma or later, on Apple Silicon or Intel.

## Updates

The app checks this repository for new versions and offers to install them. You can also check by hand from
**Vont SEO Tools › Check for Updates…**, and turn automatic checks on or off in **Settings › General**.

## What it does

- **Crawls a site** (spider, URL list or sitemap) with polite defaults, optionally rendering JavaScript.
- **Audits every page** against 90+ rules and gives the site a 0–100 health score. Each issue explains why it
  matters and how to fix it, with WordPress and Shopify specifics.
- **Builds the client report**: the Technical SEO Audit workbook (.xlsx) and a branded PDF, with Google
  Analytics 4 and Search Console data joined in.
- **Tracks sites over time** with projects, crawl comparisons, re-audits and scheduled crawls that notify you
  when things get worse.
- **Checks Core Web Vitals** for key pages with PageSpeed Insights.

## Keyboard shortcuts

| Shortcut | Action |
|---|---|
| ⌘↩ | Start crawl |
| Space | Pause or resume the running crawl |
| ⌘. | Stop crawl |
| ⌘O | Open a saved crawl |
| ⌘E | Export the audit workbook |
| ⇧⌘E | Export the PDF report |
| ⌥⌘E | Export the current table as CSV |
| ⌥⌘G | Analytics (GA4 and Search Console) |
| ⇧⌘A | Re-run the audit |
| ⌘I | Show or hide the inspector |
| ⌘0 | Projects |
| ⌘1–⌘9 | Audit Report, Dashboard, All Pages, Issues, Images, Links, Redirects, Canonicals, Structured Data |

## Privacy

- Crawls are saved on your Mac in `~/Library/Application Support/VontSEOTools/`. Nothing is uploaded.
- Google sign-in tokens and the PageSpeed API key are stored in the macOS Keychain.
- The app only connects to the sites you crawl, to Google's APIs when you use them, and to GitHub to check
  for updates.
