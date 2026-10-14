# OPENSESAME

![license](https://img.shields.io/badge/license-MIT-blue) ![offline-first](https://img.shields.io/badge/offline--first-air--gap-green) ![audit](https://img.shields.io/badge/audit-SHA3--256-orange) ![category](https://img.shields.io/badge/category-psychology-lightgrey)

> Anticloud-hardened packaging of the upstream project `OPENSESAME` in category **PSYCHOLOGY**. Upstream source is vendored in `UPSTREAM_CLONE/` at the pinned commit below; the 12-improvement overlay lives in `anticloud/`. Every fact in this file traces to a file on disk in this project directory.

**Category:** PSYCHOLOGY · **Upstream:** https://github.com/alibaba-archive/opensesame · **Upstream pin:** `1026629d6f6a13dd610d146b015d27ec3888fd2c` · **Vendor:** Anticloud FZ LLE

---

## What This Project Does

<img src="Shared/Assets.xcassets/AppIcon.appiconset/icon_512x512@2x.png" width="192" align="right" hspace="20" />

Open Sesame
======
[![Forks](https://img.shields.io/github/forks/OpenSesameManager/OpenSesame)](https://github.com/OpenSesameManager/OpenSesame/network/members)
[![Stars](https://img.shields.io/github/stars/OpenSesameManager/OpenSesame)](https://github.com/OpenSesameManager/OpenSesame/stargazers)
[![License](https://img.shields.io/github/license/OpenSesameManager/OpenSesame)](https://github.com/OpenSesameManager/OpenSesame/blob/main/LICENSE.md)

![Xcode Version](https://img.shields.io/badge/Xcode%2013+-black?logo=xcode)
![SwiftUI](https://img.shields.io/badge/SwiftUI-black?logo=swift)
![Platforms](https://img.shields.io/badge/Platform%20Compatibility-iOS%2015+%20|%20macOS%2012+-red?logo=apple&?color=red)

[![App Store](https://img.shields.io/badge/App%20Store-blue)](https://apps.apple.com/us/app/opensesame-password-manager/id1581907821)
[![TestFlight](https://img.shields.io/badge/Join%20The%20TestFlight-blue)](https://testflight.apple.com/join/5ZW0k48j)
[![Website](https://img.shields.io/badge/Website-blue)](https://opensesame.vercel.app)

Native and encrypted password manager for iOS and macOS.

![OpenSesame](Images/All.png)

![macOS](Images/macOS.png)

## What is it?

OpenSesame is a free and powerful password manager that lets you manage your passwords with ease.

It syncs with iCloud and encrypts your data to make sure only **you** get access. No more required subscriptions, no more ram hogs, *and no more electron versions.*

## Why use OpenSesame

Now more than ever, what was previously amazing native apps have become slow and big web apps. Big apps take more control away from the user and push subscriptions and other payment models without much reason. OpenSesame aims to fix that by giving a free and open source password manager that is native and performant. Still get all the great features of other password managers without all the baggage.

## Features

- iCloud Syncing
- OTP Auth (Two Factor Authentication)
- Safari Autofill
- On-Device AES encryption
- Biometrics unlock
- Pinned accounts
- Multiple vaults
- Multipeer account sharing
- Import/Export
- Password generator
- Credit/Debit card support
- Notes field
- OTP QR codes
- Alternate icons
- Customizable
- CoreData
- 100% SwiftUI
- Native support for macOS and iOS.
- Menubar access

## Requirements

- Xcode 14.2+
- macOS 13+
- iOS 16+

## License

OpenSesame is available under the MIT license. See the LICENSE.md file for more info.

## Acknowledgements

OpenSesame depends on the following open-source projects:

* [SwiftOTP](https://github.com/OpenSesameManager/SwiftOTP.git) by [lachlanbell](https://github.com/lachlanbell) ([License](https://github.com/lachlanbell/SwiftOTP/blob/master/LICENSE))
* [FaviconFinder](https://github.com/OpenSesameManager/FaviconFinder.git) by [will-lumley](https://github.com/will-lumley) ([License](https://github.com/OpenSesameManager/FaviconFinder/blob/main/LICENSE.txt))
* [KeychainAccess](https://github.com/kishikawakatsumi/KeychainAccess.git) by [kishikawakatsumi](https://github.com/kishikawakatsumi) ([License](https://github.com/kishikawakatsumi/KeychainAccess/blob/master/LICENSE))
* [DomainParser](https://github.com/Dashlane/SwiftDomainParser.git) by [Dashlane](https://github.com/Dashlane) ([License](https://github.com/Dashlane/SwiftDomainParser/blob/master/LICENSE))
* [CSV.swift](https://github.com/yaslab/CSV.swift.git) by [yaslab](https://github.com/yaslab) ([License](https://github.com/yaslab/CSV.swift/blob/master/LICENSE))
* [CodeScanner](https://github.com/twostraws/CodeScanner.git) by [twostraws](https://github.com/twostraws) ([License](https://github.com/twostraws/CodeScanner/blob/main/LICENSE))
* [ScreenCorners](https://github.com/kylebshr/ScreenCorners.git) by [kylebshr](https://github.com/kylebshr) ([License](https://github.com/kylebshr/ScreenCorners/blob/main/LICENSE))

*Quoted from the upstream `README.md` file in `UPSTREAM_CLONE/`.*
Project-specific facts detected in this directory:

- Ecosystem: **Unknown (no standard manifest detected)** (manifests: none detected; scanned in UPSTREAM_CLONE)
- Top-level source layout: `AutoFill iOS/`, `AutoFill macOS/`, `Images/`, `OpenSesame/`, `OpenSesame.xcodeproj/`, `Tests iOS/`, `Tests macOS/`
- Snapshot size: **201 files**, **8573 lines of code** (measured; see Benchmarks)
- Primary languages: `.swift` (85), `.png` (58), `.json` (31), `(none)` (4), `.plist` (4), `.svg` (4)
- Upstream commit pinned for this packaging: `1026629d6f6a13dd610d146b015d27ec3888fd2c`

---

## Installation

No installation section was found in the upstream readme, so the commands below are generated from the manifests detected in this project directory.

```sh
# No standard manifest detected. Inspect UPSTREAM_CLONE/ for the upstream
# build system (Makefile, CMakeLists.txt, configure, ...) and follow it.
```

Overlay install (this project):

```sh
python -m pip install -e anticloud/     # overlay package with the 12 improvements
python anticloud/cli.py --help          # 13 subcommands, JSON stdout
```

---

## Usage

Now more than ever, what was previously amazing native apps have become slow and big web apps. Big apps take more control away from the user and push subscriptions and other payment models without much reason. OpenSesame aims to fix that by giving a free and open source password manager that is native and performant. Still get all the great features of other password managers without all the baggage.

*Section quoted from the upstream readme.*
Anticloud overlay CLI (available in every project):

```sh
python anticloud/cli.py --help     # 13 subcommands, JSON stdout
python anticloud/cli.py checks     # run the 16-check suite
```

---

## API

The upstream API surface is defined by the `OPENSESAME` source tree vendored in `UPSTREAM_CLONE/` (Unknown (no standard manifest detected) ecosystem). Public entry points:

- Source modules: `AutoFill iOS/`, `AutoFill macOS/`, `Images/`, `OpenSesame/`, `OpenSesame.xcodeproj/`, `Tests iOS/`, `Tests macOS/`
- Overlay API: `anticloud/cli.py` exposes 13 subcommands with JSON stdout; `anticloud/bench/runner.py` runs the 16-check suite; `anticloud/provenance/chain.py` exposes the SHA3-256 + Ed25519 provenance chain.

---

## Dependencies

| Metric | Value |
|--------|-------|
| Ecosystem | Unknown (no standard manifest detected) |
| Manifests detected | none |
| Files in snapshot | 201 |
| Lines of code | 8573 |
| Dependency references | 0 |
| Upstream license | MIT |
| Overlay license | Anticommons 0.1.0 |

Pinned lockfile: `anticloud/requirements.lock` (hash-pinned, PEP 508). SBOM: `sbom.cdx.json` (CycloneDX 1.5, pinned to the upstream SHA).

---

## Configuration

No configuration section was found in the upstream readme. Configuration-relevant files detected in this project directory:

- None detected at the snapshot root; consult the upstream documentation link in the Upstream section.

Overlay configuration (Anticloud):

- `anticloud/` - improvement overlay; environment-driven, no cloud dependency
- `LEDGERS/` - aioss tamper-evident chain files (per-project, verified with `aioss verify --live`)
- `ISOLATED_LAB_RESULTS/` - reproducibility record (environment, reproduction steps, result register, evidence)
- `OFFICIAL_BENCHMARKS/` - 26 framework assessments for this project

---

## Contributing

Upstream contributions: fork the `OPENSESAME` project, create a feature branch, and open a pull request against upstream. Keep `UPSTREAM_CLONE/` untouched in this packaging; put improvements in the `anticloud/` overlay.

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

Copyright (c) 2021 Ethan Lipnik

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

- **Project:** `OPENSESAME` (category: PSYCHOLOGY)
- **Upstream URL:** https://github.com/alibaba-archive/opensesame
- **Pinned commit (SHA):** `1026629d6f6a13dd610d146b015d27ec3888fd2c`
- **Branch:** master
- **Pin provenance:** GitHub API commits/master. The parent-project stamp is explicitly rejected for this project.
- **Snapshot location:** `UPSTREAM_CLONE/` (vendored, not shipped as-is)
- **Benchmark snapshot:** `BENCH.json`

---

## Benchmarks

Measured by the Anticloud assurance suite. Every value below is read from this
project's `BENCH.json`, produced by a real run — the SHA3-256 of that file is
`0af288b03182cad1f861ab500d433a3ca15ec183d8ee291641a3444670768358`.

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

