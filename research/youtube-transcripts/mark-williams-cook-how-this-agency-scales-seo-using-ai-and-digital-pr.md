### Mark Williams-Cook

# Title: How This Agency Scales SEO Using AI and Digital PR

URL: https://www.youtube.com/watch?v=m7OyGF3mU0g&list=PLQcRJfpdUsd8&index=6

Note: This video is 46:31 long so I didn't insert the full transcript here and insert the extracted materials only. The original transcript is in /research/files/mark-williams-cook.txt

# YouTube Transcript Summary: Mark Williams-Cook
**Expert:** Mark Williams-Cook (Director at Candour & Founder of AlsoAsked)
**Topic:** AI Search Optimization (GEO), LLM Grounding, & Digital PR at Scale

---

## 1. Executive Summary
Traditional search engine optimization is evolving into optimization for conversational LLMs and agentic search engines. This framework details how Candour uses AI to expand flat keywords into deep conversational context, scales off-page visibility through synthesized Digital PR, and manages technical architectures to ensure brands are successfully retrieved, cited, and summarized by modern AI platforms.

---

## 2. Core Concepts & Technical Architecture

### The Intermediary Intent Decoding Layer
* **Traditional SEO:** The optimization effort sits directly between a single user intent (the typed query) and the search engine's ranking algorithm.
* **AI Search (LLM-Driven):** An interactive conversational layer sits in the middle. The user engages in a multi-turn, conversational dialogue with the AI (e.g., ChatGPT, Gemini, Perplexity). 
* **Universal Intent Decoder:** The AI acts as a decoder that translates messy, highly personalized, and long-form human dialogue into precise, traditional web search queries (grounding requests) which it then executes on classic indices (like Bing or Google).

### Grounded vs. In-Model Queries
1.  **Grounded Queries:** Occur when the LLM triggers a live web search to fulfill a user request. Traditional SEO can heavily influence this because the AI retrieves active top-ranking search results to synthesize its answer.
2.  **In-Model Queries:** Occur when the LLM answers entirely using its internal pre-trained weights without accessing the live web. Influencing this requires altering the base training data or heavy reinforcement learning, which is a slow and difficult process.

---

## 3. The 7-Step Keyword Research Framework for AI Platforms

To transition flat keyword lists into the multi-turn conversational paths used by AI engines, deploy the following structured API pipeline:
[Traditional Keywords] ➔ [Personalization Context] ➔ [Conversation Mapping] ➔ [Candidate Prompts] ➔ [Grounding Prediction] ➔ [SEO Action & Gap Analysis]

* **Step 1: Traditional Keywords:** Compile your existing foundational keyword list.
* **Step 2: Personalization Context:** Transform flat terms into conditional, highly situational human questions. Use a structured prompt via LLM APIs that merges your keywords with target buyer personas and specific friction points.
* **Step 3: Conversation Mapping:** Forecast the subsequent questions a user will ask once their initial question is solved. Map the logical web of the user's conversational journey.
* **Step 4: Candidate Prompts:** Document the exact prompt strings real users are sending to platforms like ChatGPT or Claude for your product vertical.
* **Step 5: Grounding Prediction:** Classify whether a specific prompt will trigger the LLM to search the web (grounded) or answer natively (in-model).
* **Step 6: Grounding Requests Exploration:** Use tracking tools (like PromptWatch or citation logs) to capture the exact traditional search strings the AI fires behind the scenes.
* **Step 7: Gap Analysis and SEO Action:** Run a standard gap analysis against these grounding queries to find coverage holes in your current content architecture.

---

## 4. Off-Site Synthesis & The New Digital PR Blueprint

AI search platforms do not merely rank a single authoritative page; they retrieve the top 10, 20, or 50 web results and *synthesize* a consensus answer across them.

* **The Co-Citation Requirement:** Being the #1 blue link on your own domain is no longer sufficient. If your brand is not mentioned across the top authoritative third-party resources scanned by the LLM, you will be omitted from the synthesized AI answer blocks.
* **Entity-First Digital PR:** Focus Digital PR efforts on establishing strong entity relationships and authority. Secure highly relevant external press, forum discussions (Reddit/Quora), and industry reviews. The AI reads this multi-site footprint to build its core perception of your brand's trustworthiness and authority.

---

## 5. Site Health & Optimization Checklist

* **Optimize for Follow-on Questions:** Always resolve the primary user intent and immediately answer the next logical follow-up question on the exact same page. Reducing "time to result" stops the user from continuing a search loop, signalizing extreme content depth to crawler models.
* **Prune Trust-Diluting Content:** Low-value, thin pages, and outdated filler articles dilute your site-wide *Site Quality Score*. Consolidate, merge, or delete anything that does not clearly satisfy deep user intents. Thin content weakens overall crawling entity signals.
* **Track Non-Click Metrics:** Traditional organic click attribution is declining. Transition KPIs toward tracking impression-style visibility, brand sentiment, and mention velocity inside LLM summaries and citation blocks.
* **Deliberately Build Direct Brand Demand:** Direct PR and product messaging must align

---

## 📝 Strategic Summary

Drawing from over two decades of agency experience, this session outlines how to build an organic growth engine that out-executes competitors without bloating operational overhead. The core strategy hinges on high-signal curation and intent mapping. By filtering out algorithm noise (the "vanity metrics" of SEO) and upgrading from basic keyword matching to semantic entity mapping, growth marketers can build lean, highly authoritative content architectures that scale sustainably.

---

## 💡 Key Takeaways & Playbook Insights

### Key Takeaways

* **Ruthless Signal-to-Noise Filtering**: Most industry updates are distraction filler (e.g., Google changing a SERP font). High-performing growth loops focus exclusively on core updates that fundamentally move the bottom line.
The Keyword Matching Trap: Churning out pages based purely on individual keyword lists creates internal content cannibalization. Modern SEO requires designing strategic, comprehensive site structures that satisfy searcher intents globally rather than chasing isolated search queries.
* **Holistic Technical & PR Integration**: Content production cannot exist in a silo. True organic lift happens when high-signal content planning is tightly integrated with technical health (crawlability, log analytics) and digital PR/link velocity.

### Playbook & Execution Insights

**The Workload Efficiency Loop**:
Filter Out Update Noise ➔ Map Comprehensive Intent Clusters ➔ Unify Technical & Digital PR Assets ➔ Execute Lean, High-Signal Iterations

* **Work Smarter, Not Harder**: Avoid increasing your content team's manual workload. Instead, reposition their focus toward strategic consulting and intent clustering to achieve a higher ROI per page published.
* **Curation as a Moat**: Building assets like hyper-focused, low-fluff industry digests (e.g., Core Updates) captures high-intent B2B audiences who suffer from information fatigue.
* **Log File Utilization**: Leverage AI tools as log analyzers to review server logs. This uncovers exactly how modern search and AI crawlers interact with your technical architecture before visibility drops hit your standard analytics dashboards.