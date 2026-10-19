# Security Review — HeziLiu

**Scope:** Every repository visible under the GitHub account `HeziLiu`, originals and forks included.
**Ecosystem background:** Python (pip) and Node (npm) — one currently published high-severity advisory recorded for each.
**Purpose:** Quarterly engineering review — security posture write-up, published as a linkable document rather than slides.

---

## Account summary

| Field | Value |
|---|---|
| Login | `HeziLiu` |
| Name | Hezi Liu |
| Public repositories | 4 (2 original, 2 forks) |
| Account created | 2017-05-22 |

Four repositories were found under the account: `Little-rookie` and `Big-Buzzard` (originals), plus `CodingInterviewChinese2` and `awesome-chatgpt-prompts-zh` (forks). The audited footprint is personal/educational in nature and contains **no Python or Node services of its own**; the Python and Node advisories below are provided as background context for the wider engineering estate that ships those ecosystems.

---

## Repository: Little-rookie

- **URL:** https://github.com/HeziLiu/Little-rookie
- **Type:** Original (not a fork) · Public
- **Description:** "Undergraduate coursework"
- **Primary language:** Java
- **Default branch:** `master`
- **Created:** 2018-05-15 · **Last push:** 2019-06-02 (dormant ~7 years)

### Recent commit history

| SHA | Message | Author | Date |
|---|---|---|---|
| `964bd6b` | DELETE | HeziLiu | 2019-06-02 |
| `0636706` | new demo | HeziLiu | 2019-05-05 |
| `9010059` | Merge branch 'master' of https://github.com/Tackic/Little-rookie | HeziLiu | 2019-04-28 |
| `d412f71` | add readme.md | HeziLiu | 2019-04-28 |
| `7021a8c` | add UI&demo — "far from completed orz...." | HeziLiu | 2019-04-28 |

Commits are sparse and non-descriptive ("DELETE", "new demo", "……"), with no review workflow or branch protection evident.

### Open issues and discussion

**None.** The repository has 0 open issues, so there is no most-recently-updated issue and consequently no issue discussion to report.

### Most recent Actions run

**No workflows.** This repository has no GitHub Actions workflows at all, so there is no most recent run to report.

### Open code scanning alerts

**None.** No code scanning alerts are present. No workflows exist and no default-setup code scanning analysis is configured, so no alerts could have been generated. (Note: the code-scanning alerts API endpoint returned a 403 for the token used to produce this report, so this could not be independently re-verified against the live alert list.)

---

## Repository: Big-Buzzard

- **URL:** https://github.com/HeziLiu/Big-Buzzard
- **Type:** Original (not a fork) · Public
- **Description:** "For future...."
- **Default branch:** `master`
- **Created:** 2018-05-15 · **Last push:** 2018-05-17 (dormant ~8 years)

### Recent commit history

| SHA | Message | Author | Date |
|---|---|---|---|
| `4ce5a6d` | Merge branch 'master' of https://github.com/Tackic/Big-Buzzard | HeziLiu | 2018-05-17 |
| `8cafeb1` | first_commit | HeziLiu | 2018-05-17 |
| `0ec9dbc` | first commit | HeziLiu | 2018-05-17 |
| `8da4156` | Initial commit | HeziLiu | 2018-05-15 |

The repository is effectively empty (reported repository size is 0 KB) and has seen no activity since May 2018.

### Open issues and discussion

**None.** The repository has 0 open issues, so there is no most-recently-updated issue and consequently no issue discussion to report.

### Most recent Actions run

**No workflows.** This repository has no GitHub Actions workflows at all, so there is no most recent run to report.

### Open code scanning alerts

**None.** No code scanning alerts are present. No workflows exist and no default-setup code scanning analysis is configured, so no alerts could have been generated. (The code-scanning alerts API endpoint returned a 403 for the token used to produce this report.)

---

## Repository: CodingInterviewChinese2

- **URL:** https://github.com/HeziLiu/CodingInterviewChinese2
- **Type:** Fork (upstream: zhedahht/CodingInterviewChinese2) · Public
- **Description:** 《剑指Offer》第二版源代码 ("Coding Interview" 2nd edition source code)
- **Primary language:** C++
- **Default branch:** `master`
- **Issues:** Disabled on this fork
- **Created:** 2019-03-12 · **Last upstream activity:** 2018-12-28

### Recent commit history

| SHA | Message | Author | Date |
|---|---|---|---|
| `2d6eb6d` | Minor changes on license comments | zhedahht | 2016-12-07 |
| `35e871d` | Move lincense information into a file | zhedahht | 2016-12-07 |
| `4f23f2a` | Encoding the license file with UTF-8 | zhedahht | 2016-12-07 |
| `03f9a3a` | Add the license file | zhedahht | 2016-12-07 |
| `444a4e5` | Add BSD open source license term | zhedahht | 2016-12-06 |

All commits are inherited from upstream; the fork has no commits of its own. The fork is many years stale relative to its parent.

### Open issues and discussion

**None.** The repository has 0 open issues (issues are disabled on this fork), so there is no most-recently-updated issue and consequently no issue discussion to report.

### Most recent Actions run

**No workflows.** This repository has no GitHub Actions workflows at all, so there is no most recent run to report.

