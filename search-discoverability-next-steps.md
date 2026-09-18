# Search Discoverability: Preliminary Test and Next Steps

Author: Paul Statchen
Date: 2026-09-18

## Purpose

This note records a preliminary approach for making Paul Statchen's public research and project archive easier to find by name, without depending on social media.

The current approach uses:

- A public GitHub repository with the author's name in the README.
- Links from `Gwhatisithub` to the larger `apo` archive.
- Descriptive subject terms connected to the author's work.
- A possible future GitHub profile repository named exactly `paulsailchen55-rgb`.
- Clear links among the author's profile, archive, project folders, and individual research notes.

## What has been verified

GitHub officially supports a profile README when a public repository has the exact same name as the GitHub username and contains a root-level `README.md`. For this account, the possible profile repository would be:

`paulsailchen55-rgb/paulsailchen55-rgb`

GitHub also supports repository READMEs, profile information, and pinned repositories as ways to present and connect public work.

This does not guarantee that Google, Bing, or GitHub search will rank the author's name prominently. Indexing and ranking depend on each search system and may take time.

## Terminology to test

There is no single universally established name for this exact practice. Useful working terms include:

- **Name-based public archive discoverability**
- **Identity-linked project discoverability**
- **Personal research archive indexing**
- **Cross-repository identity linking**
- **Public knowledge-portfolio architecture**
- **Organic search discoverability**
- **Independent searchability verification**
- **Human-in-the-loop search verification**
- **Search presence monitoring**

The most straightforward working label for this project is:

**Name-Based Public Archive Discoverability**

The verification component can be called:

**Independent Human Searchability Verification**

These labels describe the goal without claiming that search-engine placement is guaranteed.

## Expanded concept: independent human verification

A person may publish a page or document publicly but still have little practical knowledge of whether an unrelated person can find it. This project proposes a voluntary, privacy-respecting network of human testers who perform short searches using ordinary devices and networks, then report what they actually observed.

A tester could:

1. Receive a standardized search instruction.
2. Use a normal browser, private/incognito window, or another device.
3. Search one or more specified search engines using an exact query.
4. Record whether the target appears, its approximate result position, and whether the link opens.
5. Record context such as date, general region, device type, browser, and search engine, without collecting unnecessary personal information.
6. Submit the result to a central database for comparison over time.

This is similar in structure to a CAPTCHA or distributed human verification task, but the purpose is not to distinguish humans from bots. The purpose is to measure public discoverability and retrieval from outside the publisher's own account.

The system should avoid treating testers as disposable labor. Participation should be voluntary, compensated when feasible, transparent about data collection, and designed to require only a few minutes. It should not encourage manipulation of rankings, artificial clicking, spam, or coordinated attempts to influence search results.

## What the database could measure

Possible fields include:

- Test date and time.
- Search engine used.
- Exact search query.
- General location or region, if voluntarily provided.
- Device and browser category.
- Whether the target appeared in the results.
- Approximate result position or result-page number.
- Whether the result title and description were understandable.
- Whether the target page opened successfully.
- Whether the page was blocked, redirected, broken, or inaccessible.
- Whether the result appeared to be a stale copy or a current page.
- Notes about major changes in the search results.

The database could create a time series showing whether a public document remains discoverable, becomes harder to find, disappears from results, or becomes inaccessible. A single failed search would not prove that a page is absent from an index; it would be one observation within a larger monitoring system.

## Important distinctions

The project should distinguish among:

- **Existence:** the page or file is published and can be opened through a direct link.
- **Indexation:** a search engine has included the page in its searchable index.
- **Discoverability:** a person can find the page using a relevant query.
- **Retrievability:** the person can open and read the target after finding it.
- **Persistence:** the page remains available over time.
- **Prominence:** the page appears near the top of results. This is a changing measurement, not a permanent property.
- **Independence:** the test was conducted by someone other than the publisher and outside the publisher's logged-in context.

A page can exist and be retrievable by direct URL while remaining poorly indexed or difficult to discover through search.

## Automation and technical support

Automation could help with link checks, timestamping, duplicate detection, and assembling reports. Human testing may still be useful for search results that vary by context, personalized interfaces, anti-bot controls, and differences in how understandable or usable a result is.

A responsible design would use automation for repetitive checks and humans for limited observations that require ordinary user context. It should not attempt to bypass access controls, defeat anti-bot protections, generate fake engagement, or overload search services.

## Steps to complete later

1. Review the current `Gwhatisithub` README and the `apo` archive index.
2. Create a dedicated public repository named exactly `paulsailchen55-rgb` if desired.
3. Add a concise profile README introducing Paul Statchen and linking to `apo` and other major repositories.
4. Pin a small number of representative repositories on the GitHub profile.
5. Ensure each major repository has a clear README, author attribution, subject terms, and links back to the central archive.
6. Use consistent author wording: `Paul Statchen`.
7. Use consistent geographic context only where relevant, such as `Santa Cruz County, California`.
8. Keep factual distinctions visible: documented information, research questions, observations, speculative concepts, and proposals requiring verification.
9. Establish baseline searches from the publisher's own device, then repeat them from an independent browser, device, and network such as a public library connection when appropriate.
10. Record the date, exact query, search engine, approximate result position, direct-link success, and relevant test context.
11. Repeat the same tests periodically to observe changes rather than treating one search as conclusive.
12. Revisit repository descriptions and topics manually in GitHub, since the current connection can update files but cannot change those repository settings.
13. Investigate whether a small voluntary human-testing pilot can be designed with consent, privacy protections, fair compensation, and anti-manipulation safeguards.

## Evidence and limits

This is a preliminary discoverability experiment, not a guarantee of search ranking, identity verification, or creation of a formal knowledge-graph entity. The purpose is to create a coherent, publicly linked body of work that search systems and human readers can potentially understand.

Search results are measurements of a particular time and context. They should be recorded as observations, not treated as permanent judgments about the value or legitimacy of the underlying work.

## Reference

GitHub documentation:

- https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/about-readmes
- https://docs.github.com/en/account-and-profile/concepts/personal-profile
- https://docs.github.com/en/account-and-profile/tutorials/using-your-github-profile-to-enhance-your-resume
