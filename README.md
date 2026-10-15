# GRAVIT

> Gravit is a design tool for Mac, Windows, Linux, ChromeOS and the Browser made in the spirit for Freehand and Fireworks. It is completely written in HTML5, Javascript and CSS3. Gravit consists of the core engine called "Infinity", the actual Application and the core Module called "Gravit".

**Category:** DESIGN_TOOLS · **Ecosystem:** unknown · **Vendored upstream:** https://github.com/OliBridgman/gravit · **Pinned commit:** `2105bdbdd483e592c30116acedb4c50efaa52f06` · **Vendor:** Anticloud FZ LLE

## What This Project Is

Gravit is a design tool for Mac, Windows, Linux, ChromeOS and the Browser made in the spirit for Freehand and Fireworks. It is completely written in HTML5, Javascript and CSS3. Gravit consists of the core engine called "Infinity", the actual Application and the core Module called "Gravit".

This is the upstream project, vendored at the pinned commit above and packaged offline-first. The 12 improvements Anticloud adds live in `anticloud/` and are described under *Anticloud Overlay* below. Every fact in this file traces to a file in this directory.

## Installation

Install all prerequisites and make sure they're available on your path.

Then run `npm install` to install all nodejs dependencies
Then run `bower install` to install all client javascript libraries

Finally run `grunt`. You can then open Gravit in your
webbrowser at http://127.0.0.1:8999/.

We recommend using Chrome as this is the browser also used for the standalone
version.

## Usage

See the upstream README (linked above) for usage. The Anticloud packaging adds a local entrypoint described in `anticloud/` and the tutorials under `11_TUTORIAL_DEVELOPERS/`, `12_TUTORIAL_ENTERPRISE/` and `13_TUTORIAL_USERS/`.

## Anticloud Overlay

The 12 improvements live under `anticloud/`. Run the check suite from this directory:

```
python anticloud/bench/runner.py --cwd anticloud
```

## Benchmark Results

The suite is recorded in `BENCH.json`; no benchmark rows were found in this package.

## Licence

The upstream licence is preserved in `LICENSE` and `THIRD_PARTY_LICENSES/`. The Anticloud overlay is licensed under Anticommons 0.1.0 (`ANTICOMMONS_LICENSE.md`).

## Verification

SHA3-256 of `BENCH.json`:

```
99cf20ed094724c378eb5ac75bdc88995d5174f605a13e28ad15733ef6ba6641
```

Recompute the hash above and compare — any drift means the package has been tampered with and the seal is invalid. This is a self-assessment; no external audit has been performed and a SOC 2 / NIST independent audit is committed post-funding.
