# Wormhole

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

Wormhole is a decentralized cross-chain messaging and interoperability protocol connecting 45+ blockchain networks including Solana, Ethereum, Arbitrum, Base, Avalanche, BNB Chain, Aptos, Sui, and more. It provides the infrastructure for moving assets and data across chains securely via a Guardian Network of validators who sign Verifiable Action Approvals (VAAs).

## APIs

This repository catalogs the following Wormhole public APIs and developer tools:

- **Wormholescan API (Mainnet)** — `https://api.wormholescan.io/api/v1` — REST API for VAA status, token transfers, NTT metadata, cross-chain operations, and Guardian Network data
- **Wormholescan API (Testnet)** — `https://api.testnet.wormholescan.io/api/v1` — Testnet mirror for development
- **TypeScript SDK** — `@wormhole-foundation/sdk` — Unified SDK for cross-chain app development
- **Connect Widget** — `@wormhole-foundation/wormhole-connect` — Embeddable React bridge widget
- **Wormhole CLI** — Command-line tooling for protocol operations

## Key Capabilities

- Query VAA (Verifiable Action Approval) status and details
- Fetch native and wrapped token transfer operations with filtering
- Retrieve NTT token metadata across 45+ chains
- Access Guardian Network configuration and status
- Build cross-chain applications with TypeScript SDK
- Embed bridge UI with the Connect widget

## Resources

- Developer Documentation: https://wormhole.com/docs/
- Wormholescan Explorer: https://wormholescan.io/
- GitHub Organization: https://github.com/wormhole-foundation
- Community Hub: https://wormhole.com/community/hub
- Forum: https://forum.wormhole.com/
- Bug Bounty: https://immunefi.com/bug-bounty/wormhole/
- Contact: https://wormhole.com/contact
- Institutions: https://wormhole.com/institutions
