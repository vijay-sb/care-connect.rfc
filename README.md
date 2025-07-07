# care-connect.rfc
Submissions repository for `ASOC16` - Care Connect

> [!NOTE]
All discussions regarding `ASOC16: Care Connect` shall take place here.

## Overview
In-order to be eligible to work on this project as **Request for Code** under the banner of **Amrita Summer of Code, 2025**, you are required to form a team of size 1-4 and have all the members register at [amsoc.vercel.app](https://amsoc.vercel.app)

## Project Manager Details
@viswa4403
```json
"Name": "Vishwa A V",
"Year": "Alumni",
"Roll": "CB.EN.U4CSE21168",
"GitHub": "@viswa4403",
```

## How to Apply
Type out a message with the following details:
1. Team Name
2. Team Members' Names, Roll-Numbers and respective GitHub usernames
3. Tag the project manager as **@username**

## Guidelines
1. Keep all discussions limited to this discussion channel by tagging the project manager via **@username**
2. Do not try to contact the project manager personally unless they are open to it.
4. Maintain decorum and avoid any misbehavior with the project manager. This can be subjected to disqualification.
5. Send us an update every week with regards to your progress for your respective project. If we do not receive an update for more than 10 days then your team will be disqualified automatically.

## Project Description
CareConnect is a platform that connects individuals in need of short-term or
scheduled caregiving services (for elderly, disabled, or post-operative individuals)
with verified freelance caregivers in their locality.

The platform includes:
- customer-facing mobile app for people seeking caregiving services
- caregiver-facing mobile app for professionals providing the service
- web-based admin dashboard for operational management
- scalable backend infrastructure with secure APIs

Core use case: Book a caregiver for a few hours or schedule caregiving sessions
over a week/month.

### Core Features
1. Customer App
- Registration/Login
- Book a Caregiver (instant or scheduled)
- Live Tracking (when caregiver is on the way or in session)
- In-app Payments (wallet/cash)
- Ratings and Reviews
- Session History and Invoices
- Push Notifications

2. Caregiver App
- Registration and Document Upload (certifications, ID)
- Accept/Reject Care Requests
- Navigation Support to reach customer (Google Maps / Mapbox)
- Earnings Dashboard
- Session Details
- In-app Notifications

3. Admin Dashboard
- User and Caregiver Management
- Session History and Analytics
- Payment and Revenue Tracking
- Support Ticket Management
- Promotions and Discounts Management

### Technical Architecture
Frontend
- Customer & Caregiver Apps: React Native / Flutter
- Admin Dashboard: React.js / Next.js
Backend
- API: Node.js (Express.js) or Django (REST)
- Database: PostgreSQL, Redis
- Authentication: Firebase Auth / OAuth2.0
- Real-time Tracking: WebSockets / MQTT
- Geolocation: Google Maps API / Mapbox

### 4. Workflow Overview
Customer Flow
- Sign up/login
- Enter service location and time
- View caregiver availability and estimated charges
- Book caregiver
- Track caregiver en route or during care session
- Pay after session
- Rate caregiver

Caregiver Flow
- Register and upload documents

Wait for admin approval
- Go online to receive care requests
- Accept requests
- Complete session
- Earnings update
- min Flow
- Approves caregivers after verification
- Monitors active sessions
- Manages payments, reports, and promotions
- Handles customer/caregiver support