### Open code scanning alerts

**None.** No code scanning alerts are present. No workflows exist and no default-setup code scanning analysis is configured, so no alerts could have been generated. (The code-scanning alerts API endpoint returned a 403 for the token used to produce this report.)

---

## Repository: awesome-chatgpt-prompts-zh

- **URL:** https://github.com/HeziLiu/awesome-chatgpt-prompts-zh
- **Type:** Fork (upstream: PlexPt/awesome-chatgpt-prompts-zh) · Public
- **Description:** ChatGPT 中文调教指南。各种场景使用指南。学习怎么让它听你的话。
- **Primary content:** Markdown (prompt collection)
- **Default branch:** `main`
- **Issues:** Disabled on this fork
- **Created:** 2023-04-14 · **Last upstream activity:** 2023-04-13

### Recent commit history

| SHA | Message | Author | Date |
|---|---|---|---|
| `2d1ff55` | Merge pull request #127 from layyback/main — ":pencil2: fix typo" | PlexPt | 2023-04-13 |
| `4c180da` | :pencil2: fix typo | layyback | 2023-04-12 |
| `5cd796d` | Update README.md | PlexPt | 2023-04-12 |
| `036e678` | Update README.md | PlexPt | 2023-04-12 |
| `f8e6613` | Update README.md | PlexPt | 2023-04-11 |

All commits are inherited from upstream; the fork has no commits of its own and carries no executable code.

### Open issues and discussion

**None.** The repository has 0 open issues (issues are disabled on this fork), so there is no most-recently-updated issue and consequently no issue discussion to report.

### Most recent Actions run

**No workflows.** This repository has no GitHub Actions workflows at all, so there is no most recent run to report.

### Open code scanning alerts

**None.** No code scanning alerts are present. No workflows exist and no default-setup code scanning analysis is configured, so no alerts could have been generated. (The code-scanning alerts API endpoint returned a 403 for the token used to produce this report.)

---

## Ecosystem advisories (Python and Node)

One currently published, high-severity advisory from the GitHub global security advisory database, recorded for each of the two ecosystems our estate ships.

### Python (pip)

| Field | Value |
|---|---|
| GHSA identifier | **GHSA-5wr8-gcqf-gqf3** |
| Severity | **high** |
| Affected package | **aiohttp** |
| Summary (as reported) | aiohttp server lacks an initial request/header timeout |
| CVE | CVE-2026-111064 |
| Vulnerable range | <= 3.14.3 |
| First patched version | 3.14.4 |
| Published | 2026-10-19 |

The keepalive timeout was not applied during the initial portion of a request, so an attacker could keep an idle connection open indefinitely before sending any data. Recommended remediation is upgrading to aiohttp 3.14.4, or fronting the service with a reverse proxy that enforces sensible keepalive limits.

### Node (npm)

| Field | Value |
|---|---|
| GHSA identifier | **GHSA-pq7j-f95f-qfcv** |
| Severity | **high** |
| Affected package | **@anthropic-ai/claude-code** |
| Summary (as reported) | Claude Code: Plugin Hash Pin Bypass Allows Bypass of Hash Pinning |
| CVE | CVE-2026-86063 |
| Vulnerable range | < 2.1.179 |
| First patched version | 2.1.179 |
| Published | 2026-10-15 |

The plugin install flow checked out a marketplace's pinned commit SHA using `git checkout` without verifying that the resulting HEAD matched the pinned SHA, allowing an attacker controlling a plugin's upstream repository to install attacker-controlled code while bypassing the pinned hash. Users on standard auto-update have already received the fix; manual updaters should move to 2.1.179 or later.

---

## Recommended next steps

- **Add code scanning to any repository that begins shipping Python or Node code.** None of the four audited repositories currently has GitHub Actions workflows or a default-setup code scanning analysis, so there is no automated static analysis anywhere in the account.
- **Retire or archive dormant repositories.** `Big-Buzzard` has been untouched since May 2018 and is effectively empty, and `Little-rookie` has been dormant since June 2019. Archiving them reduces the audited surface and removes them from automated scanning of stale content.
- **Sync or delete stale forks.** `CodingInterviewChinese2` and `awesome-chatgpt-prompts-zh` have no commits of their own and are several years behind their upstreams. If they are not being used, delete them; if they are, sync them with upstream.
- **Upgrade Python services off aiohttp <= 3.14.3.** Apply the GHSA-5wr8-gcqf-gqf3 fix (aiohttp 3.14.4+) wherever aiohttp serves traffic, and confirm a reverse proxy enforces keepalive limits.
- **Upgrade Node tooling off @anthropic-ai/claude-code < 2.1.179.** Apply the GHSA-pq7j-f95f-qfcv fix, and treat plugin hash pinning as untrusted until patched.
- **Improve commit hygiene.** Messages such as "DELETE", "……" and "new demo" make incident response and audit trails hard; adopt a lightweight conventional-commit standard going forward.
- **Grant the reporting integration read access to security endpoints.** The token used for this review was denied the code-scanning, secret-scanning and Dependabot alert endpoints, so those signals had to be inferred from the absence of workflows rather than read directly. Widening the token's scopes would make the next quarterly review verifiable end to end.
