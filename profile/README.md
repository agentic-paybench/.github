# agentic-paybench

Research artefacts for **measuring agent-to-agent payment rails**: a pre-registered evaluation methodology and a capability oracle. Rail-neutral by design: the method is designed for pairwise comparison, no comparison results are published, and the work holds no commercial relationship with any rail it measures.

| Repository | What it is |
|---|---|
| [payhelm](https://github.com/agentic-paybench/payhelm) | PayBench: the measurement methodology (frozen v1.2), harness, and calibrated fixtures, as a fork of HELM. Pre-registered and anchored before measurement: OSF DOIs [10.17605/OSF.IO/XGFUJ](https://doi.org/10.17605/OSF.IO/XGFUJ) and [10.17605/OSF.IO/UFQG5](https://doi.org/10.17605/OSF.IO/UFQG5). |
| [oracle](https://github.com/agentic-paybench/oracle) | The capability oracle: schema, ingestion, methodology, and the static read surface, live at [oracle.agentic-paybench.dev](https://oracle.agentic-paybench.dev/). |

**What is published, and what is not.** The methods are public. Rail-by-rail results are not published, and nothing here ranks named rails, recommends a rail, or routes a payment. That is a choice, recorded in the methodology, not an omission.

**Rails covered by the methodology:** x402, AP2, the Machine Payments Protocol (the Stripe and Tempo HTTP 402 protocol, on more than one settlement rail), and Lightning-based rails, measured on test networks and first-party traffic.

Research context, writing, and contact: [everydayai.link](https://everydayai.link/), mblake@everydayai.link.