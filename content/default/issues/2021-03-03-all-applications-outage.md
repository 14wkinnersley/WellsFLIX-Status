---
section: issue
title: All Applications Outage
date: 2021-03-03T20:20:00.000Z
status: resolved
pinned: ""
current_severity: ok
max_severity: down
duration: 1h 32mn
resolved_on: 2021-03-03T21:52:37.092Z
affected:
  - WellsFLIX Website
  - Plex
  - Overseerr
  - Unifi
  - Cloud
twitterFeed: ""
enableComments: true
---
Impacted Applications: All Applications

Summary: WellsFLIX performed major DNS work across the site, migrating from Google to Cloudfare. During migration, 75% of the A records, and CNAME records did not migrate. 

Status: The DNS A Records, and CNAME records were updated manually, and DNS Caches were cleared. All applications have been verified as fully functional.