# Tinyproxy

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

Tinyproxy is a lightweight, open-source HTTP/HTTPS proxy daemon designed for POSIX operating systems. It is ideal for use cases in embedded deployments, small networks, and environments where a full-featured HTTP proxy is required with minimal system resource usage. Configuration is file-based with an internal statistics monitoring page.

## APIs

### Tinyproxy

Tinyproxy is a lightweight HTTP/HTTPS proxy daemon for POSIX operating systems with minimal system resource requirements. Provides forward proxying, HTTPS CONNECT tunneling, domain filtering, access control, upstream proxy chaining, transparent proxying, and an internal statistics monitoring page.

- **Documentation:** [https://tinyproxy.github.io/](https://tinyproxy.github.io/)
- **GitHub:** [https://github.com/tinyproxy/tinyproxy](https://github.com/tinyproxy/tinyproxy)

## Features

- HTTP and HTTPS proxy support
- CONNECT tunneling for HTTPS
- Domain and URL filtering
- Access control lists
- Upstream proxy chaining
- Transparent proxy mode
- Internal statistics monitoring page
- Privacy header filtering
- Logging with configurable verbosity
- Small memory footprint (~2MB with glibc)

## Use Cases

- Embedded systems proxy
- Small network HTTP proxy
- Content filtering gateway
- Development and testing proxy
- Container sidecar proxy
- IoT device internet access control

## Artifacts

| Type | File |
|---|---|
| JSON Schema | [tinyproxy-config-schema.json](json-schema/tinyproxy-config-schema.json) |
| JSON Structure | [tinyproxy-config-structure.json](json-structure/tinyproxy-config-structure.json) |
| JSON-LD Context | [tinyproxy-context.jsonld](json-ld/tinyproxy-context.jsonld) |
| Vocabulary | [tinyproxy-vocabulary.yml](vocabulary/tinyproxy-vocabulary.yml) |

## Examples

- [Configuration Example](examples/tinyproxy-config-example.json)

## Solutions

- Network access control
- Internet traffic filtering
- Embedded proxy deployments
- Development proxy environments

## Links

- **Website:** [https://tinyproxy.github.io/](https://tinyproxy.github.io/)
- **Documentation:** [https://tinyproxy.github.io/](https://tinyproxy.github.io/)
- **GitHub Organization:** [https://github.com/tinyproxy](https://github.com/tinyproxy)
