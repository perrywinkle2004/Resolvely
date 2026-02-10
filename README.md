# AI Based Ticket Issue resolver
A full-stack web app

Core idea:
This app automatically reads support tickets (from Excel or database), analyzes the issue description, generates a suggested fix (simulated with AI), and records the results.

Requirements:
1. Allow users to upload a ticket CSV.
2. The app should show all uploaded tickets in a Analytics dashboard.
3. For each ticket, include a “Generate Fix” button.
4. When clicked, the backend should:
   - Simulate calling an AI model to produce 
1. Issue Summary
A short 1–2 line explanation of the problem in simple terms.
2. Likely Root Cause
Explain what is most likely causing this issue, based on the ticket’s description, module/component, and severity.
3. Recommended Fix (High-Level)
Step-by-step actions an engineer should take to resolve the issue.
Use plain English.
5. Store ticket results (status, logs, fix) in a simple SQLite or JSON database.
6. Have a page to view all resolved tickets.
7. Make the UI clean and minimal — like an internal IT dashboard.

Optional:
Add a “Knowledge Base” section that lists all previous tickets and their fixes, and lets the AI learn from them (even if simulated).

Use Python for backend, React for frontend.
Include nice UI cards, progress spinners, and a success/failure indicator after each fix is tested.

the output is suggested in normal english

Project Link
created using the Lovable app: https://resolvely.lovable.app/
