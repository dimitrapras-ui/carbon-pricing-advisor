# Internal Carbon Price Advisor

An AI-powered decision support tool that helps companies set evidence-based internal carbon prices.

![Status](https://img.shields.io/badge/status-prototype-blue)
![Python](https://img.shields.io/badge/python-3.14-blue)

## 🎯 The Problem

1,800+ companies use internal carbon pricing, but most set prices that are:
- **10x too low** (median $25/ton vs EPA's $252/ton social cost)
- **Not aligned with their climate targets** (prices don't drive enough reduction)
- **Set without methodology** (copying peers or guessing)

Traditional options: hire expensive consultant ($50K-500K) or wing it.

## 💡 The Solution

Free, 5-minute tool that generates consultant-quality carbon pricing recommendations using:
- **Multi-step analysis engine** (8 analytical modules)
- **Real calculations** (price elasticity modeling, abatement cost curves)
- **Proprietary database** (49 companies + CDP's 3,600 company dataset)
- **Claude AI** (for synthesis and scenario generation)

## 🧠 How It Works

**Input:** 6 questions (industry, emissions, target, location, size, current ICP)

**Analysis Pipeline:**
1. **Company Profile** → Assesses ambition, capacity, pressure
2. **Target Math** → Calculates price needed using elasticity models
3. **Regulatory Risk** → Maps location to current/future carbon pricing
4. **Peer Benchmarking** → Positions vs 49 analyzed companies
5. **Synthesis** → AI combines all factors into recommendation
6. **Sensitivity** → 6 what-if scenarios
7. **Trajectory** → Year-by-year path to target
8. **Risk Flags** → Identifies problems + mitigation strategies

**Output:** Comprehensive recommendation with honest accountability analysis

## ✨ Key Features

- **Honest Accountability:** Shows gap between target and what price will actually achieve
- **Show Your Work:** Full transparency on calculation methodology
- **Sensitivity Analysis:** 6 scenarios (regulation changes, tech breakthroughs, etc.)
- **Year-by-Year Path:** 2026→2030 trajectory with specific actions
- **Risk Flags:** 7 potential issues with mitigation strategies
- **Peer Intelligence:** Competitive positioning vs industry leaders/laggards

## 🔬 Technical Implementation

**Backend:**
- Python 3.14
- Anthropic Claude API (Sonnet 4)
- Mathematical modeling (price elasticity, MAC curves)

**Frontend:**
- Vanilla HTML/CSS/JavaScript
- Responsive design
- Expandable module architecture

**Data Sources:**
- Barron & Prassa (2025) peer-reviewed framework
- CDP Global Carbon Price Report (2,012 companies)
- Manual analysis of 49 corporate sustainability reports
- Regulatory database (53 national + 40 subnational jurisdictions)

## 📊 Sample Output

**For a tech company (50k tons, 50% by 2030, California):**
- Recommended: **$95/ton** (escalate 3% annually)
- Reality Check: Achieves 42%, not 50% (8pp gap)
- vs Peers: 3.3x above median, near Microsoft's $100/ton
- Regulatory Prep: Ah
