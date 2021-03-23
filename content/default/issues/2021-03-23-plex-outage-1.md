---
section: issue
title: PLEX Outage
date: 2021-03-16T03:59:00.000Z
status: resolved
pinned: ""
current_severity: ok
max_severity: down
duration: 1hour, 34mn
resolved_on: 2021-03-16T05:06:00.000Z
affected:
  - Plex
twitterFeed: ""
enableComments: true
---
During the process of adding a new storage array(PowerVault MD1200) to the PLEX Host(Poweredge R720) the system became unresponsive, and crashed. After troubleshooting, it was found one of the SAS External Ports on the external RAID array adapter(Perc H800) had failed. The secondary port was put into place, and the system was rebooted. After the reboot, PLEX became available once again.

This was considered an non-interruptive maintenance that had failed. After the system became available, the new storage array came online, providing WellsFLIX an additional 36.3TB of storage.