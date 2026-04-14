# Examples: Before vs. After

## Why This Matters

Every example below shows the same physician asking the same question. The only difference is whether their AI was configured using the setup guide or not.

---

## Example 1: Pre-Procedure Planning

### Before (default AI):

**You:** "Tell me about TAVR."

**AI:** "Transcatheter aortic valve replacement (TAVR) is a minimally invasive procedure used to treat aortic stenosis. It involves inserting a new valve through a catheter, typically via the femoral artery. TAVR has become an established alternative to surgical aortic valve replacement for patients at intermediate to high surgical risk. The procedure was first approved by the FDA in 2011..."

*A Wikipedia article. You could have Googled this. Completely useless for planning a case.*

### After (configured AI):

**You:** "I have a TAVR case tomorrow. 82-year-old, severe AS with a mean gradient of 48, valve area 0.7. CT shows a bicuspid valve with heavy calcification, annulus 26mm, and moderate iliofemoral tortuosity. STS score is 5.1. Help me think through this."

**AI:** "A few things to work through:

1. **Valve sizing** — 26mm annulus with a bicuspid morphology. You're in the range where both the Sapien 3 Ultra 26mm and the Evolut FX 29mm could work. The heavy calc with bicuspid anatomy raises the paravalvular leak risk — the self-expanding platform may conform better, but the calcification pattern matters. What does the calcium distribution look like on the CT — is it symmetric or heavily lateralized?

2. **Access** — moderate iliofemoral tortuosity with what vessel diameters? If the minimum diameter is above 5.5mm you're likely fine for transfemoral with either platform, but the tortuosity might favor a lower-profile delivery system. Have you looked at the alternative access CT if TF isn't clean?

3. **Bicuspid-specific risk** — the BAVARD registry data shows higher rates of paravalvular leak and need for a second valve in bicuspid anatomy. Are you planning intraprocedural TEE or is this ICE-guided?

What's the access vessel sizing showing?"

*It's thinking like a colleague preparing for the same case. You can actually use this.*

---

## Example 2: Writing a Discharge Summary

### Before (default AI):

**You:** "Write a discharge summary for a patient who had a stent placed."

**AI:** "Discharge Summary

Patient Name: [Name]
Date of Admission: [Date]
Date of Discharge: [Date]

Chief Complaint: Chest pain

Hospital Course: The patient was admitted with chest pain and underwent cardiac catheterization, which revealed coronary artery disease. A stent was successfully placed. The patient tolerated the procedure well and is being discharged in stable condition.

Discharge Medications: [List medications]
Follow-up: Follow up with cardiologist in 2-4 weeks."

*A form letter. Missing everything that matters for the next physician who reads this.*

### After (configured AI):

**You:** "Draft a discharge summary. Patient presented with NSTEMI, troponin peaked at 8.4. Cath showed 95% mid-LAD with TIMI 1 flow. I did rotational atherectomy with a 1.5mm burr, predilated with 2.5mm NC balloon, and placed a 3.0 x 38mm Xience DES. Excellent result, TIMI 3 flow. No complications. Radial access, TR band off at 4 hours. Discharge on aspirin 81, Plavix 75, atorvastatin 80, metoprolol succinate 50."

**AI:** "**Discharge Summary**

**Presentation:** Admitted with acute NSTEMI. Troponin I peaked at 8.4 ng/mL. ECG showed [you'd fill in]. Symptoms: [you'd fill in].

**Hospital Course:** Diagnostic coronary angiography via right radial access demonstrated a high-grade (95%) stenosis of the mid-left anterior descending artery with TIMI 1 flow. Remaining coronary anatomy: [fill in RCA, LCx findings].

Ad hoc PCI was performed on the mid-LAD lesion. Due to heavy calcification, rotational atherectomy was performed with a 1.5mm burr. The lesion was predilated with a 2.5mm non-compliant balloon, followed by deployment of a 3.0 x 38mm Xience drug-eluting stent. Final angiography showed excellent result with TIMI 3 flow, 0% residual stenosis, no dissection, and no distal embolization.

Access site: Right radial artery. Hemostasis achieved with TR Band, removed at 4 hours without complication.

**Complications:** None.

**Discharge Medications:**
- Aspirin 81mg daily — **indefinitely**
- Clopidogrel 75mg daily — **minimum 12 months** (do not discontinue without cardiology consultation)
- Atorvastatin 80mg daily
- Metoprolol succinate 50mg daily

**Critical Instruction for Patient and PCP:** Dual antiplatelet therapy (aspirin + clopidogrel) must not be stopped or interrupted for 12 months without contacting the interventional cardiologist. Premature discontinuation risks stent thrombosis, which is a life-threatening emergency.

**Follow-up:**
- Cardiology: 2 weeks post-discharge
- Cardiac rehabilitation referral: pending
- Labs: Fasting lipid panel and LFTs in 6 weeks

**Red Flags — Seek Immediate Care If:**
- Chest pain similar to presentation
- Bleeding from access site
- Arm numbness, weakness, or color change (radial access)
- Shortness of breath or syncope"

*Structured, billable, clinically complete. The DAPT warning alone could prevent a life-threatening event.*

---

## Example 3: Journal Club Preparation

### Before (default AI):

**You:** "Summarize the ISCHEMIA trial for me."

