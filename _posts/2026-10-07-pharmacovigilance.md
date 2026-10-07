---
layout: post
title:  "Pharmacovigilance: How Medicines Are Watched After Approval"
date:   2026-10-07 10:00:00
image:  pharmacovigilance.svg
tags:   [Pharmacovigilance, Drug Safety]
description: "A clinical trial can't see everything. Pharmacovigilance is the system that keeps watching once a medicine reaches millions of people, turning scattered case reports into safety signals and signals into action."
---

<p class="pv-lede">A new medicine is approved after being tested in a few thousand carefully chosen people. Then it is prescribed to millions: older patients, pregnant patients, people taking five other drugs. Pharmacovigilance is the discipline that keeps watching after approval.</p>

The World Health Organization defines it as *the science and activities relating to the detection, assessment, understanding and prevention of adverse effects or any other medicine-related problem*. Put simply, its job is to notice when something is going wrong, work out whether the medicine is the cause, and act before more people are harmed.

<div class="pv-stats">
  <div class="pv-stat"><span class="pv-stat-value">~1 in 1,000</span><span class="pv-stat-label">Roughly the rarest reaction a 3,000-patient trial can reliably detect</span></div>
  <div class="pv-stat"><span class="pv-stat-value">1968</span><span class="pv-stat-label">WHO Programme for International Drug Monitoring founded, after thalidomide</span></div>
  <div class="pv-stat"><span class="pv-stat-value">15 days</span><span class="pv-stat-label">Standard deadline to report a serious, unexpected reaction to regulators</span></div>
</div>

## Why trials aren't enough

