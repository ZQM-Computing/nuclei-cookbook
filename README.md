# Nuclei Cookbook

<!-- ZQM-START -->
<!-- markdownlint-disable MD033 -->
<p align="center">
  <strong>ZQM Computing — Geospatial Engineering & Scientific Computing</strong><br>
  <a href="https://github.com/ZQM-Computing">ZQM Computing</a>
</p>
<!-- markdownlint-enable MD033 -->
<!-- ZQM-END -->

![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)

A **Nuclei cookbook** for bounded, authorized template scanning. Patterns are drawn from the ZQM fleet's Nuclei work, which is bounded-active against authorized targets only — the fleet's target is zqmlabs.com. Never point these patterns at a target you do not own or are not authorized to test. It is intended for Security practitioners who run template-based checks against their own assets. Validate each pattern against your own data, software versions, and operating environment before adopting it.

## Repository role and status

**Status:** Active, public — seeding. Pattern passes land in follow-up work from fleet-verified setups; the tables below list what is planned, not what is already written.

**What this repository is:** Nuclei patterns — see the table below.

**What it contributes:** Part of the ZQM Computing geospatial portfolio. Intended to provide geospatial data feeds (POI, weather, satellite imagery, geocoding) for the ZQM game platform. The umbrella index for the series is [geospatial-cookbooks](https://github.com/ZQM-Computing/geospatial-cookbooks).

**Standing:** This repository is maintained independently. Automated checks cover only the paths and environments configured in its workflows; they do not establish production readiness or operational certification.

## Who this is for

Security practitioners who run template-based checks against their own assets.

## Prerequisites

- Nuclei in the fleet tooling
- An authorized target (the fleet's is zqmlabs.com)
- Bash or PowerShell

## Patterns (planned)

| # | Example | What it will demonstrate |
|---|---------|--------------------------|
| 01 | `01-first-scan` | A first bounded scan against an authorized target |
| 02 | `02-templates` | Choosing and curating template sets |
| 03 | `03-output` | Reading findings and triaging false positives |

## Repository layout

```text
nuclei-cookbook/
├── examples/          # pattern passes, landing in follow-up work
├── README.md
└── LICENSE
```

## Roadmap

- First pattern pass: the first two table rows
- Second pass: the remaining rows, from fleet-verified setups

## Contributing

A contributing guide lands with the first pattern pass. Report security issues to <zqmcomputing@gmail.com> — please do not open a public issue for those.

## More from this series

- [spiderfoot-cookbook](https://github.com/ZQM-Computing/spiderfoot-cookbook) — Passive OSINT automation as a service
- [amass-cookbook](https://github.com/ZQM-Computing/amass-cookbook) — Passive subdomain enumeration and graph output
- [shodan-cookbook](https://github.com/ZQM-Computing/shodan-cookbook) — Internet-device search from the command line
