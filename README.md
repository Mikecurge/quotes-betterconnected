# quotes.betterconnected.biz

Build 22 draft. Self-serve route for Better Connected: upload a bill, sign the L1 by DocuSign, hear back by email from a named account manager.

- Single static page: index.html (light theme, Better Connected brand colours and fonts).
- Draft mode: ENDPOINT and REMIND_ENDPOINT at the bottom of index.html are empty, so nothing is sent or stored. A banner says so.
- Go live: set ENDPOINT to the Make.com webhook for scenario BCL_Quotes_Self_Serve, set REMIND_ENDPOINT, then add the custom domain quotes.betterconnected.biz (CNAME file plus a Cloudflare DNS record).
- noindex is set until launch.
