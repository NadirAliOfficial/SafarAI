# SafarAI

**Your Intelligent Travel Companion for Pakistan**

SafarAI is an AI-powered travel companion that turns a simple travel idea into a complete, safe, personalized, and budget-friendly journey plan — within seconds.

> "I have PKR 40,000. I'm traveling from Sukkur to Hunza with friends for five days."

Instead of juggling maps, booking sites, weather apps, and manual budget math, the traveler describes the trip in plain language and SafarAI returns a full plan: route, budget, hotels, packing list, and safety information — built around the realities of traveling in Pakistan.

📄 Full pitch deck: [`docs/SafarAI_Pitch.pdf`](docs/SafarAI_Pitch.pdf)

## The Problem

Planning a trip in Pakistan means juggling multiple disconnected apps and still ending up unprepared:

- Route info with no context on real road conditions or rest stops
- Hotel booking disconnected from the actual trip budget
- No single place for weather, packing guidance, or safety information
- Manual budget math for fuel, food, hotels, and emergency reserves
- Weak internet in northern areas, where most apps fail exactly when needed most
- No local context — prayer stops, halal food, family planning, nearest hospital

## Core Features

| Feature | What It Does |
|---|---|
| **Smart Itinerary** | Day-by-day plan with departure time, rest stops, food, hotels, and attractions |
| **Budget Calculator** | Auto-estimates fuel, bus tickets, hotels, meals, and emergency money |
| **Packing Assistant** | Generates a checklist based on destination, weather, duration, and activities |
| **Safety Mode** | Emergency contacts, live location sharing, nearby hospitals, police stations |
| **AI Travel Chat** | Ask questions like "Can I finish this trip in one day?" and get direct answers |
| **Offline Trip Card** | Saves itinerary, hotel details, and contacts locally for weak-signal areas |

## What Makes It Unique

Built for Pakistan-specific travel realities, not a generic map app:

| Local Challenge | How SafarAI Handles It |
|---|---|
| Uncertain road conditions | Route-aware planning with rest stops and buffer time |
| Limited internet in northern areas | Offline trip card with saved itinerary and contacts |
| Family-friendly travel | Trip style input — family, friends, or solo — shapes the plan |
| Local transport options | Plans realistically around car, bus, or mixed transport |
| Prayer stops & halal food | Built into the itinerary and recommendations by default |
| Emergency planning | Safety Mode with hospitals, police, and live location |
| Urdu and English users | Bilingual support from day one |

## Hackathon MVP

Screens for the demo build:

1. Login / Guest Mode
2. Trip Details Form
3. AI-Generated Itinerary
4. Budget Breakdown
5. Packing Checklist
6. Emergency Screen

## Demo Example

**Input:** Sukkur → Lahore · 4 people · 2 days · PKR 45,000 · by car

**Output:** recommended departure time, route and rest stops, fuel estimate, hotel suggestions, food budget, places to visit, packing list, and emergency contacts.

## Tech Stack

- **Frontend:** React / Next.js
- **Backend:** FastAPI
- **Database:** Supabase
- **AI:** Gemini API
- **Maps:** Google Maps API
- **Weather:** OpenWeather API

## Target Users

Solo travelers · Families · Backpackers · Students · Road trip enthusiasts · Tourists visiting Pakistan

## Vision

> "Plan a five-day family trip to Skardu under PKR 80,000."

Long-term, SafarAI acts as an AI travel agent that books accommodations, plans the route, estimates expenses, suggests attractions, creates a packing list, monitors weather, and adapts the plan in real time as conditions change.

## One-Line Pitch

SafarAI is an AI-powered travel companion that transforms a simple travel idea into a complete, safe, personalized, and budget-friendly journey within seconds.
