<a href="https://www.linkedin.com/in/ammar-alkazaz/">
  <img src="https://raw.githubusercontent.com/ammar-alkazaz/ammar-alkazaz/main/assets/banner.jpg" alt="A business view of growth. Connecting strategy, marketing and sales." width="100%" />
</a>

<h1 align="center">Ammar Alkazaz</h1>

<p align="center"><strong>Marketing Growth Strategist</strong><br />Paid media, lead generation, marketing automation and content systems, built to run with minimal human touch.</p>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://readme-typing-svg.demolab.com/?font=Fira+Code&size=19&pause=1100&color=BCA7C5&center=true&vCenter=true&width=780&lines=A+business+view+of+growth;Marketing+systems+that+run+with+minimal+human+touch;Outbound+that+fires+on+buying+signals%2C+not+volume;AI+drafts.+A+human+approves.+Code+enforces+the+rules.;Paid+media+with+tracking+that+survives+the+redirect;Content+systems+a+new+hire+can+run+on+day+one" />
    <img src="https://readme-typing-svg.demolab.com/?font=Fira+Code&size=19&pause=1100&color=231628&center=true&vCenter=true&width=780&lines=A+business+view+of+growth;Marketing+systems+that+run+with+minimal+human+touch;Outbound+that+fires+on+buying+signals%2C+not+volume;AI+drafts.+A+human+approves.+Code+enforces+the+rules.;Paid+media+with+tracking+that+survives+the+redirect;Content+systems+a+new+hire+can+run+on+day+one" alt="What I build" />
  </picture>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/ammar-alkazaz/"><img src="https://img.shields.io/badge/LinkedIn-ammar--alkazaz-64476F?style=for-the-badge&labelColor=231628&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:ammarahmed067@gmail.com"><img src="https://img.shields.io/badge/Email-ammarahmed067%40gmail.com-64476F?style=for-the-badge&labelColor=231628&logo=gmail&logoColor=white" alt="Email" /></a>
  <img src="https://img.shields.io/badge/Cairo%2C%20Egypt-Remote%20on%20US%2C%20UK%20and%20EU%20hours-364FCF?style=for-the-badge&labelColor=231628" alt="Cairo, Egypt. Remote on US, UK and EU hours" />
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/ammar-alkazaz/ammar-alkazaz/main/assets/status.svg" alt="Open to remote marketing roles. US, UK and EU hours." />
</p>

I build the systems behind the numbers. Paid media, lead generation, marketing automation and content systems, with enough engineering discipline that they keep running when I step away.

Most recently I was the sole marketer for a US web design and development agency, remote on US Eastern hours. I built its marketing infrastructure from zero, documented every system as a playbook, and handed it over to the people who run it now. Before that I ran my own B2C digital marketing agency and spent several years in sales development, which is why everything I build starts from what a salesperson can actually close.

<img src="https://raw.githubusercontent.com/ammar-alkazaz/ammar-alkazaz/main/assets/divider.svg" alt="" width="100%" />

## How I build a growth system

<p align="center">
  <img src="https://raw.githubusercontent.com/ammar-alkazaz/ammar-alkazaz/main/assets/pipeline.svg" alt="Signals, score, human gate, enrich and verify, sequence, replies" width="100%" />
</p>

This is the shape of the outbound engine I built and handed over at my last role, drawn here as a public architecture. The written version, with the evidence rules, the gate thresholds and the sending guardrails, is in the [signal-based outbound playbook](https://github.com/ammar-alkazaz/marketing-automation-playbooks/blob/main/08-signal-based-outbound-architecture.md).

## What I build

- Lead generation funnels on Meta Ads and Google Ads, with conversion tracking and attribution that survive redirects and form plugins.
- CRM automation in GoHighLevel. Lead capture from several intake points, validity checks, scoring, routing, speed-to-lead call and SMS steps, pipeline updates and alerts.
- Workflow automation on n8n and Make, webhooks and REST APIs, PostgreSQL, Python scripting, Linux server operations.
- Outbound engines that trigger on buying signals rather than volume, with verification, cadence, cooldown, opt-out and compliance rules enforced in code, and bounce guardrails that stop sending before deliverability is hurt.
- Content systems for founders and company pages. Voice guides, verified fact banks, posting calendars, short-form video pipelines and the playbooks that let a new hire take over.
- Video and visual production. Editing in DaVinci Resolve and CapCut, motion and graphics in After Effects, Photoshop and Lightroom, AI video and voice with HeyGen, ElevenLabs, Higgsfield, Veo and Kling.

## Marketing is becoming an operations discipline

The campaigns are no longer the hard part. The hard part is the system around them, and that is where I spend my time.

- **AI drafts, people decide.** Claude and ChatGPT write first drafts against a verified fact bank. A human approves, and every decision is stored as a label so the system can measure its own precision.
- **Rules live in code, not in memory.** Cadence, cooldown, opt-out, bounce thresholds and sending hours are enforced by the system, so quality does not depend on who is on shift.
- **AI agents on production, under supervision.** I run Claude Code as a reviewer and supervised operator on a live Linux server, with versioned releases, automated tests and an adversarial AI review before anything ships.
- **Playbooks become skills.** Every system I build is documented as a playbook. The copywriting playbook I wrote at my last role became a reusable AI skill that the next marketer inherited on day one.
- **Measure what survives.** Tracking parameters, pixels and forms get checked by a script, not by hope. Two of those scripts are in this profile.

## What is in this profile

Client work is under NDA, so nothing here is copied from a client environment. The repositories are rebuilt from scratch as reusable templates and small tools.

- [marketing-automation-playbooks](https://github.com/ammar-alkazaz/marketing-automation-playbooks). The systems I build, written as playbooks you can copy. Lead scoring and routing, speed-to-lead, cold email deliverability guardrails, paid media QA, attribution audits, scorecards, content system templates and a signal-based outbound architecture.
- [tracking-param-checker](https://github.com/ammar-alkazaz/tracking-param-checker). A small Python tool that follows a landing page's redirect chain and reports whether gclid, fbclid and UTM parameters survive to the final page, plus whether Google Tag Manager and GA4 tags are present.
- [form-health-check](https://github.com/ammar-alkazaz/form-health-check). A daily check that a landing page still loads, still has its form and its tracking tags, with an optional Slack alert. Built because a broken form under live ad spend costs money every hour it goes unnoticed.

Next up, as time allows. A set of n8n workflow templates, a website change watcher that turns site changes into outbound signals, and a lead router, all rebuilt generically.

## Stack

<p align="center">
  <img src="https://raw.githubusercontent.com/ammar-alkazaz/ammar-alkazaz/main/assets/stack.svg" alt="Growth and paid media, CRM and automation, content and creative, AI in the loop, engineering" width="100%" />
</p>

## Activity

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/ammar-alkazaz/ammar-alkazaz/output/github-snake-dark.svg" />
    <img src="https://raw.githubusercontent.com/ammar-alkazaz/ammar-alkazaz/output/github-snake.svg" alt="Contribution snake" width="100%" />
  </picture>
</p>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api?username=ammar-alkazaz&show_icons=true&hide_title=true&include_all_commits=true&bg_color=231628&title_color=BCA7C5&text_color=FFF9F3&icon_color=BCA7C5&border_color=64476F&border_radius=14" />
    <img src="https://github-readme-stats.vercel.app/api?username=ammar-alkazaz&show_icons=true&hide_title=true&include_all_commits=true&bg_color=FFF9F3&title_color=231628&text_color=231628&icon_color=364FCF&border_color=BCA7C5&border_radius=14" alt="GitHub stats" height="160" />
  </picture>
</p>

## Contact

- LinkedIn: [linkedin.com/in/ammar-alkazaz](https://www.linkedin.com/in/ammar-alkazaz/)
- Email: ammarahmed067@gmail.com
- Cairo, Egypt. Remote, available on US, UK and European hours. Arabic and English native, basic French.

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:FFF9F3,50:BCA7C5,100:64476F&height=110&section=footer" alt="" width="100%" />
</p>
