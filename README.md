# John Ramsay Insurance Agency LLC Reporting Site

Static client reporting site for John Ramsay Insurance Agency LLC (GOAL account #433), deployed on Vercel.

## Structure

- `index.html`: hub with Campaign Reports and Website & Research sections
- Campaign Reports, year to date (Jan 1 through Nov 20, 2026, with all-time context since Apr 15, 2025):
  - `John-Ramsay-Campaign-Overview-YTD-11-20-26.html`: all campaigns, Marketplace included
  - `John-Ramsay-Auto-Campaign-Performance-YTD-11-20-26.html`: Auto (New) and Auto together, opening with Analytics Breakdowns and Quote and Bind Mix
  - `John-Ramsay-Home-Campaign-Performance-YTD-11-20-26.html`: Home, opening with Analytics Breakdowns and Quote and Bind Mix
  - `John-Ramsay-Analytics-Breakdowns-11-20-26.csv` and `John-Ramsay-Quote-Bind-Mix-11-20-26.csv`: every GOAL Analytics row behind those two sections (quote funnels only; the Marketplace is not in GOAL Analytics)
  - `John-Ramsay-Monthly-Sales-by-Source-11-20-26.html`: monthly sales by source and ad channel, with the ad channels that have the fewest quotes and binds
  - `John-Ramsay-Source-ZIP-Sales-11-20-26.html` and `John-Ramsay-ZIP-Sales-11-20-26.csv`: sales by source, ad channel, county and ZIP
  - `John-Ramsay-Inbound-Call-Review-11-20-26.html`: inbound call review, Aug 22 to Nov 20, 2026 (the last 90 days)
  - `John-Ramsay-Most-Valuable-Prospect-11-20-26.html`: for Auto and Home, the attribute values with the most bound policies, lowest CPA marked
- Website & Research (Oct 14, 2026):
  - `John-Ramsay-SEO-Audit-10-14-26.html`: agency web page and local listings audit
  - `John-Ramsay-WA-*`: Washington demographic and wildfire/earthquake research, plus the ZIP CSV
- `vercel.json`: clean URLs, security headers, `noindex`, and redirects from the 11-04-26 and 11-18-26 report URLs to the 11-20-26 ones

No build step. Push to `main` and Vercel redeploys.
