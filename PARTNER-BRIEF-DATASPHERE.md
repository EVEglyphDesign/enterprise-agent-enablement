# A Datasphere Small-Unit Motion for SAP Account Executives

**Partner brief — for the SAP AE who has a customer stuck between an expiring trial and a stalled presales cycle.**

**Reader:** an SAP Account Executive in presales architecture
**Carrier:** Jeff Eden — EVEglyphDesign services executive; [linkedin.com/in/jeffeden](https://www.linkedin.com/in/jeffeden)
**Public counterpart of a private engagement note.** Client-side names and commercial figures are held in a private repository. Everything on this page is either publicly stated by SAP, publicly stated by EVEglyphDesign on its own surfaces, or generic to the AE's own book of business.

---

## The one sentence to walk in saying

> *"I have a partner who can go in on your customer's demo tenant, stand up Datasphere and SAC against the customer's own data in weeks, and hand them back a live report before you ever ask for a purchase order — so your first meeting after the trial is a licensing conversation, not another proof-of-concept debate."*

---

## The customer situation the AE already knows

- **Classic SAP BW 7.5** — mainstream maintenance ends **31 December 2027**, extended maintenance ends **31 December 2030** ([SAP · BW/4HANA End of Mainstream Maintenance Key Dates](https://www.sap.com/documents/2019/02/1ca4c940-3a7d-0010-87a3-c30de2ffd8ff.html); [SAP · NetWeaver 7.5 & BW/4HANA Maintenance Strategy](https://pages.community.sap.com/topics/abap/netweaver-maintenance-strategy)).
- **SAP BW/4HANA** — maintained through at least 2040, but the innovation gravity has shifted to Datasphere and SAC ([SAP · maintenance strategy](https://pages.community.sap.com/topics/abap/netweaver-maintenance-strategy)).
- **SAP Analysis for Microsoft Office (AfO)** — the Excel front-end most BW customers live in. The successor motion SAP is pointing to is the **SAP Analytics Cloud add-in for Microsoft 365**.
- **Datasphere + SAC** — the sanctioned successor stack. A **30-day free Datasphere trial** on a shared tenant with sample data ([SAP · Experience SAP Datasphere](https://www.sap.com/products/data-cloud/datasphere/trial.html)) and a **free SAC trial** ([SAP · Analytics Cloud trial](https://www.sap.com/products/technology-platform/cloud-analytics/trial.html)) exist — but a trial on sample data is not the same as a working report against the customer's own P&L.

The presales challenge is not the story. Every SAP AE tells this story. The challenge is the demo. Trials expire before customer IT has finished the network paperwork; sample data does not move a CFO; and the AE's SIs typically cannot spin up a real customer-data demo without a full statement of work, at which point the deal has already stalled.

The gap is not architecture. It is presales execution capacity in bounded units.

---

## What EVEglyphDesign already did at Epiq

Delivered work, not a proposal. The public evidence is on our own surfaces:

- **A Contract-to-Cash semantic layer in SAP Datasphere** on the customer's own data, delivered inside a partnership Steel Cloud Solutions led. Systems in scope included SAP S/4HANA, Workday, Salesforce, Bullhorn, and AWS S3/Lake.
- **A cross-system AI agent** — LangGraph reasoning against Datasphere's OData surface, with the compliance controls the architecture required.
- **Delivery through Microsoft Teams** — the users' existing interface. No new client to roll out.
- **A public demonstration surface** — [epiq-revenue-leakage](https://eveglyphdesign.github.io/epiq-revenue-leakage/) carries the non-proprietary reconciliation views and the shape of the work.
- **A public reference model** — [eve-datasphere-sovereign](https://github.com/EVEglyphDesign/eve-datasphere-sovereign) is an ACDOCA-anchored SAP replication schema covering 58 tables across FI, CO, MM, SD, PP, PM, and QM.

Both surfaces are public. The AE's team can read them today without an NDA.

---

## Four packaged small work units

Each one is quotable in a sentence, deliverable in weeks, and exit-friendly. We arrive, we set up, we hand back, we leave.

### 1 · Datasphere Demo-Tenant Setup on the Customer's Own Data

The customer sees their own P&L — one operating region, one product family — running inside their trial Datasphere tenant, connected to their SAP source system through their sanctioned integration path. Not sample data.

**Duration:** 3–4 weeks. **Shape:** fixed price. **Exit:** we hand back the tenant, the models, and a short compliance brief.

### 2 · AfO-to-SAC Report Parity Sprint

The customer's five most-used Analysis for Office reports — reproduced in the SAC add-in for Microsoft 365 — running against the same numbers, on the same schedule, with the same drill paths.

**Duration:** 4–6 weeks. **Shape:** fixed price per report bundle. **Exit:** we hand back the SAC content and a runbook.

### 3 · Governed Finance Proof (the Epiq Shape)

A working Teams agent that answers finance questions across the customer's SAP estate, with source citations and governance controls — the pattern delivered at Epiq, adapted to the customer's data and one finance lane they choose (revenue leakage, close acceleration, invoice reconciliation).

**Duration:** 6–8 weeks. **Shape:** fixed price with a small optional continuation. **Exit:** we hand back the pattern and the operating notes.

### 4 · BW Replacement Proof

A bounded proof that Datasphere + SAC can perform a defined slice of what the customer's BW installation performs today — validated by the customer's own users, documented, and with any exceptions explicitly listed.

**Duration:** 6–10 weeks. **Shape:** fixed price with named outcomes. **Exit:** we hand back the proof, the reconciliation, and the decision brief.

---

## The commercial shape

- **The AE refers.** They send a customer stalling in Datasphere or SAC presales.
- **EVEglyphDesign executes on the customer's demo license.** The 30-day Datasphere trial and free SAC trial are the runway. The AE does not procure. The customer does not sign a large statement of work.
- **The setup is packaged, fixed-price, and exit-friendly.** One of the four above.
- **The AE closes the license.** The customer has now seen their own numbers running in Datasphere and SAC.
- **Further build work is a referral back to the incumbent SI**, or to EVEglyphDesign only if the customer has no incumbent and needs an affordable alternative — the referral always in service of the AE's SAP license booking.

### On full S/4HANA implementation work

Full S/4HANA implementations belong with a large SI. EVEglyphDesign fits inside a full S/4 conversation only as:

- **Flex labor supporting the incumbent SI** — named specialists, monthly floor, on the SI's paper if they want it.
- **An affordable alternative** — only if the customer has no incumbent and cannot fund a large SI. Stated plainly, not as a poaching move.

In both cases, the deal the AE cares about — the SAP license — is the deal being sold.

---

## References

- The Epiq revenue-leakage public surface: [eveglyphdesign.github.io/epiq-revenue-leakage](https://eveglyphdesign.github.io/epiq-revenue-leakage/)
- The Datasphere sovereign reference model: [github.com/EVEglyphDesign/eve-datasphere-sovereign](https://github.com/EVEglyphDesign/eve-datasphere-sovereign)
- Public enterprise-agent-enablement surface: [eveglyphdesign.github.io/enterprise-agent-enablement](https://eveglyphdesign.github.io/enterprise-agent-enablement/)
- Jeff Eden on LinkedIn: [linkedin.com/in/jeffeden](https://www.linkedin.com/in/jeffeden)
- SAP BW/4HANA End of Mainstream Maintenance Key Dates: [sap.com/documents/2019/02/1ca4c940](https://www.sap.com/documents/2019/02/1ca4c940-3a7d-0010-87a3-c30de2ffd8ff.html)
- SAP NetWeaver 7.5 & BW/4HANA maintenance strategy: [pages.community.sap.com/topics/abap/netweaver-maintenance-strategy](https://pages.community.sap.com/topics/abap/netweaver-maintenance-strategy)
- SAP Datasphere trial: [sap.com/products/data-cloud/datasphere/trial](https://www.sap.com/products/data-cloud/datasphere/trial.html)
- SAP Analytics Cloud trial: [sap.com/products/technology-platform/cloud-analytics/trial](https://www.sap.com/products/technology-platform/cloud-analytics/trial.html)

---

© 2026 EVEglyphDesign. All rights reserved.
*Pour le bien-être du peuple.*
