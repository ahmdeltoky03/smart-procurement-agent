# Smart Procurement Agent

AI multi-agent system for automated product procurement and price comparison.

## Example Output

**Live Demo:** View the generated procurement report
- 📄 [View Interactive Report](https://htmlpreview.github.io/?https://github.com/ahmdeltoky03/smart-procurement-agent/blob/main/ai-agent-output/step_4_procurement_report.html)
- [Download HTML](ai-agent-output/step_4_procurement_report.html)
- [View JSON Data](ai-agent-output/)

## Workflow

![Workflow](workflow.jpg)

## System Architecture
```
┌─────────────────────────────────────────────────────┐
│  1. Search Queries Agent                            │
│     Generates targeted search queries               │
└──────────────────┬──────────────────────────────────┘
                   ▼
┌─────────────────────────────────────────────────────┐
│  2. Search Engine Agent                             │
│     Performs web searches using Tavily              │
└──────────────────┬──────────────────────────────────┘
                   ▼
┌─────────────────────────────────────────────────────┐
│  3. Web Scraping Agent                              │
│     Extracts product data using ScrapeGraph         │
└──────────────────┬──────────────────────────────────┘
                   ▼
┌─────────────────────────────────────────────────────┐
│  4. Report Author Agent                             │
│     Creates comprehensive HTML reports              │
└─────────────────────────────────────────────────────┘
```

## What It Does

Automates product research, price comparison, and generates procurement reports using 4 AI agents working together.

## Features

- Generates smart search queries
- Searches multiple e-commerce sites
- Extracts product details automatically
- Compares prices and specifications
- Creates professional HTML reports

## Tech Stack

CrewAI, OpenRouter, Tavily Search, ScrapeGraph, Python

## Contact

For questions, collaborations, or contribution opportunities, feel free to reach out:
- **Email:** [ahmdeltoky4@gmail.com](mailto:ahmdeltoky4@gmail.com)  
- **LinkedIn:** [linkedin.com/in/ahmed-eltokhy-7a7901383](https://www.linkedin.com/in/ahmed-eltokhy-7a7901383)

---

Built with AI Agents and CrewAI