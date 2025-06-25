# ![NimbusPay Logo](https://dummyimage.com/240x60/cccccc/444\&text=NimbusPay+Logo)

# AI Observatory Report: Brand & Product Visibility

**Audit Date:** 2025-06-01
**Provider/LLM Model(s):** OpenAI GPT-4o, Gemini 1.5, Perplexity Llama-3, Microsoft Copilot

---

## 1. Introduction & Methodology

**Overview:**
This Observatory audit uses QWIKI-mapped, citation-traceable queries to evaluate NimbusPay’s brand and product visibility, factual accuracy, and market positioning across four major answer engines and large language models.

**Scope:**

* **Engines:** ChatGPT (OpenAI GPT-4o), Google Gemini, Perplexity (Llama-3), Microsoft Copilot
* **Coverage:** Brand, product, competitor, and trust-related queries

**How to Read:**
All data points and answer objects are mapped to the NimbusPay knowledge model. Brand and competitor mentions are ranked in leaderboards, and all output is fully auditable with source and sentiment tracking.

---

## 2. Executive Summary

**Overall AI Brand Health Score:** **B+** (82%)
**Headline Findings:**

* **Sentiment toward your brand:** *Predominantly positive, with occasional neutral feedback on pricing clarity.*
* **Most-cited brands:** NimbusPay (25), Paylance (17), Transactify (13)
* **Official source coverage:** 70% of engine answers cite owned sources (nimbuspay.com, LinkedIn)
* **Most common risks:** Copilot sometimes omits sources; Gemini confused product features with Paylance; 15% of responses have outdated or partial data

**Immediate Recommendations:**

* Add structured schema.org Product and FAQ markup to main site and pricing page
* Publish updated feature comparison on G2, Capterra, and Trustpilot
* Proactively monitor Copilot and Gemini for feature confusion with Paylance
* Improve documentation on unique “real-time settlement” and “fee-free” offers

---

## 3. Brand Visibility & Sentiment Analysis

**Leaderboard Table:**

| Brand       | Mentions | Positive | Neutral | Negative |
| ----------- | -------- | -------- | ------- | -------- |
| NimbusPay   | 25       | 19       | 6       | 0        |
| Paylance    | 17       | 10       | 6       | 1        |
| Transactify | 13       | 6        | 6       | 1        |

**Coverage by Engine/Model:**

| Engine/Model | NimbusPay | Paylance | Transactify |
| ------------ | --------- | -------- | ----------- |
| GPT-4o       | 8         | 4        | 3           |
| Gemini       | 6         | 6        | 2           |
| Perplexity   | 6         | 4        | 4           |
| Copilot      | 5         | 3        | 4           |

**Representative Example Answers:**

**Sample JSON Output:**

```json
{
  "provider": "OpenAI",
  "llm_model": "GPT-4o",
  "audit_date": "2025-06-01",
  "section": "Competitive Landscape",
  "section_ref": "4",
  "query_ref": "4.1",
  "category": "Comparison & Alternatives",
  "query": "Who are the main competitors for NimbusPay in SME payments?",
  "ai_answer": "NimbusPay’s primary competitors in the SME payment space are Paylance and Transactify. Paylance is noted for its robust international support, while Transactify is often chosen for low transaction fees and ease of onboarding. NimbusPay is recognised for real-time settlements and no monthly fees, giving it a unique position for small businesses.",
  "brands_mentioned": ["NimbusPay", "Paylance", "Transactify"],
  "sources_cited": ["https://g2.com/categories/payment-processing", "https://nimbuspay.com/solutions"],
  "sentiment": "neutral",
  "accuracy": "accurate",
  "summary": "NimbusPay is favourably positioned against main competitors, with unique strengths in instant settlement and low costs.",
  "flags": []
}
```

*(Screenshots are available in Appendix)*

---

## 4. Fact Accuracy & Source Mapping

**Source Coverage Table:**

