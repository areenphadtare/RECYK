# ♻️ Kabadiwala Connect

### **Bridging Informal E-Waste Collectors with the Formal Recycling Ecosystem**

> **SIH 2026 | Problem ID: SIH26229 | Clean & Green Technology**

<p align="center">
  <img src="https://img.shields.io/badge/SIH-2026-blue?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Problem-SIH26229-green?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Category-Software-orange?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Theme-Clean%20%26%20Green-success?style=for-the-badge" />
</p>

<p align="center">
  <b>Making formal e-waste recycling more profitable, accessible, safe, and transparent for informal collectors.</b>
</p>

---

## 🌍 About the Project

India's informal scrap collectors and waste-pickers play a critical role in collecting end-of-life electronics. However, many remain disconnected from the formal recycling ecosystem.

This creates several challenges:

* ❌ Lack of transparent and fair pricing
* ❌ Difficulty finding authorized recyclers
* ❌ Unsafe e-waste handling practices
* ❌ No reliable transaction records
* ❌ Limited traceability of collected materials
* ❌ Dependence on intermediaries
* ❌ Poor access to digital services
* ❌ Low connectivity in operational areas

### 💡 Our Solution

**Kabadiwala Connect** is a **vernacular, low-literacy, offline-first mobile platform** that connects informal e-waste collectors directly with authorized recyclers.

The platform helps collectors:

> **Identify → Value → Compare → Sell → Track → Earn**

---

# 🎯 Problem Statement

### **SIH26229 — Kabadiwala Connect**

**Organisation:** Ministry of Defence (MoD)
**Department:** Indian Army (DGIS)
**Theme:** Clean & Green Technology
**Category:** Software

The platform aims to create a digital bridge between informal collectors and the formal recycling chain by providing:

* Fair price discovery
* Material classification
* Recycler matching
* Digital lot creation
* Traceable handovers
* Earnings tracking
* Safety guidance
* Offline-first functionality
* Marathi and Hindi support

---

# 🚀 Our Vision

> ### **"Turn every scrap collection into a traceable, fairly valued, and safely recycled resource."**

Kabadiwala Connect is not just a scrap marketplace.

It is a **decision-support and traceability platform** designed around the actual needs of informal collectors.

---

# ⭐ Key Features

## 1. 📸 AI E-Waste Scanner

Collectors can photograph collected e-waste.

The system assists in identifying:

* PCB
* Cables
* Batteries
* CRT/LCD panels
* Motors
* Magnet-bearing assemblies
* Mixed plastics
* Other electronic materials

```text
Camera
   ↓
AI Classification
   ↓
Material Category
   ↓
Confidence Score
```

---

## 2. 💰 Fair Price Calculator

Collectors can check the current market range before selling.

### Example

```text
Material: PCB
Weight: 12 kg

Current Local Price:
₹150 – ₹175 / kg

Estimated Value:
₹1,800 – ₹2,100
```

This improves price transparency and reduces information asymmetry.

---

# 🏆 3. Fair Deal Score

### **"Am I getting a fair price?"**

The platform compares the offered price against:

* Current local market range
* Historical prices
* Recycler offers
* Material category
* Location

Example:

```text
Offered Price: ₹110/kg

Typical Range:
₹150 – ₹175/kg

⚠️ POSSIBLY LOW OFFER

Nearby Authorized Recycler:
₹165/kg
```

---

# ♻️ 4. Smart Recycler Matching

Instead of simply finding the nearest recycler, the platform calculates the **best overall option**.

### Matching factors

```text
Price
+
Distance
+
Pickup Availability
+
Authorization
+
Service Area
+
Reliability
```

### Example

```text
Recycler A
₹170/kg
8 km
Pickup ✓
Authorized ✓

Recycler B
₹180/kg
35 km
Pickup ✗
Authorized ✓
```

The system can recommend the option with the best **overall economic value** rather than simply the highest quoted price.

---

# 🪪 5. Digital E-Waste Passport

Every collected lot receives a unique identifier.

```text
LOT-MH-2026-00125
```

The digital record can contain:

* Material
* Photograph
* Approximate weight
* Collection location
* Timestamp
* Collector ID
* Recycler ID
* Quoted price
* Final sale value
* Handover status
* Payment status

### QR-Based Verification

```text
QR Code
   ↓
Scan
   ↓
Lot Information
   ↓
Handover Verification
```

---

# 📋 6. Digital Handover Record

When material reaches the recycler:

```text
✓ Weight Confirmed
✓ Photograph Captured
✓ GPS Recorded
✓ Timestamp Recorded
✓ Recycler Confirmation
✓ Payment Status
```

A digital handover reference is generated for traceability.

---

# 💵 7. Earnings Ledger

Collectors receive a simple financial history.

```text
TOTAL EARNINGS

₹18,450

Completed:
₹17,250

Pending:
₹1,200
```

The ledger records:

* Transactions
* Payments
* Pending dues
* Historical earnings
* Sale values

---

# 🗣️ 8. Voice-First Interface

Designed for users with limited literacy.

Collectors can interact using voice.

### Example

**Marathi:**

> "Mala PCB cha aajcha bhav sang."

The system responds with the current available price information.

### Supported Languages

* 🇮🇳 Marathi
* 🇮🇳 Hindi
* 🇬🇧 English

The interface prioritizes:

**Icons + Voice + Minimal Text**

---

# 📶 9. Offline-First Architecture

The application is designed to remain usable even with poor connectivity.

### Offline activities

* Create lots
* Capture photographs
* Enter weight
* Save collector information
* View cached price data
* View saved recyclers
* Record transactions

When connectivity returns:

```text
Offline Data
     ↓
Internet Available
     ↓
Automatic Synchronization
     ↓
Cloud Backend
```

---

# 🛡️ 10. Safety Assistant

The application provides pictorial and audio safety guidance.

### Example

If a battery is identified:

```text
⚠️ HAZARDOUS MATERIAL

❌ Do not burn
❌ Do not puncture
❌ Do not open

✓ Keep safely separated
✓ Contact an authorized recycler
```

Safety guidance focuses on hazardous materials such as:

* Batteries
* CRTs
* PCBs
* Other potentially hazardous e-waste

---

# 📈 11. Price Trends

Collectors can view historical price movements.

```text
PCB PRICE

₹140 ── ₹150 ── ₹160 ── ₹170
                         ↑
                       Today
```

The platform can identify basic trends such as:

* Increasing
* Decreasing
* Stable

---

# 🚨 12. Abnormal Transaction Detection

The platform can flag unusual transaction values.

Example:

```text
Typical PCB Range:
₹150 – ₹180/kg

Recorded Transaction:
₹65/kg

⚠️ ABNORMAL VALUE DETECTED
```

This can help identify:

* Data-entry mistakes
* Unusual pricing
* Potentially unfair transactions

---

# 🚛 13. Smart Pickup Routing

The recycler can combine nearby pickup requests.

```text
Collector A ─┐
Collector B ─┼──→ Optimized Pickup Route
Collector C ─┘
```

### Benefits

* Reduced travel
* Lower transportation costs
* Better recycler efficiency
* Reduced emissions

---

# 📦 14. Lot Aggregation

Small collections can be grouped.

```text
Collector A → 5 kg PCB
Collector B → 7 kg PCB
Collector C → 8 kg PCB
                 ↓
             20 kg PCB
                 ↓
          Recycler Pickup
```

This helps make smaller collections more economically viable.

---

# 🌱 15. Environmental Impact Dashboard

Track the environmental impact generated through formal recycling.

Example:

```text
♻️ E-Waste Collected
245 kg

🔄 Formal Transactions
38

🚛 Optimized Pickups
21

🌱 Estimated Impact
Dashboard Metrics
```

The dashboard provides an easy way to communicate project impact during demonstrations.

---

# 🧠 AI/ML Layer

AI is used only where it adds genuine value.

```text
                    AI ENGINE
                       │
          ┌────────────┼────────────┐
          ↓            ↓            ↓
   Classification   Valuation    Anomaly
          │            │            │
          └────────────┼────────────┘
                       ↓
               Decision Support
```

### Potential AI Components

| Component               | Technology                      |
| ----------------------- | ------------------------------- |
| Material Classification | Computer Vision                 |
| Approximate Valuation   | ML Regression                   |
| Price Trend Analysis    | Time-Series / ML                |
| Transaction Anomaly     | Anomaly Detection               |
| Recycler Recommendation | Ranking / Optimization          |
| Voice Interaction       | Speech-to-Text / Text-to-Speech |

---

# 🏗️ System Architecture