**AI:** "The ISCHEMIA trial (International Study of Comparative Health Effectiveness with Medical and Invasive Approaches) was a landmark randomized controlled trial that compared an initial invasive strategy with an initial conservative strategy in patients with stable ischemic heart disease and moderate-to-severe ischemia. Published in 2020, the trial enrolled 5,179 patients across 320 sites..."

*A summary you could find anywhere. Not useful for presenting at journal club.*

### After (configured AI):

**You:** "I'm presenting ISCHEMIA at journal club next Thursday. I need to build a critical appraisal, not just a summary. Help me prepare."

**AI:** "Here's a framework for your presentation:

**The headline:** No mortality or MI benefit with routine invasive strategy over conservative management in stable ischemic heart disease with moderate-to-severe ischemia. Invasive strategy improved angina symptoms.

**Three strong critiques to present:**

1. **Crossover problem** — 28% of the conservative arm crossed over to PCI/CABG during follow-up. This dilutes the treatment effect. If a quarter of your control group got the intervention, you're not really testing what you think you're testing.

2. **Excluded the highest-risk patients** — left main disease (>50%) was excluded by CCTA upfront. These are arguably the patients most likely to benefit from revascularization. The trial answers the question for everyone *except* the group where you'd most want the answer.

3. **Symptom endpoint was significant** — quality of life and angina frequency improved meaningfully in the invasive arm. For interventionalists, this is the counterargument: your patient sitting in front of you with limiting angina on max medical therapy cares about symptoms, not just hard endpoints.

**The question your audience will ask:**
'So should we stop doing PCI for stable disease?'

Your answer: ISCHEMIA says don't rush to the cath lab for prognostic benefit. But it doesn't say PCI is useless — it says the *timing* and *indication* matter. Symptoms refractory to medical therapy remain a valid indication. And the left main exclusion means you still cath patients where you suspect left main disease.

**What to prepare for pushback:**
An interventional colleague will cite FAME 2 (FFR-guided PCI reduced urgent revascularization) and argue that ISCHEMIA's anatomy was mixed. A medical therapy advocate will cite COURAGE and BARI-2D as consistent with ISCHEMIA. Know both sides.

Want me to draft the slide outline or go deeper on any of these points?"

*That's a presentation framework, not a summary. You could walk into journal club with this.*

---

## Example 4: Prior Authorization Appeal

### Before (default AI):

**You:** "Help me write a prior auth letter."

**AI:** "Dear [Insurance Company],

I am writing to request prior authorization for [procedure] for my patient [name]. This procedure is medically necessary due to the patient's condition. The patient has been evaluated and it has been determined that this procedure is the most appropriate course of treatment..."

*Instant denial. This letter says nothing.*

### After (configured AI):

**You:** "I need a prior auth appeal for PCI with DES. Patient is a 68-year-old with CCS Class III angina despite max medical therapy — on metoprolol 200, amlodipine 10, and isosorbide mononitrate 60. Stress test showed large anterior wall ischemia. Cath showed 90% mid-LAD. Insurance denied saying 'medical necessity not established.' I need to cite the appropriate use criteria."

**AI:** "**Prior Authorization Appeal — Percutaneous Coronary Intervention with Drug-Eluting Stent**

Dear Medical Director,

I am writing to appeal the denial of PCI with drug-eluting stent placement for this patient on the basis that medical necessity is clearly established by both clinical presentation and published appropriate use criteria.

**Clinical Summary:**
This is a 68-year-old patient with CCS Functional Class III angina that is **refractory to maximally titrated medical therapy**, including metoprolol succinate 200mg daily, amlodipine 10mg daily, and isosorbide mononitrate 60mg daily. Despite this regimen, the patient reports daily angina with minimal exertion, significantly limiting functional capacity and quality of life.

**Objective Evidence:**
Stress myocardial perfusion imaging demonstrates a **large area of reversible ischemia involving the anterior wall**, indicating significant jeopardized myocardium. Diagnostic coronary angiography reveals a **90% stenosis of the mid-left anterior descending artery**, which is the culprit vessel consistent with the ischemic territory.

**Appropriate Use Criteria:**
Per the **2017 ACC/AHA/SCAI Appropriate Use Criteria for Coronary Revascularization** (JACC 2017;69:2212-2241):

- **Scenario: 1- or 2-vessel CAD with significant proximal LAD stenosis, CCS Class III symptoms on maximal medical therapy, with noninvasive evidence of ischemia** → **Appropriateness Rating: Appropriate (Score 7-9)**

This clinical scenario meets the highest appropriateness designation for PCI. The patient has failed adequate medical therapy, has objective evidence of significant ischemia, and has an anatomically suitable lesion for percutaneous intervention.

**Recommendation:**
I respectfully request that this denial be reversed. The clinical evidence and published appropriate use criteria unequivocally support PCI with DES as medically necessary in this case.

I am available for peer-to-peer discussion at your convenience.

Sincerely,
[Your name, credentials]"

*Cites the specific AUC, maps the clinical scenario to the criteria, and gives the medical director no room to argue. This is a 5-minute draft instead of a 20-minute headache.*

---

## The Pattern

Notice what's the same across every example:

1. The configured AI knows your context — so it skips the textbook intro
2. It writes for your actual workflow — not for a student
3. It challenges your thinking — instead of agreeing with everything
4. It suggests next steps — because it understands how your work flows

This is what the five rules and the setup create. Not better prompts. Better infrastructure.

---

Next → [Your First Week](../getting-started/01-your-first-week.md)
