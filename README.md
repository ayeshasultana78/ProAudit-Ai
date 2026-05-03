🛡️ Pro-Audit AI
An intelligent web diagnostic and optimization platform that crawls websites to identify technical errors and provides AI-driven solutions for real-time correction.

🌐 Live Demo
https://pro-audit-ai.vercel.app/

🛠️ Tech Stack

Analysis Engine: Powered by Google AI Studio (Gemini) to interpret complex web errors and suggest code fixes.

Web Crawler: Built with Python to scan DOM structures and identify broken links, missing metadata, and performance bottlenecks.

Frontend & Hosting: Deployed on Vercel for a high-speed, interactive diagnostic dashboard.

Data Handling: Uses Pandas for structured error reporting and auditing logs.

✨ Key Features

Full-Site Scanning: Deep crawls websites to detect 404 errors, slow-loading assets, and SEO inconsistencies.

Intelligent Error Diagnosis: Leverages AI to explain why an error occurred rather than just reporting it.

Automated Correction Guide: Provides specific code snippets (HTML/CSS/JS) to fix identified issues instantly.

Performance Auditing: Evaluates core web vitals and suggests optimizations for better search engine rankings.




<div align="center">
<img width="1200" height="475" alt="GHBanner" src="https://github.com/user-attachments/assets/0aa67016-6eaf-458a-adb2-6e31a0763ed6" />
</div>

# Run and deploy your AI Studio app

This contains everything you need to run your app locally.

View your app in AI Studio: https://ai.studio/apps/drive/1uho_AbMbcbpv1n0zyG2mLqZsNn2Y880f

## Run Locally

**Prerequisites:**  Node.js


1. Install dependencies:
   `npm install`
2. Set the `GEMINI_API_KEY` in [.env.local](.env.local) to your Gemini API key
3. Run the app:
   `npm run dev`
