# GigShield AI 🚀

## Inspiration
India’s gig workers lose income due to external disruptions like rain, pollution, and curfews. They have no financial safety net. Our solution provides AI-powered income protection.

## What it does
GigShield AI is a parametric insurance platform that:
- Detects disruptions (weather, pollution, strikes)
- Automatically triggers claims
- Provides instant payout
- Uses weekly subscription model

## How we built it
- Frontend: HTML, CSS
- Backend: Python (Flask)
- AI Model: Risk prediction based on weather + location
- APIs: Weather API (mock)
- Payment: Razorpay (mock)

## Workflow
1. User registers
2. AI calculates risk score
3. Weekly premium generated
4. System monitors triggers
5. Auto claim + payout

## AI Implementation
- Risk Prediction Model
- Fraud Detection:
  - GPS validation
  - Duplicate claim detection

## Weekly Pricing Model
Premium = Base Price + Risk Factor

Example:
Base = ₹50/week  
High risk = +₹20  
Final = ₹70/week  

## Parametric Trigger
- Rain > threshold → claim triggered
- Pollution > level → payout triggered

## Challenges we ran into
- Data availability
- Fraud detection logic
- Pricing fairness

## Accomplishments that we're proud of
- Full workflow design
- AI + automation integration
- Zero-touch claim system

## What we learned
- Insurance basics
- AI in real-world systems
- Backend integration

## What's next
- Real API integration
- Mobile app
- Advanced ML model

## Market Crash Readiness
Our system is designed to handle sudden regulatory changes:
- Modular architecture
- Easy rule updates
- Quick deployment within 24 hours

## Tech Stack
HTML, CSS, JavaScript, Python, Flask, Machine Learning

## Demo
Coming Soon
