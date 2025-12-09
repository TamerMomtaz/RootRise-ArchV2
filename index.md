# RootRise Architecture v2.0
## The Complete System with My Sector + &Eye (The Lens)

**Version:** 2.0  
**Date:** December 7, 2025  
**Authors:** Tee (CTO), Alla (CSO)  
**Status:** Restructured based on Alla's field insights

---

## Executive Summary

This document restructures the RootRise architecture based on Alla's critical insight from years of on-the-ground SME work:

> "The lens is the objective — the burning desire at the client's end. If the client sees that RootRise can achieve their objectives, they will see themselves in RootRise."

**The key restructuring:**

| Concept | Old Name | New Name | What It Does |
|---------|----------|----------|--------------|
| Industry Knowledge | &Eye / Sector Lens | **My Sector** | Loads standards, regulations, benchmarks for the industry |
| Transformation Objective | (not explicit) | **&Eye (The Lens)** | Shapes priorities, depth, focus, and framing throughout |

**Why this matters:**
- "My Sector" answers: *"What industry am I in?"*
- "&Eye (The Lens)" answers: *"What do I want to achieve?"*

Together, they make RootRise truly **"Made for You"** — not a generic diagnostic tool, but a system that understands YOUR industry AND YOUR goals.

---

## Part 1: The Two Layers Explained

### Layer 1: My Sector (Industry Context)

**What it is:** The industry/sector the SME operates in.

**How it works:**
- Auto-detected from questionnaire responses (or manually confirmed)
- Loads industry-specific knowledge into the system
- Affects: terminology, standards, regulations, benchmarks, compliance requirements

**Examples:**
| Sector | Standards Loaded | Regulators | Benchmarks |
|--------|------------------|------------|------------|
| Food Processing | HACCP, ISO 22000, Halal | NFSA, SFDA, FDA | Spoilage rate, energy/ton |
| Pharmaceuticals | GMP, WHO PQ, GDP | EDA, SFDA, EMA | Batch rejection, yield |
| Textiles | OEKO-TEX, GOTS, BSCI | EU Textile Strategy | Lead time, defect rate |
| Automotive Parts | IATF 16949, VDA 6.3 | OEM requirements | PPM defects, OTD |

**User experience:**
```
"My Sector: Food Processing"
→ System now speaks your language
→ Knows HACCP matters to you
→ Benchmarks against food industry peers
```

---

### Layer 2: &Eye — The Lens (Transformation Objective)

**What it is:** The client's burning desire — WHY they want transformation.

**How it works:**
- User explicitly selects their primary objective(s)
- Shapes the ENTIRE workflow: questions, analysis depth, priorities, recommendations, report framing
- Keeps the objective visible and central throughout the journey

**Examples of Objectives (Lenses):**

| &Eye Lens | The Burning Desire | Priority Focus |
|-----------|-------------------|----------------|
| 🌍 **Export Readiness** | "I want to sell internationally" | Certifications, logistics, market entry, compliance |
| 💰 **Investment Attraction** | "I want to raise capital" | Financials, governance, valuation, pitch readiness |
| 👤 **Owner Succession** | "I want to retire / step back" | HR, knowledge transfer, org independence, processes |
| 🏛️ **Inheritance Preparation** | "I want to pass this to my children" | Legal structure, family governance, succession planning |
| 💼 **Sale / Exit Readiness** | "I want to sell the company" | Valuation, clean books, operational independence |
| 🤝 **Partnership / JV** | "I want to find a partner" | Due diligence readiness, governance, complementarity |
| 📈 **Profitability** | "I want better margins" | Cost optimization, efficiency, pricing strategy |
| 🏭 **Operational Excellence** | "I want to run better" | Processes, quality, lean operations |
| 💻 **Digital Transformation** | "I want to modernize" | Tech stack, automation, digital presence |
| 🌱 **Sustainability** | "I want to be green / compliant" | Environmental compliance, certifications, ESG |
| 👥 **Employment Growth** | "I want to create jobs" | HR capacity, scaling, workforce development |
| 🔗 **Supply Chain Integration** | "I want to join a value chain" | Supplier readiness, quality systems, logistics |
| ✨ **Custom Objective** | "I want [something specific]" | User-defined focus areas |

