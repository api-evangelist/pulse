---
title: "We’re in a Patch Apocalypse. That Means These Three IT Excuses Won’t Work Anymore."
url: "https://www.ivanti.com/blog/patch-apocalypse"
date: "Wed, 29 Apr 2026 14:00:07 Z"
author: "Chris Goettl"
feed_url: "https://www.ivanti.com/blog/rss"
---
<p>On April 7, Anthropic announced that its Claude Mythos Preview model had autonomously identified thousands of high- and critical-severity zero-day vulnerabilities across every major operating system and every major web browser. Over 99% of them were unpatched the day of disclosure.</p>

<p>Two weeks later, on April 21, Mozilla said it had used the same model to find and patch 271 vulnerabilities in the latest Firefox release. Mozilla's own assessment: "So far we've found no category or complexity of vulnerability that humans can find that this model can't."</p>

<p>271 is the first wave. Chrome, Edge, Windows, macOS, Linux, FreeBSD — the 17-year-old remote code execution flaw in FreeBSD that Anthropic's red team disclosed (CVE-2026-4747) is an early example of what's coming. Every vendor under Anthropic's Project Glasswing umbrella is positioned to ship fixes at a tempo the industry hasn't seen before. All those fixes become public CVEs with patches available, which lands them in the same place: your environment.</p>

<p>The containment story also has a crack. On April 21, <a href="https://www.bloomberg.com/news/articles/2026-04-21/anthropic-s-mythos-model-is-being-accessed-by-unauthorized-users" rel="noopener" target="_blank">Bloomberg reported</a> that a Discord-linked group gained unauthorized access to Mythos through a third-party vendor environment. Anthropic says the activity didn't extend beyond that vendor. Whether or not similar capability is already in attacker hands, the defensive runway is shorter than the April 7 announcement implied.</p>

<p>Mythos entered a world already trending this way. <a href="https://www.crowdstrike.com/en-us/global-threat-report/" rel="noopener" target="_blank">CrowdStrike's 2026 Global Threat Report</a> documented an 89% year-over-year rise in AI-enabled attacks in 2025. That trend line predates Mythos.</p>

<p><strong>Call this a patch apocalypse</strong>. The plain operational kind, where the volume and cadence of public CVEs with available patches is about to outrun how most IT and security teams currently work.</p>

<p>NIST is already feeling the effects of the patch apocalypse. In April, the agency announced a major shift in the National Vulnerability Database (NVD) operations in response to a 263% surge in submissions. NIST will no longer provide detailed enrichment to all vulnerabilities submitted, and will instead only provide this for vulnerabilities that meet a high-risk criteria, such as those in the CISA Known Exploited Vulnerabilities catalog or those affecting critical government software. NIST will be relying on CVE Number Authorities (CNAs), like Ivanti, rather than performing its own independent assessment.</p>

<p>I've been hearing three versions of the same response from customers and peers since the announcement. All three are variations of a program designed for a slower world.</p>

<h2 id="toc_1">“We have a vulnerability scanner”</h2>

<p>Qualys, Rapid7 and Tenable do vulnerability discovery well. Scanners find, flag, score and list. Deployment, verification, reboot handling and rollback are outside their scope. That work still has to happen somewhere. In most programs it happens in a separate tool, with a separate team, on a separate cadence.</p>

<p>With the exploit window now running in hours and the Glasswing queue about to double the backlog, a scanner that produces 587 critical vulnerabilities and hands the list to a human team is a liability. The practical move is to connect the scanner you already own to a remediation engine that can act on its findings automatically. An <a href="https://www.ivanti.com/autonomous-endpoint-management">autonomous endpoint management</a> (AEM) platform, with ring-based deployment and rollback, and vulnerability intelligence to provide risk-based context for efficient remediation decisions so the list shrinks without a humans making every decision.</p>

<h2 id="toc_2">“We drive approvals through our ticketing system”</h2>

<p>Speaking of humans having to make decisions… Long linear approval processes are going to slow the remediation process significantly. When is the last time you had to decide whether you were going to deploy the latest OS or browser update?</p>

