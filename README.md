# GRC Compliance Worksheets

A collection of ready-to-use governance, risk, and compliance (GRC)
worksheets covering ITGC, SOX, NIST, and third-party/vendor risk. Each file
is a fillable Excel workbook or Word checklist — no macros, no add-ins,
just structured templates you can drop into an actual audit or review
engagement.

## Contents

### `ITGC/`
IT General Controls, covering the full control set an ITGC audit typically
tests:
- **ITGC_Access_and_Operations_Workbook.xlsx** — a 6-tab workbook: Logical
  Access, Change Management, Program Development, Computer Operations, and
  Physical Security. Every control includes a *Suggested Evidence /
  Documents to Review* column, plus owner, frequency, test approach, sample
  size, and status tracking with dropdown validation.
- **ITGC_Access_Checklist.docx** — a plain checkbox checklist version of the
  Logical Access domain, for a quick walkthrough or print-and-check review.

### `SOX/`
- **SOX_Compliance_Workbook.xlsx** — Entity Level Controls, Information
  Security, Financial Close, Revenue (O2C), Procure-to-Pay, Payroll,
  Segregation of Duties, and Disclosure Controls. Includes an Assertion(s)
  column (Existence/Occurrence, Completeness, Accuracy, etc.) alongside the
  standard test-tracking fields.

### `NIST/`
- **NIST_CSF_2.0_Compliance_Workbook.xlsx** — one tab per CSF 2.0 Function
  (Govern, Identify, Protect, Detect, Respond, Recover), broken into their
  official Categories/Subcategories, rated on the NIST 5-level maturity
  scale (Partial → Adaptive).
- **NIST_SP_800-30_Risk_Assessment_Worksheet.xlsx** — a scored risk register
  built on the NIST 800-30 Likelihood × Impact methodology, with the full
  5×5 qualitative risk matrix and automatic risk-level calculation.

### `Third-Party-Vendor-Risk/`
- **Vendor_Security_Checklist.docx** — full vendor lifecycle checklist:
  pre-engagement risk tiering, security assessment, contractual
  protections, access provisioning, ongoing monitoring, incident handling,
  and offboarding.
- **Vendor_Security_Review_Tracker.xlsx** — the same 40-item checklist in
  trackable spreadsheet form, with dropdowns for risk tier, frequency, and
  status.
- **Vendor_Risk_Assessment_Worksheet.xlsx** — a scored questionnaire across
  five weighted risk categories (Security, Data Sensitivity/Compliance,
  Operational/BC, Financial, Reputational) that auto-calculates an overall
  risk tier (Low/Medium/High/Critical).

## How to use these

1. Download the workbook/checklist for the framework you're working with.
2. Duplicate the relevant tab per vendor/system/entity being assessed
   (right-click the tab → Move or Copy → Create a copy).
3. Fill in the yellow-shaded cells — everything else is either static
   reference content or an auto-calculating formula.
4. Retain completed workbooks as your audit evidence/workpapers.

## Scope and limitations

These are **starting templates**, not a certified or legally-binding
compliance framework. They're built from the publicly available structure
of ITGC testing practices, the SOX control framework, NIST CSF 2.0, and
NIST SP 800-30 — but every organization's actual control environment,
risk appetite, and regulatory obligations differ. Adapt the control
descriptions, weights, and thresholds to your own environment before
relying on these for a real audit or regulatory submission.

## License

Released under the MIT License (see `LICENSE`) — use, modify, and
redistribute freely, including for commercial audit/consulting work.

## Contributing

Issues and pull requests are welcome — particularly additions of other
frameworks (ISO 27001, PCI-DSS, HIPAA, GDPR) following the same
worksheet structure.