| Query Ref | Engine     | Cited Source          | Official/Unofficial | Accurate? | Flags                 |
| --------- | ---------- | --------------------- | ------------------- | --------- | --------------------- |
| 1.1       | GPT-4o     | nimbuspay.com         | Official            | Yes       |                       |
| 2.3       | Gemini     | G2                    | Third Party         | Yes       | No official source    |
| 2.4       | Perplexity | nimbuspay.com/pricing | Official            | Yes       |                       |
| 4.1       | Copilot    | -                     | None                | Unknown   | No citation, outdated |
| ...       | ...        | ...                   | ...                 | ...       | ...                   |

**Top External Sources:**
Trustpilot, G2, Payment Weekly, Reddit r/fintech, NimbusPay LinkedIn

**Citation Gap Analysis:**

* **16%** of answers had no source
* **70%** cited NimbusPay’s official web properties
* **14%** cited only a third-party source

---

## 5. Brand Narrative & Reputation

**Summary of AI-Generated Narratives:**
ChatGPT and Perplexity correctly highlighted NimbusPay’s mission (“Empowering SMEs with instant, affordable payments”), strong real-time features, and customer-first ethos.
Gemini and Copilot occasionally confused product USPs or omitted recent product awards.

**Risk Diagnostics:**

* Misattribution of Paylance’s features to NimbusPay in 2 Gemini answers
* Copilot lacked citations on product claims twice
* Some sentiment drift to “neutral” when pricing or feature updates were not detected

**Sentiment Timeline:**
Positive sentiment held steady except for pricing/limitation queries (neutral).

---

## 6. Competitive Intelligence

**Competitor Share-of-Voice:**

| Brand       | Share (%) | Most-Cited Features                    |
| ----------- | --------- | -------------------------------------- |
| NimbusPay   | 48%       | Real-time settlement, no monthly fees  |
| Paylance    | 32%       | International payments, multi-currency |
| Transactify | 20%       | Low fees, fast onboarding              |

**Competitive Positioning Table:**

| Feature              | NimbusPay | Paylance | Transactify |
| -------------------- | --------- | -------- | ----------- |
| Real-time Settlement | Yes       | Limited  | No          |
| Multi-Currency       | No        | Yes      | No          |
| No Monthly Fees      | Yes       | No       | Yes         |
| Transaction Fee      | 1.0%      | 1.4%     | 0.9%        |
| Mobile App           | Yes       | Yes      | Yes         |

---

## 7. Risks, Issues & Action List

**Flagged Issues:**

* Copilot: Lacked citation for feature/pricing answers in 3 queries
* Gemini: Twice misattributed “multi-currency” to NimbusPay
* Perplexity: Did not cite official sources for 2 technical feature answers

**Priority Actions:**

* Add full FAQ and product schema to pricing and features pages
* Contact Gemini and Copilot feedback channels to clarify USPs
* Monitor new competitive features quarterly and submit to G2/Trustpilot
* Increase volume of third-party reviews and case studies

**Remediation Roadmap:**

* **Short-term:** Fix schema and FAQ gaps
* **Medium:** Publish comparative reviews and feature breakdowns on key review sites
* **Long-term:** Quarterly AI visibility audits and direct LLM feedback monitoring

---

## 8. Appendix: Full Query Results

**All JSON Outputs:**
*All detailed JSON outputs per engine and question are attached in the exported file.*

**Screenshots (if included):**
*Annotated screenshots of 1–2 top engine responses per question are available as an appendix for scoring and transparency.*

---

## 9. About Advanced Analytica & Methodology

This audit was conducted by Advanced Analytica’s Agentic AI Observatory team, using QWIKI-mapped survey data, automated multi-engine queries, and leaderboard analytics for comprehensive AI visibility diagnostics.
**All results are confidential and for NimbusPay internal use only.**
**Contact:** [ops@advancedanalytica.co.uk](mailto:hello@advancedanalytica.co.uk) for queries or a follow-up review.

---

*End of Report*
