# ARCHIV-COSTSheetCalculator
📁 ARCHIV-COST // Professional Cost Accounting Ledger & LLM Notebook

🏛️ Project Overview

ARCHIV-COST is a specialized, client-side web application designed to bridge the gap between classical management accounting and modern AI-driven intelligence. Built for professional accountants and forensic auditors, this tool provides a secure, locally-rendered environment to upload ledger data, perform complex variance analysis, and generate structured cost reports using Google Gemini 2.5.

Install Coding Agent Plugin
Turn your coding agent into a Vercel expert. Simply copy and run this in your terminal to install the plugin. Available for Claude, Cursor and Codex.
npx plugins add vercel/vercel-plugin

Forget tedious manual calculations—leverage an AI agent tailored to understand Prime Costs, Activity-Based Costing (ABC), and Overhead Disposition at a granular level.

✨ Unique Features

🎙️ Expert Cost Intelligence: The internal Gemini agent is primed with a senior management accountant’s knowledge base. It handles Variance Auditing, Cost Allocation (ABC), and CVP Analysis with mathematical precision.

📜 Archival Ledger Aesthetics: A carefully curated interface that feels like a digital ledger book, reducing digital fatigue during long audit sessions.

🔒 Secure Client-Side Execution: Your data stays in your browser memory, and your API key is stored locally in your session. All AI communication is sent directly to Google Cloud—no middleman, no cloud database.

📊 Dynamic Cost Sheet Rendering: Automatically converts raw CSV/JSON data into professional, vertically-aligned, double-underlined financial statements.

📄 Seamless Multi-Format Support: Drag-and-drop support for PDFs (OCR-lite extraction), CSV, JSON, TXT, and Markdown files.

🛠️ Built With

Frontend: Tailwind CSS for a refined, responsive layout.

AI Engine: Google Gemini 2.5 Flash API (Direct integration).

Parsing: pdf.js for robust document extraction.

Icons: Lucide Icons.

🚀 Getting Started

Clone the Repository:

git clone https://github.com/your-username/archiv-cost.git


Open in Browser: Simply open index.html in your favorite web browser. No compilation or backend server setup is required.

Configure API:

Navigate to the "GEMINI API KEY" input in the top header.

Enter your key and click CONNECT.

Note: Your key is stored in sessionStorage and cleared when the browser is closed.

⚙️ Accounting Operations Supported

Variance Auditing: Price, Usage, Rate, and Efficiency variance calculations with automated "Favorable/Unfavorable" tagging.

Overhead Disposition: Logic for applying over/under-applied overhead to COGS, WIP, and Inventory.

Margin Optimization: Actionable insights based on volume-profit data and contribution margins.

Built for the modern Accountant who appreciates the elegance of the archive.
