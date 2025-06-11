# Frontend Quote Generator

Welcome to the Frontend Quote Generator—a nimble, browser‑only tool that brings a fresh burst of inspiration whenever you need it. Instead of bundling quotes into the app itself, this project reaches out to a public quotes API, so you always get new, varied wisdom. Because the API requires an access key, you’ll plug in your own key so the app stays lightweight and under your control.

## Features

- **On‑Demand Quote Fetching**  
  Click the “New Quote” button and the app sends a request to your chosen quotes API. As soon as the response comes back, you see the quote text and author appear in a neatly styled card—no page reloads, no waiting around.

- **User‑Supplied API Key**  
  To keep this tool unopinionated and secure, you provide your own API key. That means you’re free to choose any quotes service you like (Quotable, They Said So, etc.), and there’s no hard‑coded credential buried in the code. If the key is missing or invalid, the app shows a clear error message so you know exactly what to fix.

- **Loading Indicator & Error Handling**  
  While the quote is in transit, a spinner or “Loading…” message keeps you informed. If something goes wrong—network hiccup, bad key, server error—the app gracefully displays an explanatory message rather than leaving you guessing.

- **Live Code Analysis**  
  Beyond inspiring you with quotations, this project can introspect its own text output. Paste or type any passage into the analysis box and instantly see:
  - **Character Count**: Total letters, spaces, punctuation—everything.
  - **Vowel Breakdown**: How many A’s, E’s, I’s, O’s, and U’s (both uppercase and lowercase).  
  This feature demonstrates simple string analysis in vanilla JavaScript, showing how easy it is to read values from inputs, loop through text, and update the DOM with results.

- **Clean, Responsive UI**  
  The interface adapts to desktop and mobile screens without any extra configuration. CSS Flexbox and media queries ensure the quote card and tools always look balanced, whether you’re on a laptop or phone.

- **Extensible, Vanilla‑JS Core**  
  No frameworks here—just plain HTML, CSS, and ES6+. Every piece of logic (API calls, key validation, loading states, text parsing) lives in a few small files, making it straightforward to read, fork, and extend.

---

Whether you want a daily dose of motivation or a live demo of JavaScript techniques, this Quote Generator has you covered. Simply supply your API key, hit “New Quote,” and let the words flow—then switch to the analysis view to see how your own text measures up. Enjoy exploring both inspirational philosophy and foundational front‑end code patterns!
