# google-analytics-4-notes
GA4 certification notes + practical tracking, audiences, attribution, Google Ads &amp; BigQuery
# Google Analytics 4 — Practical Knowledge & Certification Notes

This repository documents the **core knowledge and practical skills** I acquired while completing the **Google Analytics 4 Certification**.

It focuses on **real-world usage**, not theory only, and reflects how GA4 is actually used for:
- business analysis
- conversion tracking
- marketing optimization
- cross-platform measurement (web + app)

---

## 🎯 Purpose

The goal of this repository is to demonstrate:
- a **clear understanding of GA4 fundamentals**
- the ability to **configure, analyze, and interpret data**
- practical readiness to **support real clients and real websites**

This is not a demo or a tutorial dump.  
It is a **structured summary of applied GA4 knowledge**.

---

## 🧠 Core GA4 Concepts

### Event-based data model
- GA4 is fully **event-driven**
- All interactions are events (page_view, click, scroll, purchase, etc.)
- No more views or hits (Universal Analytics model)

### Key components
- **Event** → user action
- **Event parameter** → additional context (page, video name, value)
- **Dimension** → descriptive attribute (device, country, page)
- **Metric** → numeric value (users, conversions, revenue)

---

## 👤 Data scope (critical)
- **User scope** → long-term attributes (language, loyalty status, User-ID)
- **Session scope** → visit-level context
- **Event scope** → single interaction

Rule of thumb:
- Describes a user → User
- Counts something → Metric
- Describes something → Dimension

---

## ⚙️ Data Collection & Setup

### Analytics tag
- Websites use the **GA4 Analytics tag**
- Mobile apps use **Firebase SDK**

### Data streams
- One GA4 property
- Multiple data streams:
  - Web
  - iOS
  - Android

### Enhanced measurement
Automatically collects events such as:
- scrolls
- outbound clicks
- site search
- video interactions

No additional code required.

---

## 🎯 Events & Conversions

### Event creation
- New events can be created from existing events
- Conditions can be applied (e.g. page = homepage)
- No code changes required

### Key events (conversions)
- Important business actions
- Used for:
  - reporting
  - optimization
  - Google Ads bidding

---

## 👥 Audiences

### Standard audiences
- Based on events, pages, sessions, behaviors

### Predictive audiences
- Powered by machine learning
- Examples:
  - likely purchasers in next 7 days
  - churn risk users

### Audience triggers
- Automatically fire an event
- When a user **enters an audience**

Audience → event (not the other way around)

---

## 📊 Reports

### Standard reports
Located in **Reports**:
- Acquisition
- Engagement
- Monetization
- Retention
- Demographics & Technology

These are **ready-to-use insights** for common business questions.

---

## 🔍 Explorations (advanced analysis)

Located in **Explore**:
- Free form analysis
- Funnel exploration
- Cohort analysis
- Segment overlap

Notes:
- Explorations are private by default
- Can be shared in read-only mode

---

## 📈 Attribution & Advertising

### GA4 + Google Ads
- GA4 conversions can be imported into Google Ads
- Used for **Smart Bidding**
- Enables performance-driven optimization

### Attribution paths
- Found under **Advertising**
- Analyze touchpoints before conversion

---

## 🧪 BigQuery & Advanced Data

### BigQuery export
- Event-level raw data
- SQL-based analysis
- Combine GA4 with:
  - CRM data
  - offline sales
  - POS systems

Export types:
- Daily
- Streaming

---

## 🔄 Offline & Server-side Data

### Measurement Protocol
- Send events directly to GA servers
- From:
  - POS systems
  - backend services
  - CRM platforms

No browser or app required.

---

## 🧩 Customization & Governance

### Library
- Controls which reports appear in navigation
- Required for permanent report changes

### GA360 features
- Sub-properties → filtered datasets
- Roll-up properties → consolidated views

---

## 🔒 Privacy & Data Controls

- Data retention settings
- Consent mode
- Events excluded from ad personalization:
  - still measured
  - not used for advertising

---

## 🤖 Intelligence & Automation

- Anomaly detection
  - detects unexpected traffic changes
- Conversion modeling
  - fills gaps caused by consent or device fragmentation

---

## 🧾 Professional Summary

Google Analytics 4 certified, with strong practical knowledge of event-based analytics, conversion tracking, audience creation, attribution modeling, and integration with Google Ads and BigQuery. Experienced in configuring GA4 for real business use cases and actionable insights.

---

## 📌 Status

- Certification completed
- Knowledge validated through assessment
- Applied, not theoretical

---

## 📬 Usage

This documentation can be used as:
- GitHub portfolio reference
- Client credibility proof
- Freelance profile support
- Internal analytics documentation

