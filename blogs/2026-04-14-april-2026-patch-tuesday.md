---
title: "April 2026 Patch Tuesday"
url: "https://www.ivanti.com/blog/april-2026-patch-tuesday"
date: "Tue, 14 Apr 2026 22:51:36 Z"
author: "Chris Goettl"
feed_url: "https://www.ivanti.com/blog/rss"
---
<p>The lead up to Patch Tuesday has been interesting. We had a Google Chrome zero-day (CVE-2026-5281) that was patched on April 1, an Adobe Acrobat Reader zero-day (<a href="https://helpx.adobe.com/security/products/acrobat/apsb26-43.html" rel="noopener" target="_blank">CVE-2026-34621</a>) late in the day on Friday April 10, and several older CVEs that were added to the CISA KEV list yesterday (<a href="https://www.cisa.gov/news-events/alerts/2026/04/13/cisa-adds-seven-known-exploited-vulnerabilities-catalog" rel="noopener" target="_blank">April 13</a>). All of this amidst a lot of industry buzz about Anthropic Mythos and <a href="https://www.anthropic.com/glasswing" rel="noopener" target="_blank">Project Glasswing</a>.</p>

<p>What is the correlation between these events and Project Glasswing you ask? Most of the discussions around Mythos have been focused on where it will be used and the ramifications.</p>

<p>Finding exploitable flaws in code can be a powerful tool for good when used by the vendor writing the code before it is released. However, it will also be used by researchers and threat actors to find flaws in code that is already released and that is where my speculation is directed.</p>

<p>Consider the knock-on effects of a massive model like Mythos and what it will mean near term and longer term for the software that companies consume. Near term you will have the big players using a solution like this to release more secure code. As researchers and threat actors adopt more robust AI models to identify exploitable flaws this will result in more coordinated disclosures (good), zero-day exploits (bad) and n-day exploits (bad). All of this will result in more frequent, and more importantly, urgent software updates.</p>

<p>Many organizations currently struggle to keep up with priority updates resolving exploited vulnerabilities when they occur outside of their normal monthly maintenance. I suspect most organizations were not aware of the Adobe Acrobat zero-day exploit until the CISA KEV update yesterday. This means that threat actors had another 2-3 days of free reign to exploit CVE-2026-34621 before most organizations became aware and many of those organizations will likely handle the update as part of their regular maintenance that is starting today on Patch Tuesday.</p>

<p>Browser security updates are a weekly occurrence. Many other applications that users are utilizing regularly release updates on a continuous cadence, not a set monthly release date. This means many of the user targeted exploits are going to occur in software that is releasing outside of the average organizations maintenance schedules and that frequency is about to increase. It is hard to say if that increase is going to be 1.5x or 5x, but rest assured that the increase will be noticeable and will exacerbate a challenge that most organizations already struggle with – timely patch management.</p>

<p>Enter Exposure Management. This is really a mindset and maturity change as much as a technology evolution. The mindset change requires us to consider a world where we need to make the decisions up front and monitor those decisions. This is called defining your Risk Appetite and monitoring your Risk Posture. Doing this effectively matures an organizations’ response to risks and makes remediation activities much more clear cut.</p>

<p>The technology evolution requires the traditional vulnerability assessment technologies to integrate into a broader ecosystem where asset visibility or system of record comes together with vulnerability assessment and vulnerability intelligence solutions to refine when risks require more immediate action vs waiting for your regular maintenance activities to occur. Most important is the need for this tech stack to be integrated with your AEM (Autonomous Endpoint Management) platform as this is where remediation predominantly (and automatically) occurs.</p>

<p>Now, back to our regularly scheduled Patch Tuesday update. Microsoft has resolved 169 CVEs this month which is a massive patch Tuesday lineup. April Patch Tuesday is the second-largest Patch Tuesday on record behind the October 2025 Patch Tuesday which resolved 175 CVEs. The lineup includes one zero-day exploit (CVE-2026-3220) and one public disclosure (CVE-2026-33825) and breaks down into 8 Critical, 156 Important, 3 Moderate and 1 Low severity.</p>

<p>The zero-day CVE is in Microsoft SharePoint and the public disclosure is in Microsoft Defender making those two updates the most urgent for this month in addition to the Adobe Acrobat and Google Chrome updates leading up to Patch Tuesday.</p>

<h2>Microsoft’s known exploited vulnerabilities</h2>

<p>Microsoft resolved a Server Spoofing Vulnerability in Microsoft SharePoint (<a href="https://msrc.microsoft.com/update-guide/vulnerability/CVE-2026-32201" rel="noopener" target="_blank">CVE-2026-32201</a>). The vulnerability is rated Important by Microsoft and has a CVSS v3.1 score of 6.5, but it has been confirmed to be exploited in the wild. An attacker who successfully exploits this vulnerability can view sensitive information and make changes to the disclosed information. The vulnerability affects SharePoint server Subscription Edition, SharePoint Server 2019 and SharePoint Server 2016. A risk-based prioritization methodology warrants treating this vulnerability as a higher severity than the vendor rating or CVSS score assigned.</p>

<h2>Microsoft’s publicly disclosed vulnerabilities</h2>

<p>Microsoft resolved an Elevation of Privilege Vulnerability in Microsoft Defender (<a href="https://msrc.microsoft.com/update-guide/vulnerability/CVE-2026-33825" rel="noopener" target="_blank">CVE-2026-33825</a>). The vulnerability is rated Important by Microsoft and has a CVSS v3.1 score of 7.8, but has been publicly disclosed. The CVE lists exploit code maturity as Proof-of-Concept which puts this at a higher risk of exploitation. An attacker could use this vulnerability to allow an authorized attacker to elevate their privileges to SYSTEM on the local machine.</p>

<h2>Ivanti security advisories</h2>

<p>Ivanti has released one security update for April. The update affects Ivanti Neurons for ITSM and resolves two CVEs. More details and information about mitigations can be found in the&nbsp;<a href="https://www.ivanti.com/blog/april-2026-security-update">April Security Advisory</a>.&nbsp;</p>

<h2>Third-party vulnerabilities</h2>

<p>Adobe has released twelve updates this month, eleven of which released on Patch Tuesday and the zero-day update for Acrobat that released on Friday, April 10. 54 CVEs were resolved with a breakdown of 39 Critical, 13 Important and 2 Moderate. APSB26-43 resolved the zero-day exploit (<a href="https://helpx.adobe.com/security/products/acrobat/apsb26-43.html" rel="noopener" target="_blank">CVE-2026-34621</a>).</p>

<h2>April update to-do list</h2>

<ul>
	<li>Adobe Acrobat (<a href="https://helpx.adobe.com/security/products/acrobat/apsb26-43.html" rel="noopener" target="_blank">CVE-2026-34621</a>) and Google Chrome (CVE-2026-5281) each had zero-day exploits leading up to Patch Tuesday. Ensure that you are prioritizing remediation of these two products to the latest version.</li>
	<li>Microsoft SharePoint includes a zero-day exploit (<a href="https://msrc.microsoft.com/update-guide/vulnerability/CVE-2026-32201" rel="noopener" target="_blank">CVE-2026-32201</a>) and should be investigated as a priority especially if you have known update challenges with your SharePoint environments.</li>
	<li>The Microsoft Windows OS update this month resolves 133 CVEs (depending on edition) and includes 4 Critical CVEs. This update will resolve a significant number of findings across your environment.</li>
</ul>