Pre-approval trials are built to prove that a drug works. They are not built to find every way it can cause harm. They are small, short, and exclude many of the people who will eventually take the drug. Statisticians use the *rule of three*: if no event is seen in *n* patients, the true rate could still be as high as 3/*n*. With 3,000 patients, a reaction affecting 1 in 10,000 people will almost certainly go unseen.

Thalidomide showed what that gap costs. Marketed in the late 1950s as a safe sedative, it caused severe limb malformations in more than 10,000 babies before an Australian obstetrician and a German paediatrician linked the cases in 1961. Modern pharmacovigilance grew out of that failure.

## The pharmacovigilance cycle

<figure class="pv-figure">
  <svg viewBox="0 0 720 340" role="img" aria-labelledby="pv-cycle-title pv-cycle-desc">
    <title id="pv-cycle-title">The pharmacovigilance cycle</title>
    <desc id="pv-cycle-desc">Five stages in a loop: collect case reports, detect signals, assess causality, act on risk, communicate, and back to collecting.</desc>
    <defs>
      <marker id="pv-arrow" viewBox="0 0 10 10" refX="9" refY="5" markerWidth="7" markerHeight="7" orient="auto-start-reverse">
        <path d="M0 0 L10 5 L0 10 z" fill="#1ABC9C"/>
      </marker>
    </defs>
    <g fill="none" stroke="#1ABC9C" stroke-width="2" marker-end="url(#pv-arrow)">
      <path d="M206 80 L298 80"/>
      <path d="M422 80 L514 80"/>
      <path d="M576 112 L520 216"/>
      <path d="M398 250 L322 250"/>
      <path d="M200 216 L144 112"/>
    </g>
    <g font-family="Nunito, sans-serif" text-anchor="middle">
      <rect x="20" y="48" width="184" height="64" rx="6" fill="#2C2F36" stroke="#3E4250"/>
      <text x="112" y="76" fill="#ffffff" font-size="16" font-weight="700">1 · Collect</text>
      <text x="112" y="98" fill="#C9D3E7" font-size="13">Individual case reports</text>

      <rect x="300" y="48" width="120" height="64" rx="6" fill="#2C2F36" stroke="#3E4250"/>
      <text x="360" y="76" fill="#ffffff" font-size="16" font-weight="700">2 · Detect</text>
      <text x="360" y="98" fill="#C9D3E7" font-size="13">Find signals</text>

      <rect x="516" y="48" width="184" height="64" rx="6" fill="#2C2F36" stroke="#3E4250"/>
      <text x="608" y="76" fill="#ffffff" font-size="16" font-weight="700">3 · Assess</text>
      <text x="608" y="98" fill="#C9D3E7" font-size="13">Is the drug the cause?</text>

      <rect x="400" y="218" width="184" height="64" rx="6" fill="#2C2F36" stroke="#1ABC9C"/>
      <text x="492" y="246" fill="#1ABC9C" font-size="16" font-weight="700">4 · Act</text>
      <text x="492" y="268" fill="#C9D3E7" font-size="13">Minimise the risk</text>

      <rect x="136" y="218" width="184" height="64" rx="6" fill="#2C2F36" stroke="#3E4250"/>
      <text x="228" y="246" fill="#ffffff" font-size="16" font-weight="700">5 · Communicate</text>
      <text x="228" y="268" fill="#C9D3E7" font-size="13">Doctors, patients, label</text>
    </g>
  </svg>
  <figcaption>Pharmacovigilance is a loop, not a checkpoint. Every action changes what gets reported next.</figcaption>
</figure>

<ol class="pv-steps">
  <li><strong>Collect: individual case safety reports</strong>Doctors, pharmacists, patients and manufacturers submit reports of suspected adverse reactions to national databases such as the FDA's FAERS and the EU's EudraVigilance, which feed into WHO's global VigiBase. A valid report needs four things: an identifiable patient, an identifiable reporter, a suspect drug, and an adverse event.</li>
  <li><strong>Detect: find the signal in the noise</strong>A <em>signal</em> is information suggesting a new, or newly understood, link between a drug and an event. Analysts screen databases statistically to see which drug–event pairs are reported more often than expected.</li>
  <li><strong>Assess: weigh causality</strong>Experts review the case series. They look at timing, whether the reaction stopped when the drug was withdrawn (dechallenge), whether it came back when the drug was restarted (rechallenge), and whether something else explains it better. Frameworks such as the WHO-UMC system and the Naranjo scale structure this judgement.</li>
  <li><strong>Act: minimise the risk</strong>Responses run from label updates and new warnings, through dose changes, restricted use and mandatory monitoring, to withdrawing the product entirely.</li>
  <li><strong>Communicate: close the loop</strong>Safety communications reach prescribers and patients, and the benefit–risk balance is formally re-evaluated in periodic reports (PSURs/PBRERs) and in the product's Risk Management Plan.</li>
</ol>

## What makes a reaction "serious"

Seriousness is a regulatory definition, not a measure of severity. A severe headache is not serious. A mild reaction that puts someone in hospital is. Under ICH E2A, an adverse event is serious if it:

<ul class="pv-criteria">
  <li>Results in death</li>
  <li>Is life-threatening</li>
  <li>Requires or prolongs hospitalisation</li>
  <li>Causes persistent or significant disability</li>
  <li>Is a congenital anomaly or birth defect</li>
  <li>Is otherwise medically important</li>
</ul>

A serious reaction that is also *unexpected*, meaning it is not described in the product's reference safety information, triggers expedited reporting. Marketing authorisation holders generally have 15 calendar days to report it. In clinical trials, fatal or life-threatening suspected unexpected serious adverse reactions (SUSARs) must be reported within 7 days.

## How a signal is spotted

Spontaneous reports cannot give an incidence rate, because nobody knows how many people took the drug without reporting anything. Instead, signal detection asks a relative question: *compared with every other drug in the database, is this event reported unusually often with this one?*

The simplest measure is the **Proportional Reporting Ratio (PRR)**. It is built from a 2×2 table:

<div class="table-container">
<table class="pv-table">
  <thead>
    <tr><th></th><th>Event of interest</th><th>All other events</th><th>Total</th></tr>
  </thead>
  <tbody>
    <tr><td>Drug X</td><td class="pv-hit">a = 30</td><td>b = 970</td><td>1,000</td></tr>
    <tr><td>All other drugs</td><td>c = 200</td><td>d = 98,800</td><td>99,000</td></tr>
  </tbody>
</table>
</div>

PRR = [a / (a + b)] ÷ [c / (c + d)] = (30 / 1,000) ÷ (200 / 99,000) ≈ **14.9**

The event makes up 3% of Drug X's reports but only 0.2% of everyone else's. A widely used screening rule (Evans et al., 2001) flags a pair when PRR ≥ 2, chi-squared ≥ 4, and there are at least 3 cases. This pair clears all three. Related measures include the Reporting Odds Ratio and the Bayesian Information Component used on VigiBase. These methods handle small counts more cautiously.

<div class="pv-callout">
  <span class="pv-callout-title">A signal is a question, not an answer</span>
  <p>Disproportionality shows that reports are unusual, not that the drug causes the event. Publicity, a new boxed warning, or a lawsuit can all inflate reporting. So can confounding: a drug for a disease that itself causes the event will look guilty. Every statistical signal still needs clinical review.</p>
</div>

## The limits of the system

The biggest weakness is **under-reporting**. A frequently cited systematic review (Hazell &amp; Shakir, 2006) estimated that the median under-reporting rate across studies was about 94%. Reports are also uneven: new drugs and dramatic events get reported far more than old drugs and slow, common harms.

That is why spontaneous reporting is now one part of a wider toolkit:

- **Active surveillance** using electronic health records and claims data. Examples include the FDA's Sentinel System and the EU's DARWIN EU network.
- **Post-authorisation safety studies** that regulators can require as a condition of approval.
- **Patient registries** for pregnancy exposure and rare diseases.
- **Standardised coding** with MedDRA, so that a "heart attack" in Japan and a "myocardial infarction" in Brazil land in the same bucket.
- **Automation and NLP** to triage case intake, find duplicates, and mine free-text narratives and the literature at scale.

## Why it matters

Pharmacovigilance rarely makes news when it works. Its successes are quiet: a new contraindication, a monitoring requirement, a dose cap for older patients. Each one exists because someone took the time to file a report.

<div class="pv-callout">
  <span class="pv-callout-title">You can contribute</span>
  <p>Patients can report suspected side effects directly. In the US, use <a href="https://www.fda.gov/safety/medwatch-fda-safety-information-and-adverse-event-reporting-program">FDA MedWatch</a>. In the UK, use the <a href="https://yellowcard.mhra.gov.uk/">MHRA Yellow Card scheme</a>. In India, use the <a href="https://ipc.gov.in/PvPI/pv_home.html">Pharmacovigilance Programme of India</a>. Most countries have an equivalent. You don't need to be certain the medicine caused the problem; a suspicion is enough.</p>
</div>
