# Jarurat Care Foundation

A complete, beautiful, production-ready single-page web app for Jarurat Care Foundation — an Indian NGO that supports cancer patients (specifically Gallbladder, Cholangiocarcinoma, and Liver Cancer).

## Tech Stack
- HTML, CSS, JavaScript (no framework)
- Tailwind CSS (CDN)
- Google Gemini API (`gemini-2.0-flash`)

## AI Feature
**"Hope Assistant"** — an AI-powered chatbot built on Gemini that provides:
- 24/7 answers to patient and caregiver FAQs
- Compassionate guidance to relevant support services
- Emotional support and encouragement
- Information about cancer types in simple language

## NGO Use Case
Jarurat Care supports cancer patients in India who are often overwhelmed and confused. Hope Assistant reduces the burden on the support team by instantly answering common questions, guiding patients to the right form, and providing emotional comfort — especially during late hours when human support isn't available.

## How to Run
1. Open `index.html` in any modern browser.
2. To enable the chatbot, replace `REPLACE_WITH_API_KEY` with a valid Gemini API key at the top of the script section in `index.html`.
3. Forms work perfectly without an API key (using LocalStorage for demonstration purposes).

## How to Deploy
- **Netlify**: Drag and drop the folder containing `index.html` to Netlify Drop (https://app.netlify.com/drop).
- **Vercel / GitHub**: Push the repository to GitHub and connect it to Vercel or Netlify for automatic deployments. The site requires no build steps.
