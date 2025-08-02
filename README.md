# greenhill-investor-assistant
Investor-facing GPT assistant for Green Hill Canarias – interactively exploring the 2025 Strategic Plan.
# Green Hill GPT – Investor Assistant

💬 A Streamlit-powered AI assistant that allows investors to query the 2025 Strategic Plan for Green Hill Canarias in real time, powered by GPT-4.

## 🧠 Key Features
- Ask questions about CAPEX, governance, GMP certification, or shareholder rights
- Built with the latest OpenAI SDK (`openai>=1.0.0`)
- Fully branded with Green Hill logos and style
- Mobile and document-ready with a scannable QR code
- Secure GPT key management via Streamlit Cloud Secrets

## 🚀 How to Deploy

1. Sign in at [Streamlit Cloud](https://streamlit.io/cloud)
2. Connect this repo and deploy `greenhill_gpt_portal_sdk_v1.py`
3. Set your OpenAI key in **Secrets** like this:
OPENAI_API_KEY = "sk-xxxxxxxxxxxxxxxxxxxxxxxx"

yaml
Copiar
Editar

Your app will launch automatically and provide a live investor experience.

## 📎 Files Included

| File | Purpose |
|------|---------|
| `greenhill_gpt_portal_sdk_v1.py` | Main GPT app |
| `logo.png` | Primary Green Hill logo |
| `greenhill_variant.png` | Visual variant |
| `requirements.txt` | Streamlit + OpenAI SDK |
| `GreenHill_GPT_Investor_QR_FINAL.png` | QR code for sharing |
| `README.md` | You’re reading it ✅ |

## 🌿 About Green Hill Canarias
Green Hill is an EU-GMP-aligned pharmaceutical cannabis company based in the Canary Islands, backed by ZEC incentives, a vertically integrated facility, and a next-gen AI-driven operational model.

---
