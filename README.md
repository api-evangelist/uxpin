# UXPin

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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

UXPin is an AI-powered, code-based design and prototyping platform where designers work with real production React components instead of vector approximations. Its Merge technology syncs a team's design system from Git or Storybook onto the design canvas, its Forge AI assistant generates and iterates UI constrained to that design system, and export is production-ready JSX referencing components already in the codebase.

UXPin publishes no public REST API — its developer surface is the open-source Merge toolchain, centered on the [`@uxpin/merge-cli`](https://www.npmjs.com/package/@uxpin/merge-cli) npm package (repo: [UXPin/uxpin-merge-tools](https://github.com/UXPin/uxpin-merge-tools)), which analyzes a design-system repository and pushes components to UXPin. An MCP integration for AI coding tools is on the provider's published roadmap.

Backed by: a16z

## Artifacts

- `llms/uxpin-llms.txt` — provider-published llms.txt (harvested verbatim from https://www.uxpin.com/llms.txt)
- `packages/uxpin-packages.yml` — first-party npm packages under the @uxpin scope
- `cli/uxpin-cli.yml` — UXPin Merge CLI command surface
- `components/uxpin-components.yml` — Merge code-backed component libraries
- `well-known/uxpin-well-known.yml` — /.well-known/ probe results
- `conformance/uxpin-conformance.yml` — published compliance claims (PCI DSS A-EP 3.2, SOC 2 infra, GDPR, SAML 2.0)
- `lifecycle/uxpin-lifecycle.yml` — status page, changelog, versioning posture
- `security/uxpin-domain-security.yml` — TLS/HSTS/DNS probe results
- `security/uxpin-trust-center.yml` — security page certifications
