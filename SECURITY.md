Security policy
Reporting a vulnerability

Email tj@divergentfutures.co. Don't open a public issue for a security problem.

Include what you found, how to reproduce it, and what an attacker could do with it. If you're not sure whether something counts, report it anyway — a false alarm costs a few minutes, a missed one doesn't.

You'll get an acknowledgement within a few days. These are small projects maintained by one person, so a full fix may take longer than that; you'll be told where it stands rather than left waiting.

If you'd like credit in the fix, say so and you'll get it. If you'd rather stay anonymous, that's fine too.

What's in scope

Anything in this organisation's repositories. In practice that means:

Desktop and web applications (pulse, writers-codex) — the usual: arbitrary code execution, data exfiltration, anything that breaks the local-only promise these tools make. That promise is the product, so a way around it is a serious bug.
Websites (divergent-futures-web) — static sites on Cloudflare Pages. Limited attack surface, but content injection or a broken security header is worth reporting.
Build tooling — supply-chain issues, compromised dependencies.
What isn't
Physical safety issues in the hardware designs are not security bugs — but they matter more. If you spot something dangerous in slipstream or divergent-house-bus — a battery configuration that can go into thermal runaway, an exhaust routing that can put carbon monoxide somewhere people sleep, an electrical design that can't be isolated safely — open a public issue. These are unbuilt designs published for review, and the entire point of publishing them early is that someone qualified catches the problem before anyone builds it. Public is better than private here: other people reading the design need to see the objection too.
Missing hardening on a static site with no accounts and no user data.
Automated scanner output with no demonstrated impact.
No bounty

There's no money. There's genuine thanks, credit if you want it, and a fix.
