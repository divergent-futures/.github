Security policy

## Reporting a vulnerability

**Email [tj@divergentfutures.co](mailto:tj@divergentfutures.co).** Don't open apublic issue for a security problem.

Include what you found, how to reproduce it, and what an attacker could do withit. If you're not sure whether something counts, report it anyway — a falsealarm costs a few minutes, a missed one doesn't.

You'll get an acknowledgement within a few days. These are small projectsmaintained by one person, so a full fix may take longer than that; you'll betold where it stands rather than left waiting.

If you'd like credit in the fix, say so and you'll get it. If you'd rather stayanonymous, that's fine too.

## What's in scope

Anything in this organisation's repositories. In practice that means:

* **Desktop and web applications** (`pulse`, `writers-codex`) — the usual:arbitrary code execution, data exfiltration, anything that breaks thelocal-only promise these tools make. That promise is the product, so a wayaround it is a serious bug.
* **Websites** (`divergent-futures-web`) — static sites on Cloudflare Pages.Limited attack surface, but content injection or a broken security header isworth reporting.
* **Build tooling** — supply-chain issues, compromised dependencies.

## What isn't

* **Physical safety issues in the hardware designs are not security bugs — butthey matter more.** If you spot something dangerous in `slipstream` or`divergent-house-bus` — a battery configuration that can go into thermalrunaway, an exhaust routing that can put carbon monoxide somewhere peoplesleep, an electrical design that can't be isolated safely — **open a publicissue.** These are unbuilt designs published for review, and the entire pointof publishing them early is that someone qualified catches the problem beforeanyone builds it. Public is better than private here: other people reading thedesign need to see the objection too.
* Missing hardening on a static site with no accounts and no user data.
* Automated scanner output with no demonstrated impact.

## No bounty

There's no money. There's genuine thanks, credit if you want it, and a fix.
