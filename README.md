# iLEAP Protocol Technical Specifications

<img width="200" height="400" alt="iLEAP logo" align="right" src="https://github.com/user-attachments/assets/e3d0e5ad-8230-41e0-88bf-6a2f94f0a761" />

This repository contains the Technical Specifications for the [iLEAP Protocol](#ileap-protocol).

The [iLEAP initiative](https://ileap.global) is sponsored by [SINE Foundation](https://sine.foundation) and [Smart Freight Centre](https://smartfreightcentre.org/en/).

## iLEAP Protocol

The iLEAP Protocol is a data exchange protocol for logistics emissions based on and aligned with the
methodological foundations laid in the [GLEC Framework v3.1](https://smart-freight-centre-media.s3.amazonaws.com/documents/GLEC_FRAMEWORK_v3.1_March_2025_1-3.pdf) and [ISO14083:2023](https://www.iso.org/standard/78864.html).

The iLEAP Protocol consists of
- a data model; and
- an HTTP REST API.

All specifications can be found in the [index.bs](specs/index.bs) file in this repository. The rendered version of the specifications can be found at [https://specs.ileap.global/](https://specs.ileap.global/).

Details and guidance on how to implement the iLEAP can be found in the [iLEAP Community Guide](https://sinefoundation.notion.site/iLEAP-Community-Guide-d036010d2c7547d99204ea87d79c060f).

## Demo Implementation

SINE Foundation provides an open-source demo implementation of the iLEAP protocol, which can be found in [`sine-fdn/impact-protocols`](https://github.com/sine-fdn/impact-protocols).

The demo implementation is written in Rust and includes:
- the PACT data model, conforming to [the PACT v2.2.0 Technical Specifications](https://wbcsd.github.io/tr/2024/data-exchange-protocol-20240410/);
- the iLEAP data model, conforming to the iLEAP v1.0.0 Technical Specifications; and
- a demo API, conforming to the iLEAP v1.0.0 Technical Specifications.

The demo API can be accessed at [https://api.ileap.sine.dev](https://api.ileap.sine.dev).

## SQL Example Implementation

[`sine-fdn/impact-protocols`](https://github.com/sine-fdn/impact-protocols/tree/main/ileap-data-model/sql-example) also includes an SQLITE3-compliant SQL data model of the iLEAP data model (v1.0.0).

## Contribute

We welcome external contributions.

See [`CONTRIBUTING.md`](CONTRIBUTING.md) for more details.

## Join iLEAP

To join the iLEAP Community, please reach out to [team@ileap.global](mailto:team@ileap.global).