<p>Organizations already know they are going to deploy these updates. Often the approval process is due to complex internal politics and misalignment on security outcomes. The end result? A very linear process that requires the vulnerability scanner previously mentioned, an analyst approving what you already know needs to be done, tickets going out to business owners for approval and sitting in inboxes waiting for approval, and ultimately valuable time wasted on a decision that was essentially already well understood and did not need to be made.</p>

<p>The market shift to <a href="https://www.ivanti.com/exposure-management">Exposure Management</a> is approaching this process very differently by focusing on defining an organizations risk-appetite and monitoring risk-posture. Next time a Windows OS update releases you already know you will deploy it, the schedule you will deploy it on and your SLA and compliance metrics you will measure success by. What you really want to know is:</p>

<p>1. Do I need to move faster because the update includes known exploited vulnerabilities?</p>

<p>Or</p>

<p>2. Is the update impacting operations and we need to slow down (good thing the Autonomous Endpoint Management platform includes ring deployment with rollback)?</p>

<h2 id="toc_3">“We have Intune”</h2>

<p>Microsoft Intune has two scope limits that matter here.</p>

<p>First, it only manages devices enrolled with it. Unenrolled and unmanaged endpoints — servers, contractor laptops, shadow IT, neglected edge devices — sit outside its visibility entirely. During periods of increased vulnerability volume, those blind spots multiply faster than teams can handle manually.</p>

<p>Second, while Intune simplifies application deployment and updates, its third-party application coverage and prioritization depth are narrower than most administrators realize. Intune can tell you <em>what’s out of date</em>, but not <em>what actually increases your exposure</em>––which forces teams to patch everything reactively, or based on guesswork when time is scarce.</p>

<p>Most enterprise environments aren’t exclusively Windows, fully enrolled, or running a small, homogenous app stack. When vulnerability disclosures spike, routing patching leaves gaps and turns into systemic risk.</p>

<p>Keep Intune. Pair it with a discovery and remediation layer that finds the assets Intune can't see, prioritizes the vulnerabilities that matter most, and applies patches with confidence across the applications Intune doesn’t cover.</p>

<h2 id="toc_4">What to do about it</h2>

<p>Automation is the operating model. It has to be built into the workflow.</p>

<p>Practitioners have known the principle for a while. It shows up in three places:</p>

<ul>
	<li><strong>Continuous triage.</strong> Known exploited vulnerabilities can follow a zero-day response track especially in less secure parts of the organization like end user systems. Above that, set and define specific applications like the browsers and telecommunication apps to get updated on a priority track that is checked weekly or even daily. Everything else can wait for the regularly maintenance window to come around.</li>
	<li><strong>Ring deployment with automated rollback.</strong> Test ring, early-adopter ring, broad production, mission-critical. The sequence is boring and it works for most maintenance. What's changed is that certain updates will need to compress to fit the exploit window vs waiting for your monthly maintenance. The test ring has to be automated and instrumented — a human checklist can't move that fast.</li>
	<li><strong>Closed-loop verification.</strong> The patch isn't deployed until it's verified installed on the endpoint, and the CVE isn't closed until a rescan confirms it. Most teams skip that step, which is why compliance evidence becomes a fire drill the week before the audit. That's why we shipped continuous compliance in our platform this week — so compliance evidence is produced continuously and automatically as patches deploy, with automation handling the prioritization decisions most teams don't have bandwidth for.</li>
</ul>

<p>Mozilla's 271 Firefox vulnerabilities are a preview. Every major software vendor under Glasswing is about to startfixing more vulnerabilities and at an accelerated pace, and attackers with the same class of capability will be looking for exactly those openings whenever they gain access to a model like it. The resulting AI arms race will have a direct affect on the number and frequency of updates that organizations will have to remediate and at an accelerated pace. Automation is what carries a program through. Teams still doing monthly-only patching are in for a rough stretch.</p>

<p>If you run an IT or security program, the self-assessment is worth doing now. Take the last critical patch you pushed out. Even better, if a zero-day came out on a Friday would you be able to remediate it by Monday? Time it from CVE publication to verified install on the last endpoint. If that number is measured in weeks, the patch apocalypse is going to find you.</p>
