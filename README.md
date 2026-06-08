# Project Monitor Hub

A centralized **Infrastructure-as-Code (IaC)** monitoring microservice designed to maintain the uptime of my distributed web application portfolio.

## Architecture
- **Purpose**: Automates health checks for 6+ live projects hosted across Render, Streamlit, and Hugging Face.
- **Technology**: GitHub Actions (Scheduled Cron Workflows).
- **Strategy**: Executes `curl` head requests every 10 minutes to prevent service "cold-starts" (spin-downs) on free-tier hosting platforms.

## Monitored Services
| Project | Platform |
| :--- | :--- |
| Intel Flow Tech (Backend) | Render |
| Investment Decision Support | Hugging Face |
| Intrinsic Valuation Engine | Render |
| Core Inventory System | Render |
| Cyberbullying Detector | Streamlit |
| Data Science Portfolio | Streamlit |

*This repository manages infrastructure centrally to ensure high availability for my portfolio projects.*
