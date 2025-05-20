📨 GitHub Issues Digest via Email (n8n Workflow)

This workflow checks a GitHub repository for new issues and sends an email summary to your inbox at scheduled intervals.

📌 Features
- Automatically fetches issues from a GitHub repo using its API.
- Filters for new issues.
- Formats a summary email.
- Sends an update to your email via Gmail or SMTP.

🔧 Workflow Structure
1. Cron Node – Triggers the flow every X hours/days.
2. HTTP Request Nod – Calls GitHub’s API endpoint for issues.
   Example:  
   `https://api.github.com/repos/AshleyMathias/n8n-automation/issues`
3. IF Node – Checks if there are new issues (length > 0).
4. **Function Node (optional) – Formats the issues into a readable message.
5. Email Node (SMTP/Gmail) – Sends the formatted issue list to your email.

🌐 Tools & Services Used
- [n8n](https://n8n.io)
- GitHub REST API (no auth for public repos)
- Gmail / SMTP

📲 Connect with Me
- 💼 [LinkedIn: ashleymathia10](https://linkedin.com/in/ashleymathia10)
- 💻 [GitHub: AshleyMathias](https://github.com/AshleyMathias)

