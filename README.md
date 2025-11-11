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


### Current Features

● Clean Purchase Flow
● Process Core flow without internet
● Adviser can scan their credential card (QR Code) to ensure not leaking pass code
● Recovering the flow after laptop restart/power adaptor
● Adviser can select fields to print check on blank paper or a check stock
● Running on web to ensure fluent upgrade
● Sync to cloud to ensure data will not loss
● Works on windows laptop


### Roles

● Advisor/Buyer： the persons buys advisor who purchase jewelry from another
person
● Seller: the person who sell jewelry to advisor/store


## Local Buying App


### The start page

● Authenticate Advisor to start using the software
● Advisor can use hardcopy QR code or QR code on Phone
● Once the device has been bound, internet access is NOT mandatory for purchase flow


### Once Authenticated

```
● Advisor can start a purchasing
process or managing orders or
going to setting
```

### Scan driver license

```
● All info extracted from driver license
● Infomation needed for KYC/AML for
jewelry transactions
```

### Input the bill info

```
● Input bill info
● Extra text for price input to
ensure work with big numbers
```

### Sign the purchase order by parties

```
● A purchase order generated for
signatures
```

### Review the check info

```
● Review check content with the
seller
```

### Print Check

```
● Check can be print
here
● Printing stock label
and purchase order
are also options
```

### Complete the order

```
● A clear sign that the order has
been done
```

### Hardware used for the app

```
● A scaner able to scan PDF 417
● A wacom for signature
● Works on windows 10 / 11
```

### Advisor to view orders


## Buying Pro Cloud


### Login to cloud part


### Manage Advisors

● Advisor can download a QR code as credential for events


### Setup checking account for payment

● Admin can set up mutiple checking account for different events


● Create events here can track more data about the events


● Private Seller can be tracked after the transaction done


### Purchase Orders

● Orders can be synchronized from Local Buying App to Cloud, data can be
centralized backup in cloud

Feature requests and implementation ideas are welcome—open an issue or PR to
discuss.
