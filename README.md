# AckHarbor™ Spyglass™: HL7® v2 Message Viewer

A free, offline viewer that explains every segment and field of an HL7 v2 message. Paste a message, browse the segment and field tree, and click any field for plain-English Insights, code-table meanings and fix tips.

**Use it online:** https://ackharbor.com/tools/hl7-viewer.html

> ⚠️ **No real patient data. Do not load PHI.** Use test or de-identified messages only. All sample data is invented.

## Features

- Parses HL7 v2 messages into a segment, field, component and repetition tree
- Field names and code-table values (for example table 0001 Administrative Sex)
- Validation alerts with how-to-fix guidance (MSH-10, PID-3, PID-7, OBX and more)
- 21 sample messages: ADT (A01–A40), ORM, ORU, RDE, SIU, MDM, DFT, BAR, VXU and ACKs
- Batch file mode (AckHarbor Manifest™): analyze a file of many messages, with a synthetic 120-message practice batch
- De-identify helper for test files
- Runs fully offline; nothing is uploaded

## How to run

1. Clone or download this repository.
2. Open `index.html` in a modern browser.

No build step and no dependencies.

## License

[PolyForm Noncommercial 1.0.0](LICENSE). Copyright © 2026 DaRider Tech LLC. Free for learning, teaching and other noncommercial use. Commercial use, resale or hosting it as a service needs written permission from DaRider Tech LLC (support@ackharbor.com).

HL7® and FHIR® are registered trademarks of Health Level Seven International; use does not imply endorsement.
