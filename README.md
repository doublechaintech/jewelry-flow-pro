# jewelry-flow-pro

In-person buying software for high-volume jewelry events. The app speeds up customer intake, keeps paperwork consistent, and gets checks printed before the customer leaves the table.

---

## Why It Exists

- Replace clipboards and manual data entry with a guided flow.
- Keep compliance docs (ID copy + bill of sale) organized per transaction.
- Print checks on demand so customers leave paid.

---

## Core Capabilities

1. **Driver’s license scanning & auto-fill**
   - Reads PDF417 codes on US driver’s licenses.
   - Auto-populates purchase orders (name, address, DOB, ID number).

2. **Digital signature capture**
   - Captures signatures on Topaz, Wacom, or similar pads.
   - Embeds the signature into the generated Bill of Sale PDF.

3. **Check printing integration**
   - Outputs MICR-ready checks using Checkeeper, VersaCheck, or a local printer.
   - Re-uses seller data and payout amounts from the current purchase order.

4. **Document output & retention**
   - Stores signed Bills of Sale and related check stubs for bookkeeping.
   - Offers print/email copies to the seller on the spot.

---

## Typical Event Flow

1. Scan the seller’s driver’s license to pre-fill the transaction form.
2. Enter purchased items, pricing, and payout details.
3. Capture the seller’s signature on the Bill of Sale.
4. Print the check and optionally email/print the documents for the seller.
5. Archive the transaction artifacts for accounting and compliance.

---

## Integration Targets

- Hardware: PDF417-compatible ID scanners, Topaz/Wacom signature pads,
  MICR-enabled check printers.
- Software: Checkeeper, VersaCheck, or any local check-printing service that
  accepts MICR data.

---

## Getting Started

This repository currently tracks the product specification. Implementation
artifacts (source, build instructions, deployment scripts) will be added as the
software matures. In the meantime:

1. Review the core capabilities above with event stakeholders.
2. Confirm hardware availability (ID scanners, signature pads, printers).
3. Align on local compliance requirements for purchasing secondhand jewelry.

Feature requests and implementation ideas are welcome—open an issue or PR to
discuss.