**User experience:**
```
"Your &Eye Lens: Export Readiness"
→ Every question shaped by this goal
→ Every analysis prioritized for this goal
→ Every recommendation supports this goal
→ Final report framed around achieving this goal
```

---

### How They Work Together

```
┌─────────────────────────────────────────────────────────────────────────┐
│                         USER CONFIGURATION                              │
├─────────────────────────────────────────────────────────────────────────┤
│                                                                         │
│   STEP 1: MY SECTOR                                                     │
│   ┌─────────────────────────────────────────────────────────────────┐  │
│   │  "What industry is your business in?"                           │  │
│   │                                                                  │  │
│   │  [Auto-detected: Food Processing - Dairy]     [✓ Confirm]       │  │
│   │                                                                  │  │
│   │  → Loads: HACCP, ISO 22000, Halal standards                     │  │
│   │  → Loads: NFSA, SFDA, FDA regulators                            │  │
│   │  → Loads: Food industry benchmarks                              │  │
│   └─────────────────────────────────────────────────────────────────┘  │
│                                                                         │
│   STEP 2: &EYE — YOUR LENS                                             │
│   ┌─────────────────────────────────────────────────────────────────┐  │
│   │  "What is your main objective for this transformation?"         │  │
│   │                                                                  │  │
│   │  ● 🌍 Export Readiness          ○ 💰 Investment Attraction      │  │
│   │  ○ 👤 Owner Succession          ○ 🤝 Partnership / JV           │  │
│   │  ○ 📈 Profitability             ○ 💻 Digital Transformation     │  │
│   │  ○ ✨ Custom: _______________                                   │  │
│   │                                                                  │  │
│   │  [You can select up to 3 objectives]                            │  │
│   │                                                                  │  │
│   │  → Shapes: Question depth, analysis priority, recommendations   │  │
│   │  → Frames: Final report around achieving THIS goal              │  │
│   └─────────────────────────────────────────────────────────────────┘  │
│                                                                         │
└─────────────────────────────────────────────────────────────────────────┘
```

---

## Part 2: The Complete Workflow

### Phase 1: Configuration

```
USER ARRIVES
     │
     ▼
┌─────────────────────────────────────────────────────┐
│  STEP 1: WHO ARE YOU?                               │
│  • User type: SME / Investor / Government / Donor   │
│  • Basic profile: Company name, country, size       │
└─────────────────────────────────────────────────────┘
     │
     ▼
┌─────────────────────────────────────────────────────┐
│  STEP 2: MY SECTOR                                  │
│  • Auto-detect from initial responses               │
│  • User confirms or corrects                        │
│  • System loads sector context                      │
│    → Standards, regulations, benchmarks             │
└─────────────────────────────────────────────────────┘
     │
     ▼
┌─────────────────────────────────────────────────────┐
│  STEP 3: &EYE — YOUR LENS                          │
│  • "What's your main objective?"                    │
│  • User selects 1-3 objectives                      │
│  • System configures priority weighting             │
│    → Which agents get more depth                    │
│    → Which areas get focused questions              │
│    → How recommendations are prioritized            │
└─────────────────────────────────────────────────────┘
     │
     ▼
┌─────────────────────────────────────────────────────┐
│  STEP 4: AGENT SELECTION                            │
│  • Core agents always included                      │
│  • System recommends add-ons based on &Eye lens     │
│  • User confirms or adjusts                         │
│                                                     │
│  &Eye Lens: Export → Recommends: Ricardo, Ohno     │
│  &Eye Lens: Succession → Recommends: Mayo, Graham  │
└─────────────────────────────────────────────────────┘
```

### Phase 2: Data Collection (Questionnaire)

