# CoCoDa Project

**CoCoDa** (Controllable Code-based Design Amendments) is a research-focused take-home project that explores technical interventions to mitigate systemic issues in mobile apps, especially those linked to digital self-determination, as conceptualized in the Digital Services Act (DSA). The project presents three distinct technical approaches to amending app user interfaces, each documented and implemented in its own method-specific file.

## Project Overview

The primary goal of CoCoDa is to investigate alternative ways of enhancing user agency and transparency by enabling modifications to app interfaces. These methods are intended to address problematic patterns and opacity in app design—what might be termed "systemic app harms"—by giving users or auditors the tools to reshape and better understand app behaviors.

### 📁 Methods

#### 🔧 Method 1 – **GreaseMilkyway**
A UI-level amendment system that uses accessibility overlays or scripting to manipulate on-screen components without needing root access or app recompilation. Ideal for surface-level interventions.

#### 🧩 Method 2 – **GreaseDroid**
A reverse engineering approach where apps are decompiled, modified at the code or resource level, and repackaged. This method targets deeper structural changes to the app UI and behavior.

#### 🤖 Method 3 – **GreaseTerminator**
A machine learning-based vision system that detects harmful or non-compliant UI patterns (e.g., deceptive consent flows) and amends them using image-based transformations or automation.

---

## Structure

CoCoDa-project/
├── greaseMilkyway/ # Method 1: Overlay-based UI changes
├── greaseDroid/ # Method 2: Decompiled app modifications
├── greaseTerminator/ # Method 3: ML Vision-based UI adjustments
└── README.md # Project documentation
---

## Motivation

This project aligns with recent scholarship advocating for user empowerment and the "right to repair" in the mobile ecosystem. By equipping users and developers with practical tools to contest and reshape app interfaces, CoCoDa engages with a growing movement towards ethical and accountable technology.

---

## Citation

> **Kollnig, K., Datta, S., Serban von Davier, T., Van Kleek, M., Binns, R., Lyngs, U., & Shadbolt, N.** (2023).  
> *‘We are adults and deserve control of our phones’: Examining the risks and opportunities of a right to repair for mobile apps.*  
> In *Proceedings of the 2023 ACM Conference on Fairness, Accountability, and Transparency.*

> **Kollnig, K., Datta, S., & Van Kleek, M.** (2021).  
> *I Want My App That Way: Reclaiming Sovereignty Over Personal Devices.*  
> *Extended Abstracts of the 2021 CHI Conference on Human Factors in Computing Systems*, 1–8.  
> [https://doi.org/10.1145/3411763.3451632](https://doi.org/10.1145/3411763.3451632)


