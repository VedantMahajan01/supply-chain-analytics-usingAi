# supply-chain-analytics-usingAi
End-to-End Supply Chain Analytics Project Using AI Tools

#  Project Overview 
This project focuses on solving inventory management challenges in a supply chain using AI-powered analytics and automation tools. I implemented a workflow that automates data ingestion and enables real-time analytics.

# Tech Stack

| Layer | Tool |
|-------|------|
| Automation | n8n |
| Database | PostgreSQL (Supabase) |
| Analytics | Quadratic AI |

Spreadsheet (via Email) → n8n (automation) → PostgreSQL (hosted on Supabase) → Quadratic (AI-powered analysis)

n8n → Automated ingestion of incoming order data from emails into PostgreSQL.
Supabase → Cloud-hosted PostgreSQL database.
Quadratic → Pulled data from PostgreSQL, performed analysis, and generated KPIs & insights.
Validation → Quadratic output cross-verified with Supabase data.

# Architecture
Email (Order Data) → n8n (Automation) → PostgreSQL on Supabase → Quadratic AI (Analysis)

<img src="Supply-Chain-Analytics-ai/Screenshots/n8n Workflow.png" width="800">

# What This Project Does
- Automatically picks up incoming order data from emails using n8n workflows.
- Loads and stores structured data into a cloud PostgreSQL database on Supabase.
- Performs data analysis in Quadratic AI to identify trends, patterns and data quality issues in inventory data.

# Key Learnings
- Built a real-world automated data pipeline from scratch
- Gained hands-on experience with cloud database management (Supabase + PostgreSQL)
- Learned how to integrate no-code automation (n8n) with AI-powered analytics
- Understood how supply chain data flows across systems end-to-end