```text
                    ┌──────────────────────┐
                    │   COLLECTOR MOBILE   │
                    │         APP         │
                    └──────────┬───────────┘
                               │
                  ┌────────────┼────────────┐
                  ↓            ↓            ↓
               Camera        Voice       Offline DB
                  │            │            │
                  └────────────┼────────────┘
                               ↓
                       ┌──────────────┐
                       │   FastAPI    │
                       │   Backend    │
                       └──────┬───────┘
                              │
             ┌────────────────┼────────────────┐
             ↓                ↓                ↓
       Material Service  Price Service   Recycler Service
             │                │                │
             └────────────────┼────────────────┘
                              ↓
                       ┌──────────────┐
                       │  AI / ML     │
                       │    Layer     │
                       └──────┬───────┘
                              │
          ┌───────────────────┼───────────────────┐
          ↓                   ↓                   ↓
   Classification       Valuation           Matching
          │                   │                   │
          └───────────────────┼───────────────────┘
                              ↓
                   ┌──────────────────┐
                   │  Traceability    │
                   │     Engine       │
                   └────────┬─────────┘
                            ↓
                    ┌───────────────┐
                    │ PostgreSQL DB │
                    └───────┬───────┘
                            │
                 ┌──────────┴──────────┐
                 ↓                     ↓
         Recycler Dashboard      Admin Dashboard
```

---

# 🛠️ Technology Stack

## Mobile Application

* Flutter
* SQLite / local storage
* Camera API
* GPS
* Voice APIs
* Offline synchronization

## Backend

* Python
* FastAPI
* REST APIs
* JWT Authentication

## Database

* PostgreSQL
* PostGIS
* Redis *(optional)*

## AI/ML

* Python
* PyTorch / TensorFlow
* OpenCV
* Scikit-learn
* XGBoost

## Frontend Dashboard

* React
* Tailwind CSS
* JavaScript / TypeScript

## Storage

* Object Storage for images
* PostgreSQL for structured records

## Deployment

* Docker
* Cloud infrastructure
* CI/CD

---

# 📊 Data Architecture

The system continuously generates structured datasets.

### Material Dataset

```text
Material ID
Category
Sub-category
Description
Image
Weight
Condition
Source
Estimated Value
```

### Price Dataset

```text
Material
Location
Date
Buying Price
Quoted Price
Unit
Recycler
Historical Price
```

### Recycler Dataset

```text
Recycler ID
Name
Location
Accepted Materials
Authorization
Contact
Offered Rate
Pickup Availability
Service Area
```

### Transaction Dataset

```text
Lot ID
Collector ID
Recycler ID
Material
Weight
Quoted Price
Final Price
Location
Date
Payment Status
Transaction Status
```

### Traceability Dataset

```text
Lot ID
Photographs
Weight
GPS
Timestamp
Handover Reference
Recycler Confirmation
Transaction Status
```

---

# 🔄 End-to-End Workflow

```text
        COLLECT E-WASTE
               ↓
          TAKE PHOTO
               ↓
       AI CLASSIFICATION
               ↓
        ENTER WEIGHT
               ↓
       FAIR VALUE ESTIMATE
               ↓
        FIND RECYCLERS
               ↓
       SMART MATCHING
               ↓
        ACCEPT OFFER
               ↓
        DIGITAL LOT ID
               ↓
        MATERIAL HANDOVER
               ↓
        RECYCLER CONFIRMS
               ↓
            PAYMENT
               ↓
        DIGITAL RECEIPT
               ↓
         TRACEABILITY
```

---

# 👥 User Roles

## 👷 Collector

* Register/Login
* Create material lots
* Scan e-waste
* Check prices
* Find recyclers
* Accept offers
* Track handovers
* View earnings
* Receive safety guidance

## ♻️ Recycler

* Register facility
* Manage authorization information
* Define accepted materials
* Publish rates
* Manage pickup area
* View incoming lots
* Accept/reject lots
* Confirm handovers
* Record payment

## 👨‍💼 Administrator

* Manage collectors
* Manage recyclers
* Verify recycler information
* Monitor transactions
* Monitor abnormal values
* Manage price data
* Analyze platform activity

---

# 💎 Core Innovation

Kabadiwala Connect is built around **five core innovations**:

### 1️⃣ FairValue

> **Know what your e-waste is worth.**

### 2️⃣ SmartMatch

> **Find the best authorized recycler.**

### 3️⃣ Digital E-Waste Passport

> **Track the material throughout the recycling chain.**

### 4️⃣ Voice + Offline First

> **Make the platform usable by real-world collectors.**

### 5️⃣ Smart Collection

> **Combine nearby collections and reduce transportation costs.**

---

# 🎯 Why Kabadiwala Connect?

