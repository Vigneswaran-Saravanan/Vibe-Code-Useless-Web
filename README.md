# DumbGenius AI

DumbGenius AI is a fun, frontend-only AI web app that generates humorous, sarcastic, and intentionally “bad but funny” life advice using the Hugging Face Inference API.

It is built for entertainment and showcases how AI can be used creatively for comedy-based interactions.

---

## Features

-  AI-generated humorous and chaotic advice
-  Two response modes:
  - **DumbGenius Mode** → Funny, light, absurd advice
  - **Worse Advice Mode** → More chaotic and overconfident responses
-  Typewriter animation for AI output
-  Copy AI response to clipboard
-  Export question & answer as printable PDF page
-  Modern dark UI with glassmorphism design
-  Fully frontend-based (no backend required)

---

##  How It Works

1. User enters a question in the input box
2. The question is sent to the Hugging Face API
3. AI model generates a humorous response using a custom prompt
4. Response is displayed with a smooth typewriter animation
5. User can:
   - Copy the response
   - Save it as a PDF (print page)

---

## Tech Stack

- HTML5
- CSS3 (modern dark UI, glassmorphism)
- Vanilla JavaScript (no frameworks)
- Hugging Face Inference API

---

## API Setup

This project uses the **Hugging Face Inference API**.

### Step 1: Get API Token
Create an account and generate a token:

https://huggingface.co/settings/tokens

---

### Step 2: Add Token in Code

Inside your JavaScript:

```js
const HF_TOKEN = "YOUR_HUGGING_FACE_TOKEN";
