# WorkSmart AI — Workplace Productivity Assistant

A beginner-friendly, responsive web prototype demonstrating five workplace productivity tools:
1. Smart Email Generator
2. Meeting Notes Summarizer
3. AI Task Planner
4. Research Assistant
5. AI Chat Assistant

## Important implementation note
This is a **front-end demo prototype**. It uses local JavaScript templates and text-processing heuristics to demonstrate the workflow. It does **not** call a live AI model. The UI labels this clearly. For production/live AI responses, connect an approved AI provider through a secure server-side backend. Never put a private API key in `index.html`.

## Run locally
1. Download and unzip `worksmart-ai.zip`.
2. Open the `worksmart-ai` folder.
3. Double-click `index.html` to open it in a modern browser.
4. Choose a tool from the left navigation and select **Try example** or enter your own text.
5. Use Copy or Download to export generated drafts.

No installation, build tools, or account is required for the local demo.

## Deploy using GitHub Pages
1. Sign in to GitHub and create a new repository, for example `worksmart-ai`.
2. Upload `index.html` and `README.md` to the repository root.
3. Open **Settings → Pages**.
4. Under Build and deployment, choose **Deploy from a branch**.
5. Select branch `main` and folder `/ (root)`, then Save.
6. Wait for GitHub Pages to publish the site. The URL will be shown in Settings → Pages.

## Alternative: Netlify
1. Sign in to Netlify.
2. Choose **Add new site / Deploy manually**.
3. Drag the project folder (containing `index.html`) into the deploy area.
4. Netlify will provide a public URL.

## Project structure
- `index.html` — complete responsive interface, styles, and demo logic
- `README.md` — setup and deployment instructions

## Responsible AI
- Review generated drafts and summaries before using them.
- Do not enter confidential or sensitive information.
- Verify facts, deadlines, names, and recommendations.
- Treat topic outlines as starting points, not verified research.
- For live AI integration, keep API keys on the server and use an approved provider.

## Suggested demonstration
1. Generate a client follow-up email.
2. Paste meeting notes and show extracted decisions and actions.
3. Create a daily plan from a list of tasks.
4. Summarize a short text or create a research outline.
5. Ask the chatbot a workplace question.
6. Explain the prototype's current limitations and how secure AI API integration could extend it.