### Current Situation

```text
Collector
   ↓
Local Intermediary
   ↓
Unknown Processing
   ↓
Limited Traceability
```

### Proposed System

```text
Collector
   ↓
Kabadiwala Connect
   ↓
Fair Price
   ↓
Authorized Recycler
   ↓
Verified Handover
   ↓
Traceable Recycling
```

---

# 📈 Expected Impact

### Economic

* Better price transparency
* Improved collector earnings
* Reduced dependence on intermediaries
* Better access to recyclers

### Environmental

* More e-waste enters formal recycling
* Reduction in unsafe processing
* Better recovery of valuable materials
* Reduced unnecessary transportation

### Social

* Improved safety awareness
* Digital transaction history
* Better access to formal recycling networks
* Inclusive technology for low-literacy users

---

# 🧪 Field Validation

The project will be validated through direct interaction with **at least two working scrap collectors or aggregators**, as required by the problem statement.

### Research Goals

We will investigate:

* How collectors currently determine prices
* How recyclers are selected
* Common transaction problems
* Connectivity limitations
* Preferred languages
* Safety practices
* Payment preferences
* Willingness to use digital tools

### Design Principle

> **Build with collectors, not just for collectors.**

---

# 💰 Unit Economics

A key part of the project is comparing:

### Existing Model

```text
Collection
    ↓
Intermediary
    ↓
Recycler
```

versus:

### Kabadiwala Connect

```text
Collection
    ↓
Platform
    ↓
Authorized Recycler
```

We will measure:

* Collector earnings
* Transportation cost
* Recycler acquisition cost
* Pickup efficiency
* Platform operating cost
* Potential revenue/sustainability model

---

# 🗺️ Development Roadmap

## Phase 1 — Research

* Interview collectors
* Identify major pain points
* Gather initial material data
* Research recycler ecosystem

## Phase 2 — MVP

* Collector app
* Material lots
* Price board
* Recycler discovery
* Earnings ledger

## Phase 3 — Traceability

* Lot IDs
* QR codes
* Handover records
* Recycler dashboard

## Phase 4 — AI

* Material classification
* Price estimation
* Smart matching
* Anomaly detection

## Phase 5 — Offline & Vernacular

* Marathi
* Hindi
* Voice
* Offline synchronization

## Phase 6 — Validation

* Field testing
* Usability testing
* Transaction simulation
* Unit economics

---

# 🏆 SIH Demonstration Flow

Our live demonstration will follow a real-world scenario:

```text
1. Collector photographs e-waste
              ↓
2. AI identifies material
              ↓
3. Collector enters weight
              ↓
4. Platform estimates fair value
              ↓
5. Nearby authorized recyclers displayed
              ↓
6. SmartMatch recommends best option
              ↓
7. Collector creates digital lot
              ↓
8. Recycler accepts lot
              ↓
9. QR-based handover
              ↓
10. Payment recorded
              ↓
11. Digital receipt generated
              ↓
12. Lot becomes traceable
```

---

# 🌟 Future Scope

Potential future extensions include:

* IoT-enabled weighing
* Advanced price forecasting
* Automated pickup optimization
* More Indian languages
* National recycler network
* EPR ecosystem integration
* Advanced material recognition
* Collector reputation/reliability scoring
* Recycling impact analytics
* Government and institutional dashboards

---

# 🤝 Team

### Team Name

**[Your Team Name]**

### Team Members

| Name     | Role                |
| -------- | ------------------- |
| Member 1 | AI/ML               |
| Member 2 | Backend             |
| Member 3 | Mobile Development  |
| Member 4 | Frontend            |
| Member 5 | Data & Research     |
| Member 6 | Deployment / DevOps |

---

# 📜 SIH Information

| Field        | Details                    |
| ------------ | -------------------------- |
| Problem ID   | **SIH26229**               |
| Problem      | **Kabadiwala Connect**     |
| Organisation | Ministry of Defence        |
| Department   | Indian Army (DGIS)         |
| Theme        | Clean & Green Technology   |
| Category     | Software                   |
| Event        | Smart India Hackathon 2026 |

---

# 🌱 Our Mission

> ### **Make formal recycling the easiest, safest, and most profitable choice for India's informal e-waste collectors.**

**Collect Smart. Sell Fair. Recycle Safe. Track Everything.**

---

<p align="center">
  <b>♻️ Kabadiwala Connect — Turning Informal Collection into a Formal, Fair & Traceable Recycling Chain.</b>
</p>
