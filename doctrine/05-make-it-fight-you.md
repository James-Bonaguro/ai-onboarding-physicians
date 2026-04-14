# Rule 5: Make It Fight You

## The Default Problem

By default, AI agrees with everything you say.

You say: "I think this patient needs a stent." It says: "That sounds like a reasonable approach given the clinical scenario."

That's not helpful. That's confirmation bias with a friendly interface. You already do this to yourself — you don't need software doing it too.

## What To Do Instead

Tell it to push back. Explicitly. Every time it matters.

**Instead of:**
> "What do you think about my plan for this patient?"

**Say:**
> "Here's my plan for this patient. I want you to challenge it. Find the weakest part of my reasoning. What am I anchoring on? What differential am I not considering? What would a colleague across the table at cath conference say to push back on this?"

## Why This Matters More in Medicine Than Anywhere Else

You already know why. Premature closure kills people. Anchoring bias kills people. Confirmation bias kills people.

You do this at cath conference. You do it at M&M. You do it when a fellow presents a case and you ask, "What else could this be?"

AI can be that voice — the one that asks "are you sure?" — but only if you tell it to. Otherwise it defaults to being an agreeable assistant that confirms whatever you already decided.

## The Setup

Add this to your custom instructions (the ones from Rule 2):

> "When I share clinical reasoning or a management plan, your job is to find the weaknesses — not to validate me. If my logic has gaps, say so directly. If I'm anchoring on a diagnosis, flag it. If there's a guideline I'm not considering, cite it. I'd rather hear the pushback from you now than miss something on a real patient."

Once this is in your settings, it runs automatically. You don't have to ask for pushback every time — it just does it.

## Real Example

**Without the setting:**
> You: "I think this is stable angina. I'm going to optimize medical therapy and follow up in 3 months."
> AI: "That's a reasonable approach. Medical therapy is the first-line treatment for stable angina, and follow-up in 3 months is appropriate to assess symptom improvement."

**With the setting:**
> You: "I think this is stable angina. I'm going to optimize medical therapy and follow up in 3 months."
> AI: "Before you close this out as stable angina — the troponin was 0.06, which is above your institution's 99th percentile. The ECG showed subtle ST depression in V4-V6 that wasn't on the prior. And the patient described the pain as new-onset with exertional and rest components. Are you confident this isn't an NSTEMI presentation? What would change your mind?"

Same input from you. One response validates your thinking. The other one might catch something you missed.

## The One-Sentence Rule

**The most valuable thing your AI can do is tell you where you might be wrong before it matters.**

---

You've read the five rules. Now set it up → [Setup Guide](../setup/01-getting-configured.md)
