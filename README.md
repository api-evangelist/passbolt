# Passbolt

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Passbolt is an open source password manager for teams. The Passbolt API provides programmatic access to manage resources (passwords), folders, users, groups, sharing, comments, metadata, and authentication via GPGAuth or JWT.

**Areas:** Password Manager · Security · Secrets · Identity

## Passbolt on APIs.io

Everything profiled for Passbolt is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/passbolt/](https://apis.io/providers/passbolt/)** — or go straight to one of the APIs or properties below.

### APIs (27)

- [Passbolt Authentication (GPGAuth) API](https://apis.io/apis/passbolt/passbolt-authentication-gpgauth-api/) — The legacy authentication method, using the GPGAuth protocol. Find more [here](https://www.passbolt.com/docs/development/authentication).
- [Passbolt Authentication (JWT) API](https://apis.io/apis/passbolt/passbolt-authentication-jwt-api/) — JWT-based authentication is the preferred way to interact with the Passbolt API. Find more [here](https://www.passbolt.com/docs/development)
- [Passbolt Avatars API](https://apis.io/apis/passbolt/passbolt-avatars-api/) — Query avatar images.
- [Passbolt Comments API](https://apis.io/apis/passbolt/passbolt-comments-api/) — Manipulate comments for resources.
- [Passbolt Directory Sync API](https://apis.io/apis/passbolt/passbolt-directory-sync-api/) — Run directory synchronization.
- [Passbolt Favorites API](https://apis.io/apis/passbolt/passbolt-favorites-api/) — The favorite endpoints are used to add or remove a `Resource` from your favorites.
- [Passbolt Folders API](https://apis.io/apis/passbolt/passbolt-folders-api/) — Organize your passwords and share them in bulk using folders.
- [Passbolt GPG keys API](https://apis.io/apis/passbolt/passbolt-gpg-keys-api/) — In order to encrypt information, the server and the clients needs the user's public keys. These OpenPGP endpoints let you query the saved public key data.
- [Passbolt Groups API](https://apis.io/apis/passbolt/passbolt-groups-api/) — Organize users in logical groups to make it easier to share resources with them.
- [Passbolt Metadata keys API](https://apis.io/apis/passbolt/passbolt-metadata-keys-api/) — Manipulate metadata keys.
- [Passbolt Metadata private keys API](https://apis.io/apis/passbolt/passbolt-metadata-private-keys-api/) — Manipulate private keys for metadata.
- [Passbolt Metadata rotate key API](https://apis.io/apis/passbolt/passbolt-metadata-rotate-key-api/) — Gather information about metadata keys that needs to be rotated
- [Passbolt Metadata session key API](https://apis.io/apis/passbolt/passbolt-metadata-session-key-api/) — Gather information on the saved encrypted session keys cache
- [Passbolt Metadata types settings API](https://apis.io/apis/passbolt/passbolt-metadata-types-settings-api/) — Retrieve information about the resource types settings selected by the administrators
- [Passbolt Metadata upgrade API](https://apis.io/apis/passbolt/passbolt-metadata-upgrade-api/) — Upgrading elements to the new v5 metadata format
- [Passbolt Move API](https://apis.io/apis/passbolt/passbolt-move-api/) — Move a folder or a resource across folders.
- [Passbolt Multi-Factor Authentication API](https://apis.io/apis/passbolt/passbolt-multi-factor-authentication-api/) — Complete and validate authentication for users with MFA enabled.
- [Passbolt Permissions API](https://apis.io/apis/passbolt/passbolt-permissions-api/) — Query permissions for resources.
- [Passbolt Resource types API](https://apis.io/apis/passbolt/passbolt-resource-types-api/) — Resource-types are used for describing how and what data is stored for a resource and its associated secrets.
- [Passbolt Resources API](https://apis.io/apis/passbolt/passbolt-resources-api/) — A resource holds the metadata for its secrets.
- [Passbolt Roles API](https://apis.io/apis/passbolt/passbolt-roles-api/) — Different categories of users.
- [Passbolt Secrets API](https://apis.io/apis/passbolt/passbolt-secrets-api/) — Secrets associated to resources.
- [Passbolt Settings API](https://apis.io/apis/passbolt/passbolt-settings-api/) — Retrieve the server settings
- [Passbolt Shares API](https://apis.io/apis/passbolt/passbolt-shares-api/) — Share resources and folders to users with an exhaustive permission system.
- [Passbolt Tags API](https://apis.io/apis/passbolt/passbolt-tags-api/) — Get tags and add tags to resources to categorize them.
- [Passbolt Users API](https://apis.io/apis/passbolt/passbolt-users-api/) — User are entities with the ability to interact with the application.
- [Passbolt Health Check API](https://apis.io/apis/passbolt/passbolt-health-check-api/) — Gather data about the passbolt instance's health.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Passbolt Agentic Access](https://apis.io/agentic-access/passbolt/passbolt-agentic-access/)

#### Collections (27)

Postman and Open Collection request collections.

- [Passbolt Authentication (GPGAuth) Authentication (GPGAuth) Authentication (GPGAuth) API](https://apis.io/collections/passbolt/open-passbolt-authentication-gpgauth-api/)
- [Passbolt Authentication (GPGAuth) Authentication (GPGAuth) Authentication (JWT) API](https://apis.io/collections/passbolt/open-passbolt-authentication-jwt-api/)
- [Passbolt Authentication (GPGAuth) Authentication (GPGAuth) Avatars API](https://apis.io/collections/passbolt/open-passbolt-avatars-api/)
- [Passbolt Authentication (GPGAuth) Authentication (GPGAuth) Comments API](https://apis.io/collections/passbolt/open-passbolt-comments-api/)
- [Passbolt Authentication (GPGAuth) Authentication (GPGAuth) Directory Sync API](https://apis.io/collections/passbolt/open-passbolt-directory-sync-api/)
- [Passbolt Authentication (GPGAuth) Authentication (GPGAuth) Favorites API](https://apis.io/collections/passbolt/open-passbolt-favorites-api/)
- [Passbolt Authentication (GPGAuth) Authentication (GPGAuth) Folders API](https://apis.io/collections/passbolt/open-passbolt-folders-api/)
- [Passbolt Authentication (GPGAuth) Authentication (GPGAuth) GPG keys API](https://apis.io/collections/passbolt/open-passbolt-gpg-keys-api/)
- [Passbolt Authentication (GPGAuth) Authentication (GPGAuth) Groups API](https://apis.io/collections/passbolt/open-passbolt-groups-api/)
- [Passbolt Authentication (GPGAuth) Authentication (GPGAuth) Healthcheck API](https://apis.io/collections/passbolt/open-passbolt-healthcheck-api/)
- [Passbolt Authentication (GPGAuth) Authentication (GPGAuth) Metadata keys API](https://apis.io/collections/passbolt/open-passbolt-metadata-keys-api/)
- [Passbolt Authentication (GPGAuth) Authentication (GPGAuth) Metadata private keys API](https://apis.io/collections/passbolt/open-passbolt-metadata-private-keys-api/)
- [Passbolt Authentication (GPGAuth) Authentication (GPGAuth) Metadata rotate key API](https://apis.io/collections/passbolt/open-passbolt-metadata-rotate-key-api/)
- [Passbolt Authentication (GPGAuth) Authentication (GPGAuth) Metadata session key API](https://apis.io/collections/passbolt/open-passbolt-metadata-session-key-api/)
- [Passbolt Authentication (GPGAuth) Authentication (GPGAuth) Metadata types settings API](https://apis.io/collections/passbolt/open-passbolt-metadata-types-settings-api/)
- [Passbolt Authentication (GPGAuth) Authentication (GPGAuth) Metadata upgrade API](https://apis.io/collections/passbolt/open-passbolt-metadata-upgrade-api/)
- [Passbolt Authentication (GPGAuth) Authentication (GPGAuth) Move API](https://apis.io/collections/passbolt/open-passbolt-move-api/)
- [Passbolt Authentication (GPGAuth) Authentication (GPGAuth) Multi-Factor Authentication API](https://apis.io/collections/passbolt/open-passbolt-multi-factor-authentication-api/)
- [Passbolt Authentication (GPGAuth) Authentication (GPGAuth) Permissions API](https://apis.io/collections/passbolt/open-passbolt-permissions-api/)
- [Passbolt Authentication (GPGAuth) Authentication (GPGAuth) Resource types API](https://apis.io/collections/passbolt/open-passbolt-resource-types-api/)
- [Passbolt Authentication (GPGAuth) Authentication (GPGAuth) Resources API](https://apis.io/collections/passbolt/open-passbolt-resources-api/)
- [Passbolt Authentication (GPGAuth) Authentication (GPGAuth) Roles API](https://apis.io/collections/passbolt/open-passbolt-roles-api/)
- [Passbolt Authentication (GPGAuth) Authentication (GPGAuth) Secrets API](https://apis.io/collections/passbolt/open-passbolt-secrets-api/)
- [Passbolt Authentication (GPGAuth) Authentication (GPGAuth) Settings API](https://apis.io/collections/passbolt/open-passbolt-settings-api/)
- [Passbolt Authentication (GPGAuth) Authentication (GPGAuth) Shares API](https://apis.io/collections/passbolt/open-passbolt-shares-api/)
- …and 2 more published on APIs.io

#### Security (3)

Authentication, trust centre, and vulnerability disclosure.

- [Passbolt Authentication](https://apis.io/security/passbolt/passbolt-authentication/)
- [Passbolt Domain Security](https://apis.io/security/passbolt/passbolt-domain-security/)
- [Passbolt Vulnerability Disclosure](https://apis.io/security/passbolt/passbolt-vulnerability-disclosure/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Passbolt Plans Pricing](https://apis.io/plans/passbolt/passbolt-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Passbolt Rate Limits](https://apis.io/rate-limits/passbolt/passbolt-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Passbolt Finops](https://apis.io/finops/passbolt/passbolt-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.passbolt.com)
- [Documentation](https://www.passbolt.com/docs/)
- [Blog](https://www.passbolt.com/blog)

## API Evangelist rating

**Kin Score 30.9** — thin · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 57.1 |
| Contract quality | 48.4 |
| Contract governance | 0.0 |
| Operational transparency | 13.2 |
| Developer ergonomics | 23.8 |
| Access clarity | 31.6 |

**Agent readiness 17.9** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | — |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 21.6** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/passbolt/](https://apis.io/providers/passbolt/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Passbolt: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/passbolt/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
