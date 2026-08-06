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

## Baseline (handled, not the pitch)

Smart Itinerary · Budget Calculator · Packing Checklist · Offline Access — every travel app has these. SafarAI has them too, but they're not what wins the room.

## What No Other Travel App Has

The features that make this pitch memorable:

| Feature | What It Does |
|---|---|
| **Live Hazard Map & Risk Score** | Crowdsourced alerts for landslides, flooding, potholes, and checkpoints, condensed into a live Trip Risk Score with a smarter departure time |
| **Group Expense Split** | Automatically splits fuel, hotel, and food costs across the group and settles who owes who — no manual tracking after the trip |
| **Family Safety Circle** | Automatic check-in messages to family at each rest stop, sent by SMS so it still works where mobile data doesn't |
| **Urdu Voice Mode** | Plan and query trips by speaking in Urdu — built for hands-free driving and users not comfortable typing in English |
| **Fuel & Cash Finder** | Maps CNG/petrol stations and ATMs along remote routes — critical where fuel is sparse and cards aren't accepted |
| **Prayer-Aware Routing** | Auto-adjusts departure and rest timing around the five daily prayers for that day and location |

## Localization Layer

Beyond the headline features, every screen assumes local context by default:

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
4. Budget Breakdown & Group Split
5. Packing Checklist
6. Hazard Map & Emergency Screen

## Demo Example

**Input:** Sukkur → Lahore · 4 people · 2 days · PKR 45,000 · by car

**Output:** recommended departure time, route and rest stops, live Trip Risk Score, fuel estimate, group cost split, hotel suggestions, food budget, places to visit, packing list, and emergency contacts with an SMS check-in to family.

## Tech Stack

- **Frontend:** React / Next.js
- **Backend:** FastAPI
- **Database:** Supabase
- **AI:** Gemini API
- **Maps:** Google Maps API
- **Weather:** OpenWeather API

## Target Users

Solo travelers · Families · Backpackers · Students · Road trip enthusiasts · Tourists visiting Pakistan

## Vision — Beyond the Hackathon

Hazard alerts and the Trip Risk Score already make SafarAI proactive. The next step is a fully autonomous AI travel agent:

> "Plan a five-day family trip to Skardu under PKR 80,000."

Long-term, SafarAI books accommodations, plans the route, estimates expenses, suggests attractions, creates a packing list, monitors weather, and adapts the plan in real time as conditions change — negotiating and booking on the traveler's behalf.

## One-Line Pitch

SafarAI is an AI-powered travel companion that transforms a simple travel idea into a complete, safe, personalized, and budget-friendly journey within seconds.
