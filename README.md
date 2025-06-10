🧑‍🍳 Chef Claude
Chef Claude is an AI-powered recipe generator that helps you cook something delicious using ingredients you already have at home. Just type in a few ingredients, and Claude (Anthropic AI) will suggest a recipe, formatted in Markdown for easy reading and sharing.

Live demo: https://chefcluade.netlify.app

📌 Features
Add your ingredients manually

Get an AI-generated recipe based on what you have

Optional: choose servings, cuisine, or add extra instructions

Clean, responsive UI with nicely formatted Markdown output

🛠 Tech Stack
React + Vite — for a fast, modern frontend

Anthropic Claude API — natural language generation

Markdown rendering — clean and readable recipe output

⚙️ Usage
Enter at least 4 ingredients in the input field.

Click the “Get a recipe” button.

Wait a few seconds for Claude to generate a recipe.

The recipe will appear, fully formatted in Markdown.

📄 License
MIT License. See LICENSE for details.

🔐 Notes on API Keys
This project uses the Anthropic Claude API.
For security reasons, your API key should never be exposed in the frontend.
Use a backend (like Express.js or a serverless function on Netlify) to securely proxy API requests and keep your ANTHROPIC_API_KEY hidden.










