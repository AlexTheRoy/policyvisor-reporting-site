# PolicyVisor Insurance Group Reports

Static report site for PolicyVisor Insurance Group (#771), deployed on Vercel. Edition 11-13-26: all time, since launch on Jan 19, 2026 through Nov 13, 2026.

- `index.html`: report hub (Campaign Reports, Website & Research)
- Campaign Overview, Auto, Home and Home (Weekend) campaign reports (file names carry the `All-Time` window token)
- Monthly Sales by Source & Aid, Source & ZIP Sales (with the ZIP sales CSV), Lead-to-Sale Gap Analysis, Inbound Call Review
- Website SEO audit of policyvisor.com, Pennsylvania flood and winter storm risk, Pennsylvania demographic research and its ZIP data CSV (research content prepared Oct 12, 2026, unchanged in this edition)
- `vercel.json`: clean URLs, security headers, `noindex`, redirects from the earlier Last-3-Months-11-13-26 and 10-12-26 file names

Notes:

- GOAL receives only Quoted and Sold events (no Contacted pixel), so contact rate is not shown.
- Sales are matched to leads from the 11 conversion lists (Feb 12 to Nov 13, 2026), by phone and by name plus ZIP, and compared with GOAL's Quoted (370) and Sold (57) events on the Lead-to-Sale Gap Analysis. Sales after Nov 13, or not yet in a list, are not counted.
- No Producer Pipeline page: the four newest lists (Aug 14 to Nov 13) have no producer column. Producer is known for 41 of the 55 sales tied to a lead record, and for none of the 14 on leads since Jul 24 and none of the recent quotes, so a producer view would misstate recent months.
- Campaign 2457 (Auto) never had spend; Auto (2458) and Home (Weekend) started in May, and Home was the only campaign from Jan 19 to Apr 30.
- Monthly figures: Jan starts on Jan 19 and Nov runs through Nov 13. Neither partial month is projected.