```
┌─────────────────────────────────────────────────────────────────────────┐
│                         SMART QUESTIONNAIRE                             │
├─────────────────────────────────────────────────────────────────────────┤
│                                                                         │
│  BASELINE QUESTIONS (Everyone answers)                                  │
│  ├── Company profile                                                    │
│  ├── Basic financials                                                   │
│  ├── Operations overview                                                │
│  └── Team structure                                                     │
│                                                                         │
│  MY SECTOR QUESTIONS (Based on industry)                                │
│  ├── Food Processing → Food safety practices, cold chain, traceability │
│  ├── Pharma → GMP compliance, batch documentation, clean rooms          │
│  └── Textiles → Labor practices, dye management, certifications         │
│                                                                         │
│  &EYE LENS QUESTIONS (Based on objective — DEEPER)                     │
│  ├── Export → Certification status, target markets, logistics capacity │
│  ├── Succession → Key person dependencies, documented processes, heir  │
│  ├── Investment → Cap table, governance, growth projections             │
│  └── [Lens adds 10-15 focused questions in priority area]              │
│                                                                         │
│  ┌───────────────────────────────────────────────────────────────────┐ │
│  │  🎯 YOUR LENS: Export Readiness                                   │ │
│  │  "These questions help us understand your export potential"       │ │
│  └───────────────────────────────────────────────────────────────────┘ │
│                                                                         │
└─────────────────────────────────────────────────────────────────────────┘
```

### Phase 3: Analysis (The Pantheon)

```
┌─────────────────────────────────────────────────────────────────────────┐
│                    THE PANTHEON — AGENT ANALYSIS                        │
├─────────────────────────────────────────────────────────────────────────┤
│                                                                         │
│  CONTEXT INJECTION (Both layers loaded into every agent)                │
│  ┌───────────────────────────────────────────────────────────────────┐ │
│  │  My Sector: Food Processing                                       │ │
│  │  → "You are analyzing a food manufacturing company. Consider      │ │
│  │     HACCP, ISO 22000, cold chain, Halal requirements..."         │ │
│  │                                                                   │ │
│  │  &Eye Lens: Export Readiness                                     │ │
│  │  → "The client's primary objective is to become export-ready.    │ │
│  │     Prioritize findings and recommendations that support          │ │
│  │     international market entry, certifications, and compliance." │ │
│  └───────────────────────────────────────────────────────────────────┘ │
│                                                                         │
│  WEIGHTED EXECUTION (Lens determines depth)                             │
│                                                                         │
│  &Eye Lens: EXPORT READINESS                                           │
│  ┌─────────────────────────────────────────────────────────────────┐   │
│  │                                                                  │   │
│  │  HIGH PRIORITY (Deep analysis)        STANDARD PRIORITY          │   │
│  │  ┌──────────────┐ ┌──────────────┐   ┌──────────────┐           │   │
│  │  │ The Ricardo  │ │ The Ohno     │   │ The Marvin   │           │   │
│  │  │ Export ████  │ │ Supply ████  │   │ Diagnostic██ │           │   │
│  │  │ Weight: 1.5x │ │ Weight: 1.3x │   │ Weight: 1.0x │           │   │
│  │  └──────────────┘ └──────────────┘   └──────────────┘           │   │
│  │  ┌──────────────┐                    ┌──────────────┐           │   │
│  │  │ The Graham   │                    │ The Lovelace │           │   │
│  │  │ Finance ███  │                    │ Digital █    │           │   │
│  │  │ Weight: 1.2x │                    │ Weight: 0.8x │           │   │
│  │  └──────────────┘                    └──────────────┘           │   │
│  │                                                                  │   │
│  └─────────────────────────────────────────────────────────────────┘   │
│                                                                         │
│  &Eye Lens: OWNER SUCCESSION (different weighting)                     │
│  ┌─────────────────────────────────────────────────────────────────┐   │
│  │                                                                  │   │
│  │  HIGH PRIORITY (Deep analysis)        STANDARD PRIORITY          │   │
│  │  ┌──────────────┐ ┌──────────────┐   ┌──────────────┐           │   │
│  │  │ The Mayo     │ │ The Marvin   │   │ The Ricardo  │           │   │
│  │  │ HR ████████  │ │ Diagnostic██ │   │ Export █     │           │   │
│  │  │ Weight: 1.5x │ │ Weight: 1.3x │   │ Weight: 0.8x │           │   │
│  │  └──────────────┘ └──────────────┘   └──────────────┘           │   │
│  │  ┌──────────────┐                                               │   │
│  │  │ The Graham   │                                               │   │
│  │  │ Finance ███  │                                               │   │
│  │  │ Weight: 1.2x │                                               │   │
│  │  └──────────────┘                                               │   │
│  │                                                                  │   │
│  └─────────────────────────────────────────────────────────────────┘   │
│                                                                         │
└─────────────────────────────────────────────────────────────────────────┘
```

