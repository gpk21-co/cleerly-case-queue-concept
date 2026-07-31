Case prioritization & prior-auth queue — product concept

A self-directed product concept exploring how AI read severity could drive case prioritization and prior-authorization status in a single queue view.

Built after reading about Cleerly PREVIEW (launched March 2026), which maps stenosis ranges to reimbursement thresholds to speed up administrative review for coronary CT angiography reads. This prototype is my own take on what that kind of severity-to-threshold mapping could look like in a case queue — a product-thinking exercise, not a rebuild of Cleerly's actual product.
What it demonstrates
Sorting a case queue by AI-flagged severity
Clicking into a case to see stenosis mapped against reimbursement bands (the "ruler" component is the core interaction)
Tying prior-authorization status to that same severity read
Summary metrics a product team might track for this workflow (time to auth, auto-clear rate, cases needing manual review)
Important disclaimer

This is an independent, self-directed concept. It was not built by, for, or with Cleerly, Inc., and Cleerly was not involved in its creation. All patient names, case IDs, stenosis values, and plaque data are entirely synthetic and fictional, generated for demonstration purposes only. No real patient data, medical imagery, or proprietary Cleerly technology, code, or trademarks are used. References to Cleerly PREVIEW are limited to publicly available information about the product's stated purpose, used here only as context for the problem this concept explores.

Tech

Single-file HTML/CSS/vanilla JS — no build step, no dependencies beyond Google Fonts. Open index.html directly or serve it with any static host.
