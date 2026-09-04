# DixonDesk - overview for website work

## What it is

DixonDesk is a Windows desktop app for resellers - people who buy physical
goods to resell for profit. It automatically tracks purchases and sales
across multiple retailers and marketplaces, and gives an accurate,
real-time picture of profit, margin, and ROI - without manual data entry
for most of it.

It's local-first: everything lives in a database file on your own
computer, not in someone else's cloud.

## Who it's for

Resellers juggling several buying sources and several selling channels at
once - someone who might buy from Walmart, Target, Fanatics, and a few
niche retailers, then sell across eBay, Amazon, Walmart Marketplace, and
Temu. Common in collectibles and hobby reselling (action figures, trading
cards, sneakers) but not limited to it - anyone reselling physical
inventory at real volume.

The kind of person currently piecing this together across spreadsheets,
each marketplace's own separate reporting, and manual note-taking - and
losing real time and real accuracy doing it.

## The core problem it solves

Reselling profit is deceptively hard to track correctly by hand:

- The same item can be bought in different batches at different prices,
  and knowing which specific batch a given sale actually came from
  matters for the real profit number - not just an average.
- Purchases arrive as emails, sales arrive from several different
  marketplace accounts, and reconciling all of it by hand is slow and
  error-prone.
- Fees, shipping costs, refunds, and returns all eat into profit in ways
  that are easy to lose track of, especially at higher volume.

## What DixonDesk actually does

- **Reads your email automatically.** Connects to your inbox and
  recognizes order confirmations from a wide range of retailers,
  logging each purchase - vendor, items, cost, shipping, tax - without
  you typing it in.
- **Syncs your sales automatically.** Connects to eBay, Amazon, Walmart,
  and Temu seller accounts to pull in real orders, fees, and refunds.
- **Tracks real cost basis, not averages.** Each purchase batch (a "lot")
  keeps its own cost. When something sells, the app matches it to the
  actual batch it came from, so profit numbers are the real numbers -
  not an estimate.
- **Catches duplicates.** If a sale gets logged both by hand and later
  through a sync, the app flags it for a quick decision - merge into
  one record, or confirm they're genuinely different sales.
- **Handles the messy real-world cases.** Partial refunds, buyer returns,
  supplier refunds, serial-numbered items, multi-item orders - the kind
  of detail that spreadsheets quietly get wrong.
- **One dashboard, not five.** Profit, margin, and ROI broken down by
  vendor, platform, and time period, in one place instead of stitched
  together from each marketplace's own separate reporting.

## What makes it different

- **Actually automated**, not just a spreadsheet template - most
  purchases and sales require zero manual entry.
- **Gets the accounting right** in ways generic tools don't: real,
  batch-level cost tracking rather than averaged cost, careful handling
  of fees/shipping/refunds, and multi-source reconciliation across
  several retailers and marketplaces at once.
- **Local and private** - your financial data stays on your own machine.
- **Built from real, ongoing use** - actively being refined against real
  reseller workflows and real edge cases as they come up, not built once
  and left alone.

## Tone/positioning notes for the site

Written for a working reseller, not a generic small-business audience -
someone who already knows what a "lot," an "ROI," and a "marketplace
sync" are. Confidence should come from specificity (what it actually
handles) rather than generic claims like "powerful" or "easy to use."