### Phase 4: Synthesis & Recommendations

```
┌─────────────────────────────────────────────────────────────────────────┐
│                    THE DRUCKER — SYNTHESIS                              │
├─────────────────────────────────────────────────────────────────────────┤
│                                                                         │
│  LENS-AWARE SYNTHESIS                                                   │
│  ┌───────────────────────────────────────────────────────────────────┐ │
│  │  The Drucker receives:                                            │ │
│  │  • All agent outputs                                              │ │
│  │  • My Sector context                                              │ │
│  │  • &Eye Lens (primary objective)                                 │ │
│  │                                                                   │ │
│  │  Synthesis instructions:                                          │ │
│  │  "Frame all findings through the lens of EXPORT READINESS.       │ │
│  │   Every recommendation should answer: 'How does this help        │ │
│  │   the company become export-ready?'"                             │ │
│  └───────────────────────────────────────────────────────────────────┘ │
│                                                                         │
│  RECOMMENDATION PRIORITIZATION                                          │
│  ┌───────────────────────────────────────────────────────────────────┐ │
│  │                                                                   │ │
│  │  TIER 1: Direct Lens Impact                                      │ │
│  │  "These actions directly advance your EXPORT READINESS"          │ │
│  │  ├── Obtain ISO 22000 certification                              │ │
│  │  ├── Register with target market food authorities                │ │
│  │  └── Establish export logistics partnership                      │ │
│  │                                                                   │ │
│  │  TIER 2: Supporting Actions                                      │ │
│  │  "These strengthen your foundation for export"                   │ │
│  │  ├── Improve inventory management                                │ │
│  │  ├── Document all production processes                           │ │
│  │  └── Train quality team on international standards               │ │
│  │                                                                   │ │
│  │  TIER 3: General Improvements                                    │ │
│  │  "Important for overall business health"                         │ │
│  │  ├── Update financial reporting                                  │ │
│  │  └── Implement digital inventory system                          │ │
│  │                                                                   │ │
│  └───────────────────────────────────────────────────────────────────┘ │
│                                                                         │
└─────────────────────────────────────────────────────────────────────────┘
```

### Phase 5: Report Generation

```
┌─────────────────────────────────────────────────────────────────────────┐
│                    THE TUFTE — REPORT GENERATION                        │
├─────────────────────────────────────────────────────────────────────────┤
│                                                                         │
│  LENS-FRAMED REPORT                                                     │
│  ┌───────────────────────────────────────────────────────────────────┐ │
│  │                                                                   │ │
│  │  ╔═══════════════════════════════════════════════════════════╗   │ │
│  │  ║           ROOTRISE DIAGNOSTIC REPORT                      ║   │ │
│  │  ╠═══════════════════════════════════════════════════════════╣   │ │
│  │  ║  Company: ABC Foods Ltd.                                  ║   │ │
│  │  ║  My Sector: Food Processing — Dairy Manufacturing         ║   │ │
│  │  ║                                                           ║   │ │
│  │  ║  🎯 &EYE LENS: EXPORT READINESS                          ║   │ │
│  │  ║                                                           ║   │ │
│  │  ║  "This diagnostic was conducted through the lens of       ║   │ │
│  │  ║   preparing ABC Foods for international export markets,   ║   │ │
│  │  ║   with specific focus on EU compliance, Halal             ║   │ │
│  │  ║   certification, and supply chain readiness."             ║   │ │
│  │  ╚═══════════════════════════════════════════════════════════╝   │ │
│  │                                                                   │ │
│  │  EXECUTIVE SUMMARY                                                │ │
│  │  "Based on your goal of becoming export-ready, we found..."      │ │
│  │                                                                   │ │
│  │  EXPORT READINESS SCORE: 62/100                                  │ │
│  │  ├── Certification Readiness: 45/100 ⚠️                         │ │
│  │  ├── Logistics Capability: 70/100 ✓                             │ │
│  │  ├── Documentation: 55/100 ⚠️                                   │ │
│  │  └── Market Knowledge: 78/100 ✓                                 │ │
│  │                                                                   │ │
│  │  ROADMAP TO EXPORT READINESS                                     │ │
│  │  "Your 90-day path to international markets"                     │ │
│  │  ├── Month 1: Certification gaps                                 │ │
│  │  ├── Month 2: Documentation & processes                          │ │
│  │  └── Month 3: Logistics & market entry                          │ │
│  │                                                                   │ │
│  └───────────────────────────────────────────────────────────────────┘ │
│                                                                         │
│  LENS REMINDER THROUGHOUT                                               │
│  Every section includes:                                                │
│  ┌───────────────────────────────────────────────────────────────────┐ │
│  │  🎯 How this supports your Export Readiness goal:                │ │
│  │  "[Explanation of why this finding/recommendation matters        │ │
│  │   for achieving the client's stated objective]"                  │ │
│  └───────────────────────────────────────────────────────────────────┘ │
│                                                                         │
└─────────────────────────────────────────────────────────────────────────┘
```

