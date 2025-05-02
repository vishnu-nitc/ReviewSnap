📍 ReviewSnap – Smart Google Maps Review Summarizer
ReviewSnap helps you make faster decisions when you're searching for places—like restaurants or cafes—on Google Maps. Instead of reading hundreds of mixed reviews (positive, negative, or unrelated), ReviewSnap summarizes them using an LLM (Large Language Model) so you can quickly grasp what people are saying.

🚀 App Overview
When you're in an unfamiliar place, finding the best spot to eat can be overwhelming due to the sheer number of reviews. ReviewSnap solves this problem by summarizing all reviews into a single, easy-to-understand summary in real time.

📱 User Flow
Splash Screen
The app starts with a simple and elegant splash screen.

Search Page

After the splash screen, you land on the search page.

Type in the name of a place (e.g., "Café in Koramangala").

The search is powered by Google Maps API, giving you the same flexibility and accuracy as Google Maps itself.

Review Summary

Once you select a place, the app fetches all its reviews.

The reviews are processed using an LLM in real time.

You receive a concise summary of what people are saying.

Option to go back and search again.

📦 Phase 1 Features
🔍 Google Maps API-integrated search

⚡ Real-time LLM-based review summarization

🔄 Easy navigation between search and summary

⏭️ Phase 2 Roadmap
✅ Limit free usage to 5 summaries per user

👤 User authentication with Google/Facebook SSO

💬 Chat with Reviews
Ask questions like:

"Is the place good for vegetarians?"

"Any mentions of hygiene?"

💡 Custom Review Summary Model
Replace LLM with an in-house NLP model to reduce cost and latency.

📊 Advanced Review Analytics

Detect common topics (e.g., food quality, ambience, service)

Segment reviews by sentiment and theme

🛠️ Tech Stack (Planned)
Frontend: React Native / Flutter

Backend: Python (FastAPI / Flask), LLM APIs

Maps & Reviews: Google Maps Places API

LLM: OpenAI / Custom NLP Model (Phase 2)

🌐 Future Vision
A smart decision-making companion for local discovery. Whether you're a tourist or a local, get the gist of what the crowd is saying—instantly.
