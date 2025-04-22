# 📈 Alltech MCP (Model Context Protocol)

Originally, this project started as a standalone MCP (Model context protocol) server + client setup.  
After some challenges integrating with the OpenAI SDK — and with OpenAI now allowing **direct tool integrations** —  
the system was restructured and simplified.

Instead of a full custom server and client, the MCP logic is now built **directly into the  openai sdk**.  
This keeps it lightweight, faster to deploy, and easier to extend.

---

## 🚀 What This Does

- Connects **GPT-4.1 Mini** directly to the business transactions database
- Allows GPT to **query**, **analyze**, and **generate insights** based on real data
- Provides admins with automatic **business health reports** without manual work

---

## ⚡ Current Features

- Fetch daily and weekly transaction summaries
- Analyze stock and sales patterns
- Identify products that are low on stock after recent sales
- Built to be lightweight with minimal server load

---

## 🔥 Why This Is Cool

- Get **AI-powered** insights without expensive dashboards
- No complicated setup or external analytics platforms needed
- Real-time analysis of business performance
- Set up for future automation (like daily WhatsApp reports)

---

## 📚 Quick Example Usage

> Example prompts that GPT can now handle using live business data:

```python
Q: "What were the top-selling products this week?"
Q: "Which products need restocking based on recent sales?"
Q: "Summarize today's revenue and number of transactions."
