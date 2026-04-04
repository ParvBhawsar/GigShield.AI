<div align="center">

# GigShield.AI
### AI-Powered Parametric Income Protection For India’s Gig Economy

**Team Payload**

Protecting Delivery Partners From Income Loss Using Weekly Pricing, AI-Based Risk Assessment, And Automated Parametric Payouts.

![Built for](https://img.shields.io/badge/Built%20for-Gig%20Economy-blue)
![Model](https://img.shields.io/badge/Pricing-Weekly-success)
![Platform](https://img.shields.io/badge/Platform-Mobile--First-orange)
![AI](https://img.shields.io/badge/AI-Risk%20%26%20Fraud%20Detection-purple)

</div>

---

## 🎥 Demo Video

**https://drive.google.com/file/d/1XfjCdgx6HEARWX_bNppjS4NYW2GiQC9Z/view**

---

## Overview

GigShield.AI is an AI-enabled parametric insurance platform designed to protect India’s delivery workforce from income loss caused by external disruptions such as rainfall, extreme heat, pollution, and zone restrictions.

Unlike traditional insurance, it focuses strictly on **income protection** and operates on a **weekly subscription model aligned with gig earnings cycles**.

---

## Vision

To build a system where gig workers are financially protected against uncontrollable disruptions and can earn with stability and confidence.

---

## The Problem

Gig workers across platforms like Zomato, Swiggy, Blinkit, and Amazon face **20–30% income volatility weekly** due to:

- Weather disruptions  
- Pollution spikes  
- Local restrictions / zone shutdowns  

There is **no real-time, short-term financial safety net**.

---

## Our Solution

GigShield.AI provides **weekly parametric micro-insurance**, where payouts are:

- Automatically triggered  
- Based on real-world measurable events  
- No manual claim process required  

---

## Parametric Trigger System (Now With Defined Thresholds)

We define **clear, measurable triggers** for payouts:

| Condition | Threshold | Impact |
|----------|----------|--------|
| Heavy Rain | > 50 mm/day | Reduced delivery hours |
| Extreme Heat | > 40°C | Worker fatigue, reduced shifts |
| AQI Spike | AQI > 300 | Health risk, reduced mobility |
| Flood Alert | Govt-issued warning | Work disruption |
| Zone Closure | Platform/API signal | No delivery access |

📌 If threshold is crossed for **≥ 4 hours in a working window**, payout is triggered.

---

## How It Works

1. Worker onboarding (location, platform, working hours)
2. AI-based risk profiling
3. Weekly premium generation
4. Continuous monitoring (weather + platform signals)
5. Automatic payout trigger
6. Instant payout to wallet/bank

---

## AI & ML System (Detailed)

### 1. Risk Scoring Model
- Inputs: location, past earnings, weather history, shift patterns  
- Model: Gradient Boosting / Regression-based scoring  
- Output: Weekly risk score → premium pricing  

### 2. Disruption Prediction
- Time-series forecasting (ARIMA / LSTM-lite)
- Predict probability of disruption in upcoming week  

### 3. Fraud Detection
- Location spoof detection  
- Behavioral anomaly detection  
- Duplicate claim filtering  
- Device fingerprinting  

---

## Financial Model (Added Depth)

### Premium Calculation

Example:
- Weekly Income: ₹4000  
- Risk Probability: 0.25  
- Coverage: 30%  

→ Premium ≈ ₹120–₹200/week  

### Payout Logic

→ ₹1200 payout for disruption  

### Sustainability

- High volume, low premium model  
- Risk pooled across city clusters  
- AI reduces loss ratio via pricing accuracy  

---

## Platform Architecture (Development Artifact Added)

### System Components

- Mobile App (React Native / Flutter)
- Backend API (FastAPI / Node.js)
- Database (PostgreSQL / Supabase)
- AI Engine (Python microservice)
- External APIs:
  - Weather API
  - AQI API
  - Platform signals (mock / real)

### Pipeline

User → API → Risk Engine → Monitoring Engine → Trigger Engine → Payment Service

---

## Adversarial & Fraud Defense

To prevent misuse:

- GPS consistency checks  
- Time-window validation  
- Multi-signal verification (weather + activity)  
- Claim frequency caps  
- ML-based anomaly detection  

---

## Regulatory Considerations

- Aligns with **IRDAI sandbox model for parametric insurance**  
- Can operate via:
  - Insurer partnership (B2B2C)
  - Embedded insurance model  
- Compliance areas:
  - KYC onboarding  
  - Data privacy (DPDP Act)  
  - Transparent payout logic  

---

## Key Features

- AI-based risk pricing  
- Weekly flexible subscription  
- Real-time disruption monitoring  
- Automated payouts  
- Fraud-resistant system  
- Analytics dashboard  

---

## Scope Clarification

GigShield.AI focuses **only on income loss** due to external disruptions.

Not covered:
- Health insurance  
- Accidents  
- Vehicle damage  

---

## Roadmap (Improved)

**Phase 1: Foundation & Design**  
- Problem validation and research  
- System architecture design  
- Parametric trigger definition  
- Initial financial model  

**Phase 2: Development & Intelligence**  
- Backend + API development  
- Parametric trigger engine implementation  
- AI-based risk scoring and pricing  
- Fraud detection module  

**Phase 3: Deployment & Scaling**  
- Mobile app + dashboard  
- Real-time monitoring integration (weather, AQI, etc.)  
- Pilot testing with users  
- Partnerships with insurers / platforms  

---

## Team Payload

Parv Bhawsar  
Nupur Goswami  
Shashwat Singh  
Bhoomi Thakur  
Kanishk Sinha
