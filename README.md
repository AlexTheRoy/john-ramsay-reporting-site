# John Ramsay Insurance Agency LLC Reporting Site

Static client reporting site for John Ramsay Insurance Agency LLC (GOAL account #433), deployed on Vercel.

## Structure

- `index.html`: hub with Campaign Reports and Website & Research sections
- `John-Ramsay-Campaign-Overview-YTD-10-14-26.html`, `...Auto...`, `...Home...`: campaign reports, year to date
- `John-Ramsay-Inbound-Call-Review-10-14-26.html`: inbound call review, Jul 16 to Oct 14, 2026
- `John-Ramsay-SEO-Audit-10-14-26.html`: Allstate agent page audit
- `John-Ramsay-WA-*`: Washington demographic and wildfire/earthquake research, plus the ZIP CSV
- `vercel.json`: clean URLs, security headers, `noindex`

No build step. Push to `main` and Vercel redeploys.
