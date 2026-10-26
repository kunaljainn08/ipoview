# IPOView: DRHP and RHP analyser

**Live tool:** https://kunaljainn08.github.io/ipoview/

IPOView helps you read an Indian IPO offer document (RHP, DRHP or prospectus) in a structured way. Everything runs in the browser: the PDF is never uploaded anywhere.

## What it does

- **One-step report:** upload the RHP or DRHP (and, optionally, the anchor allocation file). IPOView reads the issue details, the restated financials (converted from ₹ million or ₹ lakh to ₹ crore), the pre-issue share count, promoter holding, listed peers, risk factors and red flags, then opens a ready 6-page IPO note in the Report tab with a checklist of anything that still needs your input.

- **Overview:** detects the company name, document type, listing, fresh issue, offer for sale, price band, lot size, bid open/close and anchor dates, face value, lead managers, registrar, promoters and use of proceeds, each linked to its page.
- **Sections & search:** maps the standard SEBI ICDR sections with page ranges and lets you search the whole document.
- **Risk factors:** lists the numbered risk factors, groups them by theme, and lets you star the ones that matter.
- **Red flags:** scans for terms such as pledged shares, qualified audit opinions, regulatory actions and loan defaults, and separates real mentions from routine “none” disclosures.
- **Workbench:** you enter the restated financials, offer details and listed peers; it calculates growth, margins, ROE, ROCE, leverage, cash conversion, receivable days and valuation (P/E, EV/EBITDA, P/B, market cap/sales, premium to peers).
- **Competitive:** compares the IPO with its listed peers on revenue, growth, margins, ROE, ROCE, leverage, P/E, EV/EBITDA and market cap, plus custom KPIs. Peers from the RHP’s basis for offer price table are imported automatically where possible. Includes a radar chart, rankings and award stickers.
- **Market Pulse:** enter the grey market premium (GMP), lot size and subscription (or paste an IPO page to auto-fill). Shows a GMP thermometer, estimated listing price, gain per lot and retail allotment odds, with quick links to IPO Premium, Investorgain and Chittorgarh.
- **Anchor Book:** upload the anchor allocation document (PDF, CSV or Excel) or paste the table. IPOView lists every anchor investor, classifies them (domestic mutual funds, insurers, sovereigns and pension funds, FPIs, AIFs), and shows the long-only share, top-5 concentration, marquee names, the 30-day and 90-day lock-in unlock dates, and an anchor-quality score that feeds the listing-day rating.
- **Rating & Crux:** two scores out of 10, one for listing day (driven by GMP, subscription and valuation) and one for the long term (driven by financials, competitive position, valuation and governance), each with its own verdict and a plain-English crux. You can adjust either score and add your own calls and note.
- **Report Studio:** the report picks up the company’s brand colours and logo from the RHP cover automatically (or from an uploaded logo), with an editable “About the company” paragraph and assumptions.
- **IPO note (PDF and Word):** a 6-page, broker-style IPO note in the company’s colours: header with key data points, issue details sidebar, T+3 timeline, issue composition, shareholding, two verdicts and the crux; rationale and concerns with financial charts; valuation at both ends of the band with peer-implied value and the growth already priced in; and a “Beyond the Broker Note” page with report-card grades, 3-year return scenarios, listing-day scenarios, allotment maths, the post-IPO balance sheet and quality of earnings; competitive edge, questions for management and what to track; risks, financial summary, analyst’s note and the disclaimer at the end.
- **Excel export** of all inputs, ratios, scores and peer data.

## Limits

GMP is unofficial and unregulated, and is entered by hand because a static website cannot pull live data from other sites. 
Automatic extraction uses pattern matching, so detected values depend on each PDF’s layout and should always be checked against the page shown. Scanned PDFs cannot be read. For learning and discussion only; not investment advice.

Built by [Kunal Jain](https://www.linkedin.com/in/kunaljainkj/), CA Finalist. Also see [CapView](https://kunaljainn08.github.io/cap-table-test/), a cap table and fundraise simulator.
