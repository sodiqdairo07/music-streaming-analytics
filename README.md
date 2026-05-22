# 🎵 Music Streaming Performance Analytics
### DataDNA Dataset Challenge, May 2026

![Dashboard Preview](Streaming_analysis_may_challenge_final-page-001__1_.jpg)

## What This Project Is About

I built this dashboard for the DataDNA May 2026 Challenge using a music streaming dataset. But honestly, I didn't want to just visualise the data; I wanted to treat it like a real business problem. The kind where decisions actually cost money if you get them wrong.

So before touching Power BI, I spent time reading through the dataset and asking three questions that felt genuinely important: where is revenue bleeding out, which users are actually worth keeping, and which markets are being left behind?

Everything in this dashboard flows from those three questions.

## The Dashboard

Built entirely in **Power BI Desktop** as a single-page report. The goal was to make it the kind of dashboard where someone can open it, spend 60 seconds on it, and walk away knowing exactly what the business needs to do next.

### What's Inside

| Section | What It Shows |
|---|---|
| KPI Cards | MRR, ARPU, Churn Rate, Active Users, Listen Hours at a glance |
| MRR Trend | Monthly recurring revenue growth from 2021 to 2024 |
| Geographic Map | Revenue distribution across 10 markets by bubble size |
| Cohort Retention | How well each signup month retains users through month 12 |
| Tier Preference Heatmap | How subscription tier preferences vary by country |
| Skip Rate Analysis | Engagement comparison across Free, Premium, and Family tiers |
| Key Findings | 5 actionable recommendations with supporting numbers |

## Tools & Techniques

**Power BI Desktop** handled everything from data modelling to the final layout. **DAX** was used for custom measures including MRR, ARPU, churn rate, skip rate, and cohort retention; all segmented properly by subscription tier so comparisons were meaningful. A **Matrix Visual** powered the cohort analysis, tracking users from signup through 12 months. **Conditional Formatting** on the tier preference table made market concentration patterns visible without needing an extra chart. A **Bubble Map** handled the geographic revenue spread across 10 markets.


## What The Data Actually Said

### 1. The churn rate is the elephant in the room
**66.1% churn** with over **$2,400 in monthly revenue at risk**. That number shapes everything else. A platform growing MRR by 43% year-on-year but losing two-thirds of its users is running on a leaky bucket.

### 2. Free users aren't disengaged; they're under-served
Free tier skip rate sits at **20.0%** vs **10.6% for Premium**. That's not a content problem. That's what happens when users don't have access to the same curation and features that paying users do. The gap is wide enough that closing it even partially would move the needle on conversions.

### 3. Some markets are seriously underperforming
The bottom 3 markets generate roughly **51% of what the top 3 produce**. Canada's numbers stood out; the performance gap suggests there's a working playbook somewhere that isn't being replicated. The model puts the uplift potential at **$945 MRR** if the right approach gets rolled out properly.

### 4. The fraud problem is bigger than the headline suggests
Half the user base is flagged as fraudulent, generating **70% of sessions**; a **1.4× over-index**. Every headline metric (ARPU, engagement, session counts) is likely overstated by around **30%**. This isn't just a data quality issue. It's a business integrity issue that affects every decision made from this data.

### 5. The recommendation algorithm is working against itself
Recommended tracks skip at **13.2%**. Organic discovery skips at **12.7%**. The algorithm that's supposed to help users find music they love is actually performing worse than chance. At scale, that gap adds up fast; and it's fixable.

## Key Metrics At A Glance

| Metric | Value |
|---|---|
| Active MRR (Dec 2024) | $8.14K |
| MRR Growth (12 months) | +43.3% |
| Churn Rate (LTM) | 66.1% |
| Revenue at Risk | $2,432 |
| Total Active Users | 961 |
| Users After Fraud Filter | 471 |
| Total Listen Hours | 5.75K |
| Platform Skip Rate | 12.9% |
| Total Sessions (4 years) | 224K |
| Markets Covered | 10 |

## Files In This Repo

📁 music-streaming-analytics
├── 📊 Streaming_analysis_may_challenge_final.pdf
├── 🖼️  Streaming_analysis_may_challenge_final-page-001.jpg
└── 📄 README.md


## About This Challenge

The DataDNA Dataset Challenge is a monthly data visualisation competition run by **Onyx Data**. Participants are given a real dataset and asked to build a dashboard or visualisation that uncovers meaningful insights. Entries are judged on how well they visualise the data, define key indicators, find insights, and define calculations and metrics.

**Challenge:** DataDNA May 2026, Music Streaming Performance Analytics  
**Tool Used:** Microsoft Power BI  
**Dataset:** DataDNA Music Streaming Dataset

## Connect

If you found this useful or want to talk data, feel free to connect on LinkedIn or drop a comment on the submission post.
