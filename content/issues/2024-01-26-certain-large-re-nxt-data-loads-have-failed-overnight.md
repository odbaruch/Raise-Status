---
section: issue
title: Certain large RE NXT data loads have failed overnight
date: 2024-01-26T12:14:26.356Z
resolved: true
draft: false
informational: false
pin: false
resolvedWhen: 2024-01-26T12:14:26.366Z
affected:
  - Data Loads - Salesforce and RE NXT
severity: disrupted
---
**C﻿lient Impact** - Organizations using RE NXT with over 10,000 active donors in Raise should expect to receive automated Stewardship prompts for yesterday's gifts on Monday, Jan 29th. Affected organizations should additionally expect donor data to be out-of-date by one day until tomorrow, Jan 27th.

*Resolved* - Data loads for organizations using RE NXT with over 10,000 active donors in Raise will be rerun automatically this evening after business hours.

*I﻿nvestigation Concluded -* We have concluded our investigation and found that certain large RE NXT data loads timed out overnight due to slow response from the SKY API.

*I﻿ssue Reported -* Our automated alerts system has reported a small number of RE NXT data loads have failed overnight.