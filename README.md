# MismotuMuzej: QR-code guide for a network of small museums (prototype)

*Guida a codici QR per una rete di piccoli musei (prototipo)*

**MIT App Inventor (Android)** · 2020 · version 1.0  
Author: **Massimo Sbarbaro** ([ORCID 0009-0006-8965-9013](https://orcid.org/0009-0006-8965-9013))

## Overview

The first version of a museum guide based on QR codes. The visitor starts the visit, frames the QR code displayed in the museum with the camera and the app opens the corresponding content page in an embedded web viewer. It is the prototype from which the *museum passport* app was developed.

I designed and programmed this application in 2020. It is published here in 2026 as part of the documented record of my software work, with a permanent DOI on Zenodo.

## Main functions

- Start screen with credits and a button to begin the visit (`Screen1`).
- QR-code scanning with the camera (ZXing barcode scanner) and opening of the scanned address in a web viewer (`Screen2`).
- Validation of the scanned text as an http/https address.

## Data

No local data: content pages are reached through the QR codes placed in the museums.

## Technology

MIT App Inventor 2: BarcodeScanner, WebViewer; permissions CAMERA and INTERNET.

## Repository contents

| Path | Content |
|---|---|
| `project/*.aia` | The App Inventor project, ready to be imported (*Projects → Import project (.aia)* at ai2.appinventor.mit.edu). |
| `source/src/` | Screen designs (`.scm`, JSON) and block programs (`.bky`, Blockly XML), one pair per screen. |
| `source/assets/` | Button icons and App Inventor extensions used by the project. |
| `source/youngandroidproject/` | Project properties (package, version, theme). |

## What is not included

Photographs, illustrations, logos, sound recordings and stock images are **not** included: most of them belong to third parties (photographers, illustrators, performers, the commissioning organisation). The project still opens in App Inventor; the components that showed those media are simply empty. The name of the commissioning organisation and the funding statement have been removed, together with addresses, telephone numbers, e-mail addresses and websites of third parties; web addresses used by the app have been replaced with `example.org`. The compiled APK and its signing key are not published.

## Related repositories

- [museum-network-qr-passport-appinventor](https://github.com/massimosbarbaro/museum-network-qr-passport-appinventor)

## How to cite

Use the citation metadata in [`CITATION.cff`](CITATION.cff) (GitHub: *Cite this repository*). Each release is archived on Zenodo with its own DOI.

> Sbarbaro, Massimo. *MismotuMuzej: QR-code guide for a network of small museums (prototype) (MIT App Inventor (Android), 2020)*. Software, version 1.0. GitHub: https://github.com/massimosbarbaro/museum-qr-guide-prototype-appinventor

## License

Released under the [MIT License](LICENSE). © 2020 Massimo Sbarbaro.
