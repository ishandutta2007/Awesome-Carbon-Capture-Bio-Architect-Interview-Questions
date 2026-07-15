# 🌍 Carbon-Capture Bio-Architect Interview Questions 🌍🧬

<p align="center">
  <img src="assets/banner.svg" alt="Carbon-Capture Bio-Architect Banner" width="100%">
</p>
<p align="center">
  <a href="https://github.com/ishandutta2007/Awesome-Awesome-Awesome"><img src="https://img.shields.io/badge/Awesome-%E2%9C%94-blueviolet?style=flat-square&logo=github" alt="Awesome"/></a><a href="https://discord.gg/jc4xtF58Ve"><img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord" /></a>
</p>

✨ A curated, community-driven collection of interview questions (with model answers, frameworks, and explanations) for roles working at the intersection of **synthetic biology and carbon capture/removal** — engineering organisms and enzymes to fix, convert, or mineralize atmospheric or point-source CO₂, and designing the measurement systems that verify how much carbon was actually, durably removed. ✨

> 📝 **A note on the title:** "Carbon-Capture Bio-Architect" isn't a standardized industry job title. This repo covers the real, active intersection of synthetic biology and carbon removal — titles you're more likely to actually see include "Synthetic Biology Engineer (Carbon Removal)," "Bioprocess Engineer," or "MRV Scientist" at a carbon removal or industrial biotechnology company.

This is not a list of trivia. Every question includes:
- **Why interviewers ask it**
- **A model answer or framework**
- **Follow-up questions** interviewers commonly use to probe deeper

> 🌱 This is v1. Contributions, corrections, and new questions are very welcome — see [CONTRIBUTING.md](CONTRIBUTING.md).

> ⚠️ **Note on scope:** This role spans plant/microbial biochemistry, synthetic biology, process engineering, and — distinctively for this field — measurement/verification and carbon accounting. This repo builds directly on the companion **Synthetic Biology Designer** and **Bioremediation AI Engineer** repos — read those first if the fundamentals there are unfamiliar. Most engineered carbon-fixation systems remain at lab or pilot scale, and this repo is deliberately honest throughout about the difference between short-term biomass carbon storage and genuinely durable, geologic-timescale sequestration — a distinction that matters enormously in this field and is too often glossed over in public discussion. Environmental-release and containment content stays at the conceptual/policy level throughout, consistent with the companion Synthetic Biology Designer repo's approach.

---

## 📚 Table of Contents

| # | Category | What it covers |
|---|----------|-----------------|
| 1 | [Carbon Capture & Sequestration Fundamentals](questions/01-carbon-capture-and-sequestration-fundamentals.md) | Biological vs. mechanical capture, the permanence spectrum, why "capture" isn't "storage" |
| 2 | [Engineering Photosynthetic & Carbon-Fixing Organisms](questions/02-engineering-photosynthetic-and-carbon-fixing-organisms.md) | RuBisCO engineering, alternative CO₂ fixation pathways, algae/cyanobacteria chassis |
| 3 | [Enzymatic & Biohybrid Capture Systems](questions/03-enzymatic-and-biohybrid-capture-systems.md) | Carbonic anhydrase, enzyme-enhanced direct air capture, biomineralization |
| 4 | [Computational Design & Modeling](questions/04-computational-design-and-modeling.md) | Metabolic modeling, pathway design, ML-guided enzyme/pathway optimization |
| 5 | [Measurement, Reporting & Verification (MRV)](questions/05-measurement-reporting-and-verification.md) | Quantifying real sequestration, permanence, additionality, avoiding double counting |
| 6 | [Scale-Up, Deployment & Techno-Economics](questions/06-scale-up-deployment-and-techno-economics.md) | Lab to industrial scale, cost per ton, honest comparison to mechanical DAC |
| 7 | [Environmental Release, Biosafety & Regulatory](questions/07-environmental-release-biosafety-and-regulatory.md) | Kept at the conceptual/policy level — ecological risk, containment, carbon market regulation |
| 8 | [Behavioral & Case Studies](questions/08-behavioral-and-case-studies.md) | Cross-disciplinary collaboration, real-world engineering tradeoffs |

Also see: [resources.md](resources.md) for external reading, key papers, and communities.

---

## 🧭 How to Use This Repo

- **Coming from a plant biology/microbiology background?** Prioritize sections 4 and 5 — the goal is building fluency in computational pathway design and the measurement/verification rigor this field specifically demands.
- **Coming from a climate science/process engineering background?** Prioritize sections 2 and 3 — you'll need working fluency in the actual biochemistry and organism engineering involved before your systems-level thinking is usefully applied to this domain.
- **Interviewing at a company engineering algae or cyanobacteria for carbon fixation?** Focus heavily on section 2.
- **Interviewing at a company building enzyme-enhanced direct air capture systems?** Focus heavily on section 3.
- **Interviewing at a carbon removal company or one selling carbon credits?** Focus heavily on section 5 — MRV rigor is often the single most scrutinized part of this field.

Each question is tagged with a rough difficulty and role-level indicator:
- 🟢 Junior/Associate · 🟡 Mid-level Engineer/Scientist · 🔴 Senior/Principal

---

## 🗂 Repo Structure

```
carbon-capture-bio-architect-interview-questions/
├── README.md                                              ← you are here
├── CONTRIBUTING.md
├── LICENSE
├── resources.md
└── questions/
    ├── 01-carbon-capture-and-sequestration-fundamentals.md
    ├── 02-engineering-photosynthetic-and-carbon-fixing-organisms.md
    ├── 03-enzymatic-and-biohybrid-capture-systems.md
    ├── 04-computational-design-and-modeling.md
    ├── 05-measurement-reporting-and-verification.md
    ├── 06-scale-up-deployment-and-techno-economics.md
    ├── 07-environmental-release-biosafety-and-regulatory.md
    └── 08-behavioral-and-case-studies.md
```

## 🤝 Contributing

PRs are the whole point of this repo. If you were asked a question in a real interview that isn't here, add it! See [CONTRIBUTING.md](CONTRIBUTING.md) for format guidelines — note in particular the environmental-release/biosafety content guidelines, which keep this repo at the conceptual/policy level only.

## 📄 License

Content is available under [MIT License](LICENSE) — use it freely for your own prep, mock interviews, or hiring loops.

## ⭐ Support

If this helped you land an offer, consider starring the repo and adding the question that stumped you — it might help the next person.
