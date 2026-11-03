# Repository Guide: SH-101 Industry Plays

## What This Repository Holds
This repository contains "SH-101 verified growth plays", a collection of industry-specific growth strategies and case studies with measured results. It consists of a single self-contained HTML report (`index.html`) focusing strictly on verified plays.

Only plays with a public URL, a measured result, and a quote copied from that page are included. The focus is to keep the report "thin" by excluding unaudited or unverified fluff where possible, though vendor and self-reported pages are included and labeled as such.

## The Plays Contained
The plays are organized into the following industry categories:

1. **FLEET-COMMERCIAL-VEHICLE-DEALERSHIP** (3 plays)
2. **FLEET-MAINTENANCE** (2 plays)
3. **FOOD-BANKS-PANTRIES** (2 plays)
4. **FOOD-TRUCK-MOBILE-CATERING** (1 play)
5. **FOODSERVICE-DISTRIBUTOR** (2 plays)
6. **FOUNDATION-REPAIR-WATERPROOFING** (3 plays)
7. **FRANCHISES** (1 play)
8. **FREIGHT-BROKERAGE** (2 plays)

## Play Structure
Each play is structured consistently within the `index.html` file. A typical play includes:
- **Actor and Vendor**: The name of the company or client, and any vendor/partner involved (e.g., agency or software provider).
- **Result Summary**: A brief, stated result (e.g., percentage increase in sales, amount of money saved, or leads generated).
- **Source Link**: An anchor tag linking to the original public case study, article, or press release.
- **Quote**: A `<blockquote>` containing the exact text from the source page that states the measured result.
- **Verification Note**: A `.meta` paragraph detailing the verification status (e.g., "Vendor case study", "Actor identity NOT VERIFIED", or expectations versus realized outcomes).

## How the Set is Maintained
- **Content Updates**: All plays and their data are maintained directly in the `index.html` file. There is no build step or static site generator. The file is hand-authored HTML with inline CSS.
- **Verification Standard**: A play is proven only if the named actor’s own filing or an independent reporter quoting a ledger repeats the number. Vendor pages with unnamed clients are labeled and not counted as named systems.
- **Visual Captures**: Layout captures of the report are maintained in the `captures/` directory as SVGs (`report-1440.svg` for desktop and `report-390.svg` for mobile). These are generated manually (not via headless browser screenshots) to reflect the layout of the verified set.
