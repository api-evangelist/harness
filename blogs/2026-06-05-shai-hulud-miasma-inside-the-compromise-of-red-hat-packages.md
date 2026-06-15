---
title: "Shai-Hulud Miasma: Inside the Compromise of Red Hat's Packages"
url: "https://www.harness.io/blog/shai-hulud-miasma-inside-the-compromise-of-red-hats-packages"
date: "2026-06-05"
author: "Roshan Piyush"
feed_url: "https://www.harness.io/blog/rss.xml"
---
On June 1, 2026, security teams discovered that 32 packages within the @redhat-cloud-services npm namespace were compromised with a credential-stealing worm called Miasma after an employee's GitHub account was hijacked, allowing attackers to inject malicious code that bypassed code review processes. The malware runs during installation, extracts credentials and cloud identities, and spreads itself by republishing infected packages to other projects it can access. This breach occurred within Red Hat's internal release infrastructure, highlighting the risk of supply chain attacks that exploit trusted internal systems rather than external dependency chains.
