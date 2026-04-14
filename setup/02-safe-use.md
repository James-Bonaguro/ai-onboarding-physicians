# Safe Use: HIPAA, Patient Data, and Common Sense

## The Bright Line

**Never put protected health information (PHI) into consumer AI tools.**

ChatGPT, Claude, Gemini — on your personal account, these are consumer products. They are not covered by a Business Associate Agreement (BAA). Anything you type into them could be stored, used for training, or potentially exposed. This is not a gray area.

If you remember one thing from this page: **no patient identifiers, ever.**

## What Counts as PHI

HIPAA defines 18 types of identifiers. The ones most likely to end up in an AI conversation:

- **Names** — patient, family members, referring physicians in context
- **Dates** — admission, procedure, birth dates
- **Ages over 89**
- **Medical record numbers or account numbers**
- **Locations** — addresses, specific hospital names in combination with clinical details
- **Phone numbers, email addresses, SSN**
- **Any detail that could identify a specific person**

## The Green / Yellow / Red Framework

**Green — Always safe to use with consumer AI:**
- Literature questions: "What does the ISCHEMIA trial show about stable angina?"
- Guideline interpretation: "Walk me through the ACC/AHA Class I recommendations for DAPT duration."
- Teaching prep: "Help me build a journal club presentation on the PARTNER 3 trial."
- Administrative templates: "Draft a template for a prior authorization letter for drug-eluting stents."
- Research design: "Help me think through a study design comparing two access strategies for TAVR."
- General clinical reasoning: "How do you approach anticoagulation in a patient with AFib and recent GI bleed?" (no specific patient details)

**Yellow — Safe only if you de-identify first:**
- Clinical scenarios for decision support: Change the age (slightly), remove dates, change gender if not clinically relevant, remove all names and locations
- Documentation drafts: Use "a patient" not "my patient," strip all identifying details
- Case presentations: De-identify before pasting into AI

**Red — Never do this:**
- Copy-pasting from the EHR directly into ChatGPT or Claude
- Uploading clinical documents with patient identifiers
- Dictating patient names, MRNs, or dates of birth into AI voice mode
- Sharing imaging with embedded patient data (DICOM headers contain PHI)

## How to De-Identify for AI Use

When you want to think through a clinical scenario with AI, use this checklist:

1. **Change the age** — shift by a few years (make 67 into "a patient in their late 60s" or just say 65)
2. **Remove all dates** — say "6 months ago" instead of "October 2025"
3. **Remove names** — use "the patient" or "a 65-year-old"
4. **Remove locations** — no hospital names, no cities in combination with clinical details
5. **Remove MRN, account numbers, SSN** — obviously
6. **Ask yourself:** Could anyone reading this identify the patient? If yes, strip more.

## What About Institutional AI Tools?

Some hospitals now offer AI tools covered by a BAA:
- **Epic AI / ambient documentation tools** (Nuance DAX, etc.)
- **Microsoft 365 Copilot** on institutional accounts
- **Vendor-specific tools** approved by your IT/compliance team

These are different. They have data governance, audit trails, and legal agreements in place. If your institution offers these, use them for anything involving patient data.

**Before you start using consumer AI for anything clinical, ask your institution:**
1. Do we have an AI use policy?
2. Are there approved AI tools for clinical use?
3. What's the policy on de-identified data in consumer AI tools?

## The Decision Tree

Before typing anything into ChatGPT or Claude, ask:

1. **Does this involve a specific patient?** → If no, you're fine. If yes, go to 2.
2. **Can I fully de-identify it?** → If yes, de-identify and proceed. If no, go to 3.
3. **Does my institution have an approved AI tool for this?** → If yes, use that. If no, don't use AI for this task.

## The Bottom Line

AI is incredibly useful for physicians. Literature review, teaching, documentation templates, clinical reasoning practice, administrative work — all fair game. Just keep patient identifiers out of consumer tools.

This isn't about fear. It's about being smart with a powerful tool.

---

Next → [Examples: Before vs. After](../examples/01-before-vs-after.md)
