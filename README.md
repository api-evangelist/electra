# Electra

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

Electra (legal name **Electrasteel, Inc.**) is a Boulder, Colorado clean-industrial company founded in
2020 that is reinventing ironmaking. Instead of smelting iron ore with fossil fuels in a blast furnace,
Electra uses an electrochemical process — an acidic leach plus electrowinning driven by renewable
electricity — to dissolve a broad range of iron ores, including low-grade and previously
uncommercialized ores, and plate out 99% pure iron at roughly 60°C while recovering high-value
co-minerals and emitting oxygen. Electra has raised over $200M from Rio Tinto, BHP Ventures, POSCO,
Breakthrough Energy Ventures, Amazon's Climate Pledge Fund, Capricorn and Lowercarbon Capital, runs a
pilot plant in Boulder, and is building a demonstration plant in Colorado.

## API surface

**Electra publishes no public API.** It is an industrial manufacturer, not a software provider. Its
entire public web surface is a nine-page marketing site (verified against its own sitemap): homepage,
technology, team, careers, newsroom, privacy policy, terms & conditions, and purchase-order terms.
There is no developer portal, documentation, API reference, machine-readable specification, GraphQL
endpoint, MCP server, or agent card, and no `api.`/`docs.`/`developer.` subdomain resolves. The probes
run and their HTTP statuses are recorded in `apis.yml` under `x-contract-discovery` and in
`well-known/electra-well-known.yml`. This is a valid, expected result — not a gap.

Not to be confused with the unrelated **Electra Systems** (energy/IoT device API), **Electra
Information Systems** (financial reconciliation), **Electra Coin** (ECA), or Google's **ELECTRA** NLP
model.

## Artifacts

| Artifact | File | Method |
|---|---|---|
| Domain security | `security/electra-domain-security.yml` | probed |
| Well-known probe evidence | `well-known/electra-well-known.yml` | probed (all paths 404) |

## Links

- Website — https://www.electra.earth/
- Technology — https://www.electra.earth/our-technology/
- Team — https://www.electra.earth/our-team/
- Careers — https://www.electra.earth/careers/
- Newsroom — https://www.electra.earth/newsroom/
- LinkedIn — https://www.linkedin.com/company/electra-earth
- Secondary-market listing — https://forgeglobal.com/electra_stock/
