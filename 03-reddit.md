# A free, source-mapped method for keeping an authorized pentest defensible

*Platform: Reddit · Suggested subs: r/netsec (primary) → r/ethicalhacking (secondary), one sub at a time · Alternate title: "The part of a pentest write-up most reports skip: where and why you stopped" · Source: Publishing_Kit.md v1.3*

---

I've sat in enough reviews to notice a pattern: the hardest question is almost never "did you find the thing?" It's "can you show where you stopped, and why?"

Most writeups nail the finding part. Almost none cover the rest — the scope gate before you start, the moment you decide "that's enough," and a record someone else can read without you in the room.

So I wrote that part down and put it out free:

- Scope gate first — if a target isn't on the written scope, it doesn't get tested. No "just this once," no "we were only checking."
- Stop at proof — enough to show an issue is real, not a working exploit.
- Write down what you ruled out — facts, guesses and dead ends in separate columns, so "we were careful" becomes something a reviewer can actually check.

None of it is my invention; it maps to frameworks you can look up yourself (NIST SP 800-115, OWASP WSTG/ASVS, MITRE CWE/ATT&CK, FIRST CVSS). Boundary I won't cross: defensive and educational only — no real targets, no working payloads, no legal text for any one country. The whole method is free to read; the paid bit is just fill-in sheets for people actually running tests.

Free library: https://friendly-skiff-f57.notion.site/

Genuine question for the sub: how do you record the "we stopped here" decision today — a proper form, or pieced together from memory afterward?
