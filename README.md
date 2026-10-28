# Soumya Singh Bais — Portfolio

A responsive portfolio built around a “build / learn / repeat” concept. It presents five public projects, a skills toolkit, combined project search and filters, light/dark mode, and a portfolio Q&A assistant.

## Run the page

Open `index.html` in a browser for the portfolio layout, navigation, theme switch, and project filtering. Styling and browser interactions are embedded in the HTML, so they do not depend on a separate CSS or JavaScript file.

The chatbot needs the serverless function in `api/chat.js` and a Gemini API key. To run it locally:

1. Create an API key in [Google AI Studio](https://aistudio.google.com/apikey).
2. Install the Vercel CLI.
3. Create a local `.env.local` containing:
   ```text
   GEMINI_API_KEY=your_api_key_here
   ```
4. Run `vercel dev` from the project directory.

Keep the key out of client-side code and GitHub.

## Deploy

Import the project folder into Vercel, set `GEMINI_API_KEY` under Project Settings → Environment Variables, then deploy. The default model is `gemini-3-flash-preview`; set `GEMINI_MODEL` to override it. Redeploy after changing environment variables.

## Project links

- [Python Basics: Small Programs](https://github.com/soumya2007-29/Python_Basics_2112)
- [Student Marks Report](https://github.com/soumya2007-29/Messy-code-project)
- [Student Utils: Bug Fixes](https://github.com/soumya2007-29/Buggy-Code-Project)
- [Code With AI Quiz](https://github.com/soumya2007-29/Quiz_Project) · [Live demo](https://quizproject4.vercel.app/)
- [Reading List App](https://github.com/soumya2007-29/Reading-list-app) · [Live demo](https://readinglistapp-gamma.vercel.app/)

## Privacy

When visitors send a question, the server sends it and the portfolio facts to Google Gemini to create an answer. The provider’s free tier may use submitted data to improve Google products. Visitors should avoid entering sensitive information.

"# Portfolio" 
