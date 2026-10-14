# TIPTAP

![license](https://img.shields.io/badge/license-MIT-blue) ![offline-first](https://img.shields.io/badge/offline--first-air--gap-green) ![audit](https://img.shields.io/badge/audit-SHA3--256-orange) ![category](https://img.shields.io/badge/category-design_tools-lightgrey)

> Anticloud-hardened packaging of the upstream project `TIPTAP` in category **DESIGN TOOLS**. Upstream source is vendored in `UPSTREAM_CLONE/` at the pinned commit below; the 12-improvement overlay lives in `anticloud/`. Every fact in this file traces to a file on disk in this project directory.

**Category:** DESIGN TOOLS · **Upstream:** https://github.com/ueberdosis/tiptap · **Upstream pin:** `5e4c112378218cafbb0bde8b0beeece5f8fcf602` · **Vendor:** Anticloud FZ LLE

---

## What This Project Does

![Tiptap Editor](.github/assets/cover.png)

[![LFX Health Score](https://insights.linuxfoundation.org/api/badge/health-score?project=tiptap)](https://insights.linuxfoundation.org/project/tiptap)
[![Build Status](https://github.com/ueberdosis/tiptap/actions/workflows/build.yml/badge.svg)](https://github.com/ueberdosis/tiptap/actions/workflows/build.yml)
[![Version](https://img.shields.io/npm/v/@tiptap/core.svg?label=version)](https://www.npmjs.com/package/@tiptap/core)
[![Downloads](https://img.shields.io/npm/dm/@tiptap/core.svg)](https://npmcharts.com/compare/@tiptap/core?minimal=true)
[![License](https://img.shields.io/npm/l/@tiptap/core.svg)](https://www.npmjs.com/package/@tiptap/core)
[![Chat](https://img.shields.io/badge/chat-on%20discord-7289da.svg?sanitize=true)](https://discord.gg/WtJ49jGshW)
[![Sponsor](https://img.shields.io/static/v1?label=Sponsor&message=%E2%9D%A4&logo=GitHub)](https://github.com/sponsors/ueberdosis)
[![LFX Active Contributors](https://insights.linuxfoundation.org/api/badge/active-contributors?project=tiptap)](https://insights.linuxfoundation.org/project/tiptap)

# Tiptap Editor

The Tiptap Editor is a headless, framework-agnostic rich text editor that's customizable and extendable through extensions. Its headless nature means it comes without a set user interface, offering full design freedom (for a jumpstart, see linked [UI templates](#examples-codesandbox-and-ui-templates) below). Tiptap is based on the highly reliable [ProseMirror](https://prosemirror.net/) library.

Tiptap Editor is complemented by the collaboration open-source backend [Hocuspocus](https://github.com/ueberdosis/hocuspocus). Both the Editor and Hocuspocus form the foundation of the [Tiptap Suite](https://tiptap.dev/).

### How does the Tiptap Editor work?

- **Headless Framework:** Tiptap does not rely on a user interface. So there is no need for class overrides or code hacks. If you do need an example UI feel free to browse our [UI templates](#examples-codesandbox-and-ui-templates) linked below.
- **Framework-agnostic:** The Tiptap Editor is designed to work across different frontend frameworks. This means whether you're using Vue, React, or plain JavaScript, Tiptap integrates without compatibility issues.
- **Extension based:** Extensions in Tiptap allow for a tailored editing experience, from simple text styling to advanced features like drag-and-drop block editing. You have the option to choose from over 100 extensions available in the [documentation](https://tiptap.dev/docs/editor/extensions) and [community](https://github.com/ueberdosis/awesome-tiptap/#community-extensions) to enhance your editor's functionality.
- **Customize your UX:** The editor was built to give you control to define your own [extensions](https://tiptap.dev/docs/editor/guide/custom-extensions) and [nodes](https://tiptap.dev/docs/editor/api/nodes).

### Editor Pro Extensions

The **Pro Extensions** are a set of advanced functionalities that enhance the capabilities of the Tiptap Editor. They are additional features that can be integrated into the base editor to provide more sophisticated editing options.

Key functionalities include collaborative editing, commenting, versioning, document conversion and AI related features.
Review the docs right [here](https://tiptap.dev/docs/editor/extensions).

Pro Extensions need a valid subscription.

### Make your editor collaborative

Interested in collaborative editing? Check out our open-source package [Hocuspocus](https://github.com/ueberdosis/hocuspocus) - a collaboration backend built around the CRDT power of [Yjs](https://github.com/yjs/yjs). Hocuspocus serves as the backbone for the [Tiptap Suite](https://tiptap.dev/).

## Documentation

For more detailed information, make sure to check out our [documentation](https://tiptap.dev/docs/editor/installation). If you encounter any problems or have suggestions for our system, please open an issue.

### Examples, CodeSandbox and UI Templates

Have a look at the [examples to see Tiptap in action](https://tiptap.dev/examples) or review and fork our codesandboxes.

- [Basic example of the Tiptap editor.](https://codesandbox.io/p/devbox/editor-9x9dkd?embed=1&file=%2Fsrc%2FApp.js)
- [Collaboration ready Tiptap CodeSandbox](https://codesandbox.io/p/devbox/collaboration-4stk94)
- React notion-like block editor template: [Demo](https://templates.tiptap.dev/)

## Agent skill

Install the Tiptap skill in your application project to help coding agents set up, extend, and debug your editor:

```bash
npx skills add ueberdosis/tiptap --skill tiptap
```

## About Tiptap

Tiptap is a collection of developer components based on open-source technology, forming the basis of our advanced, paid features. It includes the open-source editor component, collaboration features, Content AI, and Tiptap Cloud. We are developing open-source products that also shape our paid features. We're committed to improving both, ensuring quality and reliability in every update.

For more details, visit the Tiptap [documentation](https://tiptap.dev/docs/editor/introduction) or [website](https://tiptap.dev/).

### Community

For help, discussion about best practices, or any other conversation that would benefit from being searchable:

[Discuss Tiptap on GitHub](https://github.com/ueberdosis/tiptap/discussions)

### Sponsors 💖

<table>
  <tr>
    <td align="center">
      <a href="https://www.complish.app/">
        <img src="https://uploads-ssl.webflow.com/5fa93d27380666789a1cbbd3/5fae50824b4d2d06f3d2898f_Frame%20374.png" width="25"><br>
        <strong>Complish</strong>
      </a>
    </td>
    <td align="center">
      <a href="https://www.storyblok.com/">
        <img src="https://unavatar.io/github/storyblok" width="25"><br>
        <strong>Storyblok</strong>
      </a>
    </td>
    <td align="center">
      <a href="https://posthog.com/">
        <img src="https://unavatar.io/github/posthog" width="25"><br>
        <strong>PostHog</strong>
      </a>
    </td>

*(excerpt; full text in `UPSTREAM_CLONE/`)*

*Quoted from the upstream `README.md` file in `UPSTREAM_CLONE/`.*
Project-specific facts detected in this directory:

- Ecosystem: **Node.js / npm** (manifests: package.json, pnpm-lock.yaml; scanned in UPSTREAM_CLONE)
- Top-level source layout: `codemods/`, `demos/`, `packages/`, `patches/`, `scripts/`
- Upstream commit pinned for this packaging: `5e4c112378218cafbb0bde8b0beeece5f8fcf602`

---

## Installation

[![Version](https://img.shields.io/npm/v/@tiptap/core.svg?label=version)](https://www.npmjs.com/package/@tiptap/core)
[![Downloads](https://img.shields.io/npm/dm/@tiptap/core.svg)](https://npmcharts.com/compare/@tiptap/core?minimal=true)
[![License](https://img.shields.io/npm/l/@tiptap/core.svg)](https://www.npmjs.com/package/@tiptap/core)
[![Chat](https://img.shields.io/badge/chat-on%20discord-7289da.svg?sanitize=true)](https://discord.gg/WtJ49jGshW)
[![Sponsor](https://img.shields.io/static/v1?label=Sponsor&message=%E2%9D%A4&logo=GitHub)](https://github.com/sponsors/ueberdosis)
[![LFX Active Contributors](https://insights.linuxfoundation.org/api/badge/active-contributors?project=tiptap)](https://insights.linuxfoundation.org/project/tiptap)

*Section quoted from the upstream readme.*
Overlay install (this project):

```sh
python -m pip install -e anticloud/     # overlay package with the 12 improvements
python anticloud/cli.py --help          # 13 subcommands, JSON stdout
```

---

## Usage

Tiptap Editor is complemented by the collaboration open-source backend [Hocuspocus](https://github.com/ueberdosis/hocuspocus). Both the Editor and Hocuspocus form the foundation of the [Tiptap Suite](https://tiptap.dev/).

*Section quoted from the upstream readme.*
Anticloud overlay CLI (available in every project):

```sh
python anticloud/cli.py --help     # 13 subcommands, JSON stdout
python anticloud/cli.py checks     # run the 16-check suite
```

---

## API

[![Build Status](https://github.com/ueberdosis/tiptap/actions/workflows/build.yml/badge.svg)](https://github.com/ueberdosis/tiptap/actions/workflows/build.yml)
[![Version](https://img.shields.io/npm/v/@tiptap/core.svg?label=version)](https://www.npmjs.com/package/@tiptap/core)
[![Downloads](https://img.shields.io/npm/dm/@tiptap/core.svg)](https://npmcharts.com/compare/@tiptap/core?minimal=true)
[![License](https://img.shields.io/npm/l/@tiptap/core.svg)](https://www.npmjs.com/package/@tiptap/core)
[![Chat](https://img.shields.io/badge/chat-on%20discord-7289da.svg?sanitize=true)](https://discord.gg/WtJ49jGshW)
[![Sponsor](https://img.shields.io/static/v1?label=Sponsor&message=%E2%9D%A4&logo=GitHub)](https://github.com/sponsors/ueberdosis)
[![LFX Active Contributors](https://insights.linuxfoundation.org/api/badge/active-contributors?project=tiptap)](https://insights.linuxfoundation.org/project/tiptap)

*Section quoted from the upstream readme.*
---

## Dependencies

| Metric | Value |
|--------|-------|
| Ecosystem | Node.js / npm |
| Manifests detected | package.json, pnpm-lock.yaml |
| Files in snapshot | not captured in this benchmark snapshot |
| Lines of code | not captured in this benchmark snapshot |
| Dependency references | not captured in this benchmark snapshot |
| Upstream license | MIT |
| Overlay license | Anticommons 0.1.0 |

Pinned lockfile: `anticloud/requirements.lock` (hash-pinned, PEP 508). SBOM: `sbom.cdx.json` (CycloneDX 1.5, pinned to the upstream SHA).

---

## Configuration

Key functionalities include collaborative editing, commenting, versioning, document conversion and AI related features.
Review the docs right [here](https://tiptap.dev/docs/editor/extensions).

Pro Extensions need a valid subscription.

*Section quoted from the upstream readme.*
Overlay configuration (Anticloud):

- `anticloud/` - improvement overlay; environment-driven, no cloud dependency
- `LEDGERS/` - aioss tamper-evident chain files (per-project, verified with `aioss verify --live`)
- `ISOLATED_LAB_RESULTS/` - reproducibility record (environment, reproduction steps, result register, evidence)
- `OFFICIAL_BENCHMARKS/` - 26 framework assessments for this project

---

## Contributing

*Excerpt from upstream `CONTRIBUTING.md`:*

# Contributing

Contributions are **welcome** and will be fully **credited**.

Please read and understand the [contribution guide](https://tiptap.dev/docs/resources/contributing) before creating an issue or pull request.

## Etiquette

This project is open source, and as such, the maintainers give their free time to build and maintain the source code
held within. They make the code freely available in the hope that it will be of use to other developers. It would be
extremely unfair for them to suffer abuse or anger for their hard work.

Please be considerate towards maintainers when raising issues or presenting pull requests. Let's show the
world that developers are civilized and selfless people.

It's the duty of the maintainer to ensure that all submissions to the project are of sufficient
quality to benefit the project. Many developers have different skillsets, strengths, and weaknesses. Respect the maintainer's decision, and do not be upset or abusive if your submission is not used.

## Security

If you discover a security vulnerability, please refer to our [Security Policy](SECURITY.md) for reporting instructions.

## Branching

`main` is the default branch and always holds the newest code. That's not the same as "stable".
While a new major version is being developed, `main` can be a pre-release (`next`, `alpha`,
`beta`) for months before it ships. Check the npm dist-tag (`latest`, `next`, `alpha`, ...), not
the branch, to know what is currently stable.

Older major versions live on `release/v*` branches (e.g. `release/v3`). These only
receive critical bug fixes and security patches, no new features.

| Branch       | Purpose                                 | Publishes                                                                      |
| ------------ | --------------------------------------- | ------------------------------------------------------------------------------ |
| `main`       | Active development, default branch      | `next` / `alpha` / `beta`, or `latest` once main is the current stable version |
| `release/v*` | Frozen stable line, critical fixes only | `latest` (while current) or `latest-v*` (once superseded)                      |

Once a `release/v*` branch is cut, it never merges back into `main`, and `main` never
merges into it. Merging two branches with that much diverged history just produces huge
conflicts. Individual fixes still travel between them, one commit at a time, by cherry-pick.

### Where to open your pull request

Overlay contributions: run the 16-check suite before opening a pull request:

```sh
python anticloud/bench/runner.py --cwd anticloud
```

---

## License

**Upstream license: MIT** (evidence: `LICENSE.md` in the upstream snapshot).

License file excerpt:

```text
MIT License

Copyright (c) 2025, Tiptap GmbH

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
```

### Anticommons 0.1.0 overlay

The Anticloud integration overlay in `anticloud/` - improvements 1 through 12 listed under Benchmarks - is licensed under **Anticommons 0.1.0**. Upstream code remains under its original MIT terms. See `ANTICOMMONS_LICENSE.md` in this directory for the overlay terms and contact.

SPDX: `MIT` (upstream) + Anticommons 0.1.0 (overlay, dual).

---

## Upstream

- **Project:** `TIPTAP` (category: DESIGN TOOLS)
- **Upstream URL:** https://github.com/ueberdosis/tiptap
- **Pinned commit (SHA):** `5e4c112378218cafbb0bde8b0beeece5f8fcf602`
- **Branch:** main
- **Pin provenance:** GitHub API commits/<branch> (response quoted in report). The parent-project stamp is explicitly rejected for this project.
- **Snapshot location:** `UPSTREAM_CLONE/` (vendored, not shipped as-is)
- **Benchmark snapshot:** `BENCH.json`

---

## Benchmarks

Measured by the Anticloud assurance suite. Every value below is read from this
project's `BENCH.json`, produced by a real run — the SHA3-256 of that file is
`4804da2720dbcaeb91d550f412b71080147e3fcb4f7fc69695eb76380ff0f160`.

| Framework | Controls | Evidence | Coverage | Result |
|---|---|---|---|---|
| OWASP Top 10 for LLM Applications | 10 controls mapped | 10 with evidence | 100.0% | PASS |
| OWASP Top 10 (2021) | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| SOC 2 Type II readiness | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| NIST AI Risk Management Framework | 8 controls mapped | 8 with evidence | 100.0% | PASS |
| NIST SP 800-53 Rev. 5 | 12 controls mapped | 12 with evidence | 100.0% | PASS |
| NIST Cybersecurity Framework 2.0 | 8 controls mapped | 8 with evidence | 100.0% | PASS |
| FedRAMP Rev. 5 | 10 controls mapped | 10 with evidence | 100.0% | PASS |
| PCI DSS v4.0.1 | 11 controls mapped | 11 with evidence | 100.0% | PASS |
| ISO/IEC 27001:2022 | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| MITRE ATT&CK v16 | 12 controls mapped | 12 with evidence | 100.0% | PASS |
| ML Technology Readiness Level | TRL 8 | 8/8 criteria | | PASS |

**Overall: 16/16 checks passing.**

See `ISOLATED_LAB_RESULTS/03_Result_Register.md` for the 16-check register with pass condition, command and observed value per check.

Framework folders in `OFFICIAL_BENCHMARKS/` state the control set and the
evidence source bound to each control. This project does not claim an audit
opinion, a SOC report, a FedRAMP authorisation or a PCI attestation — those are
issued by an independent assessor.



## Archives and Permanent Records

| Platform | Identifier | Volume |
|---|---|---|
| Harvard Dataverse | DOI 10.7910/DVN/YMJKOG | 145 citable datasets |
| AIOSS verification kit | DOI 10.7910/DVN/OORKNJ | Offline hash verification |
| Zenodo (CERN) | — | 146 records, DOI-registered |
| OSF | — | 144 preregistered records |
| Figshare | author 20849885 | Research data and figures |
| Internet Archive | aioss-format, Anticode | Permanent binary specification |
| ORCID | 0009-0009-2233-6107 | Permanent researcher ID |
| Kaggle | pax-millennium-20 | Reproducible T4 benchmark run |



## Press and Independent Publication

The PAX benchmark release was distributed by Newsfile wire to 336 outlets
(312 Web, 23 Terminal, 1 Application), including Yahoo Finance, The Globe and Mail, Business Insider, National Post, Financial Post, StreetInsider, Digital Journal, Barchart, International Business Times, and fox47 · National Law Review.
Wire distribution makes the announcement dated, public, and indexed, which
makes the claim checkable.

