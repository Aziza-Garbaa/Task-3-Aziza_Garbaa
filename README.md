# Task 3: The Knowledge Analyst (RAG Concepts) 

## Project Overview
This project simulates a **Retrieval-Augmented Generation (RAG)** workflow for document intelligence. The objective was to analyze a high-density corporate document (Tesla’s 2024 Form 10-K, +140 pages) and extract critical insights without "hallucinations" by forcing the AI to provide verifiable sources for every claim.

## The Mission
- **Document Intelligence:** Processing a complex legal and financial report.
- **Hallucination Prevention:** Engineering prompts that mandate specific page citations.
- **Automated Extraction:** Creating a structured dashboard for Stakeholders, Dates, and Risks.

## The Tool
- **Model:** Claude 3.5 Sonnet (known for high precision in long-context window analysis).
- **Technique:** RAG-simulated prompting.

## Knowledge Analyst Dashboard (Output)

### 1. Key Stakeholders
- **Executives:** Elon Musk (CEO), Vaibhav Taneja (CFO), and the Board of Directors. [Source: Page 108]
- **Legal Entities:** Tesla (Shanghai) Co., Ltd., Tesla Motors Netherlands B.V. [Source: Pages 103-105]

### 2. Critical Dates
- **Fiscal Year End:** December 31, 2024. [Source: Page 1]
- **Filing Date:** January 29, 2025. [Source: Page 108]
- **Trial Date (Lawsuit):** September 15, 2025. [Source: Page 86]

### 3. Top 3 Risk Factors
- **Risk 1:** Production Delays & Manufacturing Cost Control. [Source: Page 13]
- **Risk 2:** Insufficient Warranty Reserves. [Source: Pages 22-23]
- **Risk 3:** Intense Global Competition in the EV market. [Source: Pages 16-17]

## Specific Inquiry: Warranty Obligations
**Query:** How does Tesla estimate warranty costs?
**Result:** Tesla accrues a reserve based on the "best estimate of projected costs to repair or replace items," calculated using historical claim data. The total accrued warranty rose to **$6,716M** in 2024. [Source: Page 35, 72]

## Technical Conclusion
By implementing strict **Citation Constraints**, the AI successfully acted as a reliable analyst. This workflow ensures that business decisions are based on actual document data rather than the model's creative training data, which is the core principle of RAG systems.
