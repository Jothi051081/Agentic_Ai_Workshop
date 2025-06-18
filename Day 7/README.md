# 🧠 Campus–Company Ecosystem Compatibility Mapper

This AI-powered system aligns campus placement efforts with companies that best fit institutional strengths, improving hiring outcomes and reducing mismatches.

## 📌 Problem Statement

Not all companies are the right cultural or technical fit for every campus. This project analyzes campus strengths and company profiles using Generative AI and intelligent agents to identify ideal placement partnerships.

---

## ⚙️ Architecture Overview

### ✅ Framework Used:
- **LangChain** – For chaining prompts, building agents, and managing tools.

### 🤖 Agents:
1. **Campus History Analyzer Agent**  
   - Analyzes mock campus data (skills, internship experience, communication styles).

2. **Company Fit Profiler Agent**  
   - Retrieves and processes company info via scraping and search tools.

3. **Compatibility Scorer Agent**  
   - Compares campus strengths with company data to calculate fit scores.

4. **Priority Agent**  
   - Sorts companies based on score to suggest top 3 high-fit organizations.

### 🛠️ Tools Used:
- **Web Scraper Tool** – For collecting company data from job sites.
- **Search Tool** (e.g., Bing, Google) – For real-time company insights.

---

## 📊 Output
- Detailed compatibility analysis between campus strengths and company profiles.
- Compatibility scores (0–100) for each company.
- Justification and qualitative reasoning.
- Final prioritized company list for targeted outreach.

---

## 🚀 How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/yourusername/campus-company-mapper.git
   cd campus-company-mapper