---

## Part 3: The &Eye Lens Library

### Pre-Defined Lenses

| ID | Lens Name | Icon | Primary Focus | Key Agents | Typical Client |
|----|-----------|------|---------------|------------|----------------|
| 01 | Export Readiness | 🌍 | International markets, certifications, logistics | Ricardo, Ohno, Graham | SME wanting to sell abroad |
| 02 | Investment Attraction | 💰 | Financial structure, governance, valuation | Graham, Marvin, Deming | SME seeking funding |
| 03 | Owner Succession | 👤 | HR, processes, operational independence | Mayo, Marvin, Graham | Founder wanting to retire |
| 04 | Inheritance Preparation | 🏛️ | Legal structure, family governance | Graham, Mayo | Family business planning transfer |
| 05 | Sale / Exit | 💼 | Valuation, clean books, due diligence readiness | Graham, Marvin, Deming | SME planning exit |
| 06 | Partnership / JV | 🤝 | Governance, complementarity, readiness | Marvin, Graham, Mayo | SME seeking partners |
| 07 | Profitability | 📈 | Cost optimization, efficiency, pricing | Graham, Ohno, Porter | SME wanting better margins |
| 08 | Operational Excellence | 🏭 | Processes, quality, lean | Ohno, Marvin, Deming | SME wanting to run better |
| 09 | Digital Transformation | 💻 | Tech stack, automation, digital presence | Lovelace, Marvin | SME wanting to modernize |
| 10 | Sustainability / ESG | 🌱 | Environmental, social, governance | Specialized, Marvin | SME wanting green compliance |
| 11 | Employment Growth | 👥 | HR capacity, scaling, workforce | Mayo, Marvin | Donor/govt job creation mandate |
| 12 | Supply Chain Integration | 🔗 | Supplier readiness, quality systems | Ohno, Ricardo | SME joining value chain |
| 13 | Local Economic Development | 🏘️ | Community impact, local sourcing | Ohno, Mayo | Govt/donor local development |
| 14 | Cross-Border Collaboration | 🌐 | Regional integration, border compliance | Ricardo, Ohno | Regional development programs |
| 00 | Custom Objective | ✨ | User-defined | User-selected | Unique situations |

### Lens Configuration Structure

```python
class EyeLens:
    id: str                      # "export_readiness"
    name: str                    # "Export Readiness"
    icon: str                    # "🌍"
    description: str             # "Prepare for international markets"
    
    # Agent weighting (1.0 = standard, >1 = priority, <1 = reduced)
    agent_weights: Dict[str, float] = {
        "marvin": 1.0,           # Diagnostic - standard
        "graham": 1.2,           # Finance - elevated (export needs capital)
        "ricardo": 1.5,          # Export - HIGH PRIORITY
        "lovelace": 0.8,         # Digital - reduced
        "mayo": 0.9,             # HR - slightly reduced
        "ohno": 1.3,             # Supply Chain - elevated (logistics)
        "porter": 1.1,           # Market - slightly elevated
    }
    
    # Additional questions for this lens
    focused_questions: List[Question]
    
    # Recommendation prioritization rules
    priority_keywords: List[str]  # ["certification", "export", "international"]
    
    # Report framing
    executive_summary_template: str
    section_framing: Dict[str, str]
```

---

## Part 4: Multiple Lenses

Alla noted that clients may have multiple objectives. The system supports up to 3 lenses:

```
┌─────────────────────────────────────────────────────────────────────────┐
│  &EYE — YOUR LENSES (Select up to 3)                                   │
├─────────────────────────────────────────────────────────────────────────┤
│                                                                         │
│  PRIMARY LENS (highest priority):                                       │
│  ● 🌍 Export Readiness                                                 │
│                                                                         │
│  SECONDARY LENS (also important):                                       │
│  ● 💰 Investment Attraction                                            │
│                                                                         │
│  TERTIARY LENS (consider):                                             │
│  ○ [None selected]                                                     │
│                                                                         │
│  Combined weighting:                                                    │
│  • Export questions + Investment questions                              │
│  • Ricardo HIGH + Graham HIGH                                          │
│  • Report shows both objectives                                         │
│                                                                         │
└─────────────────────────────────────────────────────────────────────────┘
```

**Weight combination formula:**
```python
def calculate_combined_weight(agent, lenses):
    primary_weight = lenses[0].agent_weights[agent] * 1.0
    secondary_weight = lenses[1].agent_weights[agent] * 0.6 if len(lenses) > 1 else 0
    tertiary_weight = lenses[2].agent_weights[agent] * 0.3 if len(lenses) > 2 else 0
    return primary_weight + secondary_weight + tertiary_weight
```

---

## Part 5: How It Shows in the UI

### At Onboarding
```
┌─────────────────────────────────────────────────────────────────────────┐
│                                                                         │
│  Welcome to RootRise                                                    │
│                                                                         │
│  We'll customize your diagnostic based on:                              │
│                                                                         │
│  📍 YOUR SECTOR                                                        │
│     The industry you operate in — so we speak your language            │
│                                                                         │
│  🎯 YOUR LENS                                                          │
│     Your transformation objective — so we focus on what matters to YOU │
│                                                                         │
│                              [Get Started →]                            │
│                                                                         │
└─────────────────────────────────────────────────────────────────────────┘
```

### During Questionnaire
```
┌─────────────────────────────────────────────────────────────────────────┐
│  ┌───────────────────────────────────────────────────────────────────┐ │
│  │  📍 Food Processing    🎯 Export Readiness                        │ │
│  └───────────────────────────────────────────────────────────────────┘ │
│                                                                         │
│  Section 4 of 7: Export Capabilities                                    │
│                                                                         │
│  🎯 This section dives deep because of your Export Readiness lens      │
│                                                                         │
│  Q: Which international certifications do you currently hold?           │
│  □ ISO 22000    □ HACCP    □ Halal    □ Kosher    □ FSSC 22000        │
│                                                                         │
│  Q: Which export markets are you targeting?                             │
│  □ EU    □ GCC    □ Africa    □ Americas    □ Asia                     │
│                                                                         │
└─────────────────────────────────────────────────────────────────────────┘
```

### In Results Dashboard
```
┌─────────────────────────────────────────────────────────────────────────┐
│                                                                         │
│  ABC FOODS — DIAGNOSTIC COMPLETE                                        │
│                                                                         │
│  ┌─────────────────────────────────────────────────────────────────┐   │
│  │  📍 MY SECTOR                    🎯 MY LENS                      │   │
│  │  Food Processing — Dairy         Export Readiness                │   │
│  └─────────────────────────────────────────────────────────────────┘   │
│                                                                         │
│  ┌─────────────────────────────────────────────────────────────────┐   │
│  │                                                                  │   │
│  │  🎯 EXPORT READINESS SCORE                                      │   │
│  │                                                                  │   │
│  │     ████████████░░░░░░░░  62/100                                │   │
│  │                                                                  │   │
│  │  "You're 62% ready to export. Here's what's holding you back    │   │
│  │   and how to fix it."                                           │   │
│  │                                                                  │   │
│  └─────────────────────────────────────────────────────────────────┘   │
│                                                                         │
│  TOP PRIORITIES FOR EXPORT READINESS                                    │
│  ┌─────────────────────────────────────────────────────────────────┐   │
│  │  1. 🔴 Obtain ISO 22000 certification         Impact: HIGH      │   │
│  │  2. 🟡 Register with EU food authorities      Impact: HIGH      │   │
│  │  3. 🟡 Establish cold chain documentation     Impact: MEDIUM    │   │
│  └─────────────────────────────────────────────────────────────────┘   │
│                                                                         │
└─────────────────────────────────────────────────────────────────────────┘
```

