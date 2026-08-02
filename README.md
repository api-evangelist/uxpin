# UXPin

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
