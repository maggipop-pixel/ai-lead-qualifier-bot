# 🤖 AI Lead Qualifier Bot

Automated lead qualification system powered by ChatGPT that analyzes sales prospects and generates actionable insights in seconds.

![Status](https://img.shields.io/badge/status-active-success.svg)
![License](https://img.shields.io/badge/license-MIT-blue.svg)

## 🎯 What It Does

This bot automatically:
- 📊 Reads lead data from Excel files
- 🤖 Analyzes each prospect using ChatGPT API
- ⭐ Assigns quality scores (1-10)
- 🎯 Determines priority level (High/Medium/Low)
- 💡 Recommends specific next actions
- 📥 Exports results to a new Excel file

**Time saved:** What takes 5-10 minutes per lead manually now takes 10 seconds with AI analysis.

## 💼 Business Value

### Problem
Sales teams waste hours manually qualifying leads:
- ⏰ 10-15 min per lead evaluation
- 📉 Inconsistent qualification criteria
- 🔄 Repetitive manual work
- 💸 Missed opportunities due to delayed follow-up

### Solution
Automated AI-powered qualification:
- ⚡ Process 100 leads in 2 minutes
- 🎯 Consistent, data-driven scoring
- 🤖 Instant actionable recommendations
- 💰 Focus sales time on high-value prospects

### ROI
- **Manual process:** 100 leads × 10 min = 16.7 hours
- **With this bot:** 100 leads = 2 minutes
- **Time saved:** 99% reduction in qualification time

## ✨ Features

- ✅ Excel file input/output (familiar workflow)
- ✅ AI-powered analysis using GPT-3.5-turbo
- ✅ Customizable scoring criteria
- ✅ Batch processing capability
- ✅ Detailed reasoning for each score
- ✅ Priority-based sorting
- ✅ Cost-effective (<$0.01 per lead)

## 🛠️ Tech Stack

- **Language:** JavaScript (Node.js)
- **AI:** OpenAI GPT-3.5-turbo API
- **Data Processing:** xlsx library
- **Runtime:** Node.js v24+

## 📦 Installation
```bash
# Clone repository
git clone https://github.com/maggipop-pixel/ai-lead-qualifier-bot.git

# Navigate to directory
cd ai-lead-qualifier-bot

# Install dependencies
npm install xlsx openai

# Add your OpenAI API key to the code
# Edit lead-bot.js and replace 'YOUR_API_KEY'
```

## 🚀 Usage

### 1. Prepare your Excel file

Create `leads.xlsx` with these columns:
- NOMBRE (Name)
- EMPRESA (Company)
- PROBLEMA (Problem/Pain point)
- PRESUPUESTO (Budget)
- URGENCIA (Urgency)
- EMAIL

### 2. Run the bot
```bash
node lead-bot.js
```

### 3. Get results

The bot will create `leads-calificados.xlsx` with added columns:
- **SCORE:** Quality score (1-10)
- **RAZON:** Why this score
- **ACCION:** Recommended next step
- **PRIORIDAD:** Priority level

## 📊 Example Output
```
[1/5] Juan Pérez...
   Score: 9/10 | Priority: Alta

[2/5] María López...
   Score: 5/10 | Priority: Media

COMPLETED!
File created: leads-calificados.xlsx

=== SUMMARY ===
Total leads: 5
High Priority: 3
Medium Priority: 1
Low Priority: 1
Average Score: 7.4/10
```

## 💡 Use Cases

Perfect for:
- 🏢 **Sales teams** - Qualify inbound leads automatically
- 📱 **Marketing agencies** - Score ad campaign leads
- 🚀 **Startups** - Optimize founder time on best prospects
- 💼 **Consultants** - Prioritize client outreach
- 🎯 **Anyone with Excel lead lists**

## 💰 Pricing for Clients

This solution can be sold as:
- **One-time implementation:** $800-1,200
- **Monthly processing service:** $200-400/month
- **Custom integration:** $1,500-3,000

**Client ROI:** Pays for itself in first week of time savings.

## 🔒 Security Note

- API key stored locally (never committed)
- Data processed locally on your machine
- No data sent to third parties (except OpenAI API)
- Use environment variables for production

## 🎓 Learning Outcomes

This project demonstrates:
- API integration with AI services
- File processing (Excel read/write)
- Asynchronous JavaScript
- Prompt engineering for business use
- Practical automation that generates revenue

## 👤 About Me

**Luz** - Business Automation Specialist | AI Integration Developer

I build hybrid automation solutions combining no-code tools (Make, n8n, Zapier) with custom code when ROI justifies it.

**Specialties:**
- AI-powered workflow automation
- Lead qualification & CRM automation
- Business process optimization
- Web scraping & data processing

**Connect:**
- 💼 [Upwork Profile](https://www.upwork.com/freelancers/~01fc4564292723fd16)
- 🔗 [LinkedIn](https://www.linkedin.com/in/luz58zavala/)
- 🎥 [YouTube](https://www.youtube.com/@TrabajoDigitalconMaggie)

## 📄 License

MIT License - Free to use and modify

---

⭐ If you find this useful, give it a star! Questions? Open an issue or reach out directly.
