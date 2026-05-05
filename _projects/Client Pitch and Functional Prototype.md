---
layout: project
title: "SLF Crushers"
image: /assets/images/LSF.jpg
---

## Table of Contents
- [Client Pitch](#client-pitch)
- [Functional Prototype](#functional-prototype)
- [Success Criteria + Test Results](#success-criteria--test-results)
- [Full Documents](#full-documents)

---

## Client Pitch

### Problem Statement
Vineyard growers face severe spotted lanternfly (SLF) infestations before harvest. SLF feed on vine sap, weaken grapevines, reduce sugar content, and can cause major yield loss.

### Impact
Our goal is to remove adult SLF from grapevines without damaging the fruit or vines, while reducing labor and pesticide use.

### Proposed Direction
We designed a low-power rotating trap that attracts, guides, captures, and contains SLF with minimal human involvement.

### Concept
1. Attract SLF using tree-of-heaven sap or other lures  
2. Guide them inward using a rotating reaper wall and peg plate  
3. Drop them through a center opening  
4. Contain them in a removable collection chamber  

### Key Risks
- Attractant may not outperform natural vines  
- SLF may escape before capture  
- Full-scale rotation may require stronger motor support  

---

## Functional Prototype

### Purpose
The prototype tested whether a rotating peg-and-wall system could guide surrogate insects into a collection chamber without jamming, escaping, or failing to rotate.

### What Was Tested

**Peg Guidance Test**  
- Assessed whether the reaper wall and peg plate guided marbles toward the center opening  
- Result: GPI = 93.0, with 19/20 successful trials  

**Chamber Drop Test**  
- Assessed whether marbles/Orbeez fell cleanly into the collection chamber  
- Result: CRI = 92.5, with 19/20 successful trials  

**Rotational Test with Motor**  
- Assessed whether the full assembly completed powered 360° rotations  
- Result: RSI = 85.0, with 18/20 successful trials  

---

## Success Criteria + Test Results

Our prototype exceeded all three success criteria. The Peg Guidance Test showed that the system can guide objects toward the center with minimal bypass and no jamming or compression. The Chamber Drop Test showed that the collection chamber works reliably, with only one partial entry and no bounce-out or missed openings. The Rotational Test showed that the system can complete full 360° rotations under motor power, although future improvements should reduce sticking and base movement.

### Final Scores
- **GPI:** 93.0  
- **CRI:** 92.5  
- **RSI:** 85.0  

### Future Recommendations
To improve the GPI, the system should be scaled to the target size with added structural reinforcement so the peg and wall system stays aligned. To improve the CRI, the chamber opening and final peg placement should be refined so SLF have more room to fall cleanly into the container. To improve the RSI, a stronger low-speed, high-torque 12V–24V gear motor and better load distribution should be used to support continuous full-scale rotation.

---

## Full Documents

- [View Client Outline (PDF)]({{ '/assets/pdfs/client-outline.pdf' | relative_url }})
- [View Functional Prototype (PDF)]({{ '/assets/pdfs/functional-prototype.pdf' | relative_url }})
- [View ODP6 Final SLF Crushers Report (PDF)]({{ '/assets/pdfs/ODP6_SLF_Crushers(1).pdf' | relative_url }})