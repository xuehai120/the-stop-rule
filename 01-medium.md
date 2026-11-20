# The Part of Pentesting Nobody Writes Down: Knowing When to Stop

*Subtitle: A free, source-mapped method for scope, refusal and a reviewer-ready record.*
*Platform: Medium · Voice: personal blog · Source: Publishing_Kit.md v1.3*

---

I've sat in enough reviews to notice a pattern: the hardest question is almost never "did you find the thing?" It's "can you show where you stopped, and why?"

Most writeups are great at the finding part. Almost none of them cover the part that actually keeps an engagement defensible — the scope gate before you start, the point where you decide "enough, stop," and a record a second person can read without you in the room.

So I wrote that part down, and I'm giving it away free.

The first habit is boring but it does the most work: decide the boundary before you touch anything. If a target isn't written in scope, it's out. No "just this once," no "we were only checking." Turning something down isn't the method failing — it's the method working.

The second is stop at proof. For each kind of finding, decide ahead of time what's enough to show it's real, and stop there. Going further doesn't make the work more defensible. It just creates more exposure and a longer story you have to explain later.

The third one surprised me the most when I started doing it: write down what you ruled out. A record that shows what you eliminated is far more credible than one that only lists what you found. Facts in one column, hypotheses in another, ruled-out in a third — suddenly "we were careful" becomes something a reviewer can actually check instead of just take on faith.

None of this is my invention. It maps to frameworks you can look up yourself: NIST SP 800-115, OWASP WSTG/ASVS and the LLM Top 10, MITRE CWE/ATT&CK, and FIRST CVSS v4.0. Every card points to a public reference. That's deliberate — you should be able to check the method, not trust me on it.

One thing I want to be clear about: this is for defensive, educational use only. No real targets, no working payloads, no legal text for any specific jurisdiction. It's a way to do authorized work you can defend, nothing more.

The whole method is public and free to read: https://friendly-skiff-f57.notion.site/ — the SOP, mapping cards, update policy and change log are all there, no paywall on the reading. The paid part is only the fill-in sheets people actually use mid-engagement.

If you run tests yourself, I'm curious — how do you record the "we stopped here" decision today? A proper form, or still pieced together from memory afterward?