---

## Part 6: Technical Implementation

### State Object Structure

```python
@dataclass
class DiagnosticState:
    # Session
    session_id: str
    user_id: str
    created_at: datetime
    
    # Configuration
    user_type: str                    # "sme" | "investor" | "government" | "donor"
    
    # MY SECTOR (Industry Context)
    sector: SectorContext
    # {
    #   id: "food_processing",
    #   sub_sector: "dairy",
    #   standards: ["HACCP", "ISO 22000", ...],
    #   regulators: ["NFSA", "SFDA", ...],
    #   benchmarks: {...}
    # }
    
    # &EYE — THE LENS (Transformation Objective)
    eye_lenses: List[EyeLens]         # Up to 3 lenses
    # [
    #   {id: "export_readiness", weight: 1.0},
    #   {id: "investment_attraction", weight: 0.6}
    # ]
    
    # Computed from lenses
    agent_weights: Dict[str, float]   # Combined weights per agent
    priority_areas: List[str]         # Focus areas from lenses
    
    # Questionnaire
    responses: Dict[str, Any]
    documents: List[Document]
    
    # Agent outputs
    agent_outputs: Dict[str, AgentOutput]
    
    # Synthesis
    synthesis: Synthesis
    recommendations: List[Recommendation]  # Prioritized by lens
    
    # Report
    report: Report
```

### Lens-Aware Agent Execution

```python
async def run_agents(state: DiagnosticState) -> DiagnosticState:
    """Run all agents with lens-aware weighting"""
    
    # Build context that includes both layers
    context = {
        "sector": state.sector,                    # My Sector
        "lenses": state.eye_lenses,                # &Eye Lenses
        "primary_objective": state.eye_lenses[0].name,
        "priority_areas": state.priority_areas,
    }
    
    # Run agents in parallel with weighted depth
    tasks = []
    for agent in selected_agents:
        weight = state.agent_weights[agent.id]
        
        # Higher weight = more depth in analysis
        depth_config = {
            "analysis_depth": "deep" if weight > 1.2 else "standard" if weight > 0.9 else "light",
            "recommendation_count": int(5 * weight),  # More recommendations for priority agents
            "evidence_detail": "high" if weight > 1.2 else "standard",
        }
        
        task = agent.analyze(
            data=state.responses,
            context=context,
            depth=depth_config
        )
        tasks.append(task)
    
    # Parallel execution
    outputs = await asyncio.gather(*tasks)
    
    return state.with_outputs(outputs)
```

### Lens-Aware Recommendation Prioritization

```python
def prioritize_recommendations(
    recommendations: List[Recommendation],
    lenses: List[EyeLens]
) -> List[Recommendation]:
    """Sort recommendations by lens relevance"""
    
    def lens_score(rec: Recommendation) -> float:
        score = 0
        for i, lens in enumerate(lenses):
            weight = [1.0, 0.6, 0.3][i]  # Primary, secondary, tertiary
            
            # Check if recommendation keywords match lens priority keywords
            keyword_matches = len(
                set(rec.keywords) & set(lens.priority_keywords)
            )
            score += keyword_matches * weight
            
            # Check if recommendation's agent is prioritized by this lens
            agent_weight = lens.agent_weights.get(rec.source_agent, 1.0)
            score += (agent_weight - 1.0) * weight
        
        return score
    
    # Sort by lens relevance, then by impact
    return sorted(
        recommendations,
        key=lambda r: (lens_score(r), r.impact_score),
        reverse=True
    )
```

