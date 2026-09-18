# Searchability Verification Protocol

Author: Paul Statchen
Date: 2026-09-18

## Core idea

A public posting should not feel like sending a message into a void. A person should be able to publish material in a durable public location and then independently verify that the material is reachable and discoverable through ordinary search.

This is not only a question of whether a file exists at a URL. It includes whether an unrelated person, using a different session, device, location, or network, can find the material through a search engine without relying on the author's account history or social-media distribution.

The proposed approach avoids making social media the central distribution mechanism. Social platforms may be optional announcement channels, but the primary record should remain in durable, directly linked public repositories or archives.

## Working name

The most useful working name is:

**Independent Searchability Verification**

Related terms:

- Public content discoverability
- Search-index verification
- Anonymous retrieval testing
- Cross-context search validation
- Durable public publication
- Search presence monitoring

The phrase **Independent Searchability Verification** describes the testable activity: publish content, then test whether a person who is not relying on the publisher's logged-in context can locate it.

## What the test can establish

A repeatable search test can provide evidence about:

- Whether the URL is publicly accessible.
- Whether a search engine has indexed the URL or related text.
- Whether the content can be found using the author's name, project name, exact title, or subject terms.
- Whether results differ across search engines, devices, browsers, locations, or signed-in states.
- Whether the result remains available at a later date.

It cannot prove that every person will see the same result or that a page will always rank highly. Search systems use factors such as location, language, device, context, personalization, and changing indexes.

## Preliminary verification procedure

For each important publication, record:

1. Publication date and exact public URL.
2. Search engine used: Google, Bing, DuckDuckGo, or another service.
3. Search query used, including exact-name and subject-based queries.
4. Whether the browser is signed in or signed out.
5. Whether private/incognito mode was used.
6. Device type and, if useful, browser type.
7. General location or network context, such as home, library, or mobile network. Do not collect unnecessary personal data.
8. Whether the URL appears, approximately where it appears, and whether the result opens correctly.
9. Whether the page content and author attribution are clear once opened.
10. The date and time of the test.

Possible test queries include:

- `"Paul Statchen"`
- `"Paul Statchen" GitHub`
- `"Paul Statchen" [project title]`
- The exact page title in quotation marks.
- `site:github.com/paulsailchen55-rgb`
- The exact public URL pasted into the search engine's search field.

## Important distinction

Incognito mode reduces use of the browser's existing local session, but it does not make a search completely neutral. Search results can still vary because of location, language, device, network, search-engine data centers, and other context. A different device or public network can provide an additional comparison, not an absolute guarantee of anonymity.

For pages the publisher controls, Google Search Console can provide a separate technical check of whether Google knows about a URL, whether it is indexed, and whether there are crawl or indexing problems. Search Console's indexing status is not the same as a guarantee of prominent placement in search results.

## Design objective

Create a lightweight, repeatable system that combines:

- Durable publication in public repositories or archives.
- Clear links between the author's name, archive, projects, and individual documents.
- Consistent titles and author attribution.
- Search-engine indexing checks where the platform permits them.
- Independent retrieval tests performed from more than one context.
- A dated log of results and failures.
- Periodic rechecking so that links, access, and discoverability are not assumed to remain permanent.

A possible future automation could check URL availability, follow authorized public links, record search-console data where available, and maintain a human-reviewed log. Automated search scraping should be evaluated carefully because search providers may restrict automated queries, change interfaces, or prohibit certain forms of collection.

## Why this matters

The goal is not to guarantee that every publication reaches the right person. The goal is to replace pure hope with a measurable chain:

**Publish → link → index or submit → independently search → retrieve → record → recheck.**

This creates a practical distinction between content merely being posted somewhere and content having a documented, testable public presence.

## Sources for further study

- Google Search Console URL Inspection: https://support.google.com/webmasters/answer/12482179
- Google Search Console indexing guidance: https://support.google.com/webmasters/answer/7440203
- Google guidance on requesting recrawls: https://developers.google.com/search/docs/crawling-indexing/ask-google-to-recrawl
- Google explanation of differences in search results: https://support.google.com/websearch/answer/12412910