---

## Part 7: Client Types and Their Typical Lenses

| Client Type | Typical &Eye Lenses | Why |
|-------------|---------------------|-----|
| **SME Owner** | Export, Profitability, Succession, Investment | Their personal business goals |
| **Bank** | Investment Attraction, Sale Readiness | Loan/credit assessment |
| **Development Org (UNIDO, GIZ)** | Export, Employment, Sustainability | Their mandate objectives |
| **Donor** | Employment, Local Development, Sustainability | Impact measurement |
| **Government** | Employment, Local Development, Export | Policy objectives |
| **Accelerator** | Investment Attraction, Digital, Growth | Portfolio development |
| **Private Equity** | Sale Readiness, Profitability, Operational Excellence | Investment screening |

---

## Part 8: Summary

### The New Architecture in One Diagram

```
┌─────────────────────────────────────────────────────────────────────────┐
│                                                                         │
│                           USER CONFIGURES                               │
│                                                                         │
│         ┌──────────────────┐        ┌──────────────────┐               │
│         │   MY SECTOR      │        │   &EYE LENS      │               │
│         │   (Industry)     │        │   (Objective)    │               │
│         │                  │        │                  │               │
│         │  Food Processing │        │ Export Readiness │               │
│         │                  │        │                  │               │
│         │  → Standards     │        │  → Priorities    │               │
│         │  → Regulations   │        │  → Depth         │               │
│         │  → Benchmarks    │        │  → Framing       │               │
│         └────────┬─────────┘        └────────┬─────────┘               │
│                  │                           │                          │
│                  └───────────┬───────────────┘                          │
│                              │                                          │
│                              ▼                                          │
│         ┌─────────────────────────────────────────────────┐            │
│         │              COMBINED CONTEXT                    │            │
│         │                                                  │            │
│         │  "Analyzing a FOOD PROCESSING company           │            │
│         │   through the lens of EXPORT READINESS"         │            │
│         └─────────────────────────────────────────────────┘            │
│                              │                                          │
│                              ▼                                          │
│         ┌─────────────────────────────────────────────────┐            │
│         │              THE PANTHEON                        │            │
│         │                                                  │            │
│         │    Marvin   Graham   Ricardo   Lovelace   Mayo  │            │
│         │      █        ██      ████        █        █    │            │
│         │                                                  │            │
│         │    (Weighted by &Eye Lens)                      │            │
│         └─────────────────────────────────────────────────┘            │
│                              │                                          │
│                              ▼                                          │
│         ┌─────────────────────────────────────────────────┐            │
│         │           LENS-FRAMED OUTPUT                     │            │
│         │                                                  │            │
│         │  "Your Export Readiness Score: 62/100"          │            │
│         │  "Top 3 actions to become export-ready..."      │            │
│         └─────────────────────────────────────────────────┘            │
│                                                                         │
└─────────────────────────────────────────────────────────────────────────┘
```

### Key Principles

1. **My Sector** loads WHAT the system knows (industry context)
2. **&Eye Lens** shapes HOW the system thinks (objective focus)
3. Together they make the diagnostic truly **"Made for You"**
4. The lens is visible throughout — user always sees their objective front and center
5. Recommendations are prioritized by lens relevance
6. Report is framed around achieving the stated objective

---

## Appendix: Glossary

| Term | Definition |
|------|------------|
| **My Sector** | The industry/sector the SME operates in (Food, Pharma, Textiles). Loads relevant standards, regulations, and benchmarks. |
| **&Eye (The Lens)** | The client's transformation objective — their burning desire, their reason for seeking help. Shapes priorities, depth, and framing throughout the workflow. |
| **The Pantheon** | The 10 AI specialist agents that perform analysis |
| **The &I** | The human intelligence layer — expert validation when needed |
| **Agent Weighting** | How much depth/priority an agent gets based on the selected &Eye lens |
| **Lens-Framed Output** | Report and recommendations structured around the client's stated objective |

---

*Document Version 2.0 — Restructured to incorporate Alla's field-proven lens concept*
