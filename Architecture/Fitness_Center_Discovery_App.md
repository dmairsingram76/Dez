# Fitness Center Discovery App

An AI-powered application that helps users discover personalized
wellness and fitness centers near them through an intelligent
conversational interface with Dez, your fitness assistant.

## 🎯 Overview

This app uses AI to conduct natural language conversations, collect
comprehensive health and fitness information, and provide personalized
recommendations for nearby fitness facilities. Users can interact with
Dez (our AI assistant) through chat or direct form input to provide
their information, and receive tailored exercise recommendations along
with nearby fitness centers that match their needs.

## ✨ Features

-   **Dez AI Assistant**: Chat with our friendly AI assistant to answer
    questions naturally
-   **Dual Input Methods**: Choose between conversational chat or direct
    form input
-   **Comprehensive Questionnaire**: Covers personal info, health &
    safety, goals, lifestyle, and preferences
-   **Personalized Recommendations**: AI-powered exercise
    recommendations based on your profile
-   **Location-Based Search**: Find nearby fitness centers matching your
    needs
-   **Multi-Channel Delivery**: Receive recommendations via app, email,
    or WhatsApp

## 🚀 Getting Started

### Prerequisites

-   Node.js (v18 or higher)
-   npm or yarn
-   API keys for:
    -   LLM service (OpenAI GPT-4 or Anthropic Claude)
    -   Google Maps API
    -   Email service (SendGrid, Mailgun, etc.)

### Installation

``` bash
# Clone the repository
git clone [repository-url]

# Navigate to project directory
cd fitness-center-discovery-app

# Install dependencies
npm install

# Set up environment variables
cp .env.example .env
# Edit .env with your API keys

# Run development server
npm run dev
```

## 📁 Project Structure

    fitness-center-discovery-app/
    ├── src/
    │   ├── components/       # React components
    │   │   ├── dez/         # Dez AI chat interface
    │   │   ├── forms/       # Form components
    │   │   └── shared/      # Shared UI components
    │   ├── services/        # API services
    │   │   ├── llm/         # LLM integration
    │   │   ├── maps/        # Maps API integration
    │   │   └── email/       # Email service
    │   ├── hooks/           # Custom React hooks
    │   ├── utils/           # Utility functions
    │   └── types/           # TypeScript types
    ├── server/              # Backend API
    │   ├── routes/          # API routes
    │   ├── models/          # Database models
    │   └── services/        # Business logic
    ├── docs/                # Documentation
    │   └── PRD.md           # Product Requirements Document
    └── README.md            # This file

## 🏗️ Architecture

### Frontend

-   **Framework**: React/Next.js
-   **State Management**: Redux/Zustand/Context API
-   **UI Library**: Material-UI/Tailwind CSS

### Backend

-   **Runtime**: Node.js/Python
-   **Framework**: Express/FastAPI
-   **Database**: PostgreSQL/MongoDB
-   **LLM**: OpenAI GPT-4 or Anthropic Claude

### Third-Party Services

-   Google Maps API (geolocation & places)
-   LLM API (OpenAI/Anthropic)
-   Email service (SendGrid/Mailgun)
-   WhatsApp API (Twilio - post-MVP)

## 📦 MVP Epics

1.  ✅ **User Onboarding & Personal Information Collection**
2.  ⏳ **Conversational AI Interface**
3.  ⏳ **Health & Safety Questionnaire (PAR-Q)**
4.  ⏳ **Goals & Motivation Assessment**
5.  ⏳ **Lifestyle & Availability Assessment**
6.  ⏳ **Exercise Preferences Assessment**
7.  ⏳ **LLM Recommendation Engine**
8.  ⏳ **Location-Based Facility Search**
9.  ⏳ **Recommendation Summary & Output**
10. ⏳ **Data Management & Privacy**

## 🧪 Testing

``` bash
npm test
npm run test:integration
npm run test:e2e
npm run test:coverage
```

## 🔒 Security & Privacy

-   All data encrypted at rest
-   HTTPS only
-   GDPR compliant
-   User data deletion capability
-   Secure API authentication
-   Input validation and sanitization
-   Rate limiting on API endpoints

## 🗝️ Environment Variables

Create a `.env` file in the root directory:

    OPENAI_API_KEY=your_openai_key
    ANTHROPIC_API_KEY=your_anthropic_key
    GOOGLE_MAPS_API_KEY=your_google_maps_key
    SENDGRID_API_KEY=your_sendgrid_key
    EMAIL_FROM=noreply@yourapp.com
    DATABASE_URL=your_database_url
    NEXT_PUBLIC_APP_URL=http://localhost:3000
    NODE_ENV=development
    SESSION_SECRET=your_session_secret
    TWILIO_ACCOUNT_SID=your_twilio_sid
    TWILIO_AUTH_TOKEN=your_twilio_token

## 🚢 Deployment

### Staging

``` bash
npm run build:staging
npm run deploy:staging
```

### Production

``` bash
npm run build:production
npm run deploy:production
```

## 📊 Monitoring

-   Sentry
-   Google Analytics / Mixpanel
-   DataDog / New Relic
-   Winston / Pino

## 🤝 Contributing

1.  Fork the repository
2.  Create a feature branch
3.  Commit your changes
4.  Push the branch
5.  Open a Pull Request

## 📄 License

\[Your License Here\]

## 👥 Team

-   **Product Manager**: \[Name\]
-   **Tech Lead**: \[Name\]
-   **Developers**: \[Names\]

## 📞 Support

-   Open an issue
-   Contact support email
-   Check documentation

## 🧭 Roadmap

### MVP

-   [x] Setup
-   [x] Personal info collection
-   [ ] Remaining assessments
-   [ ] Recommendation engine
-   [ ] Facility search

### Post-MVP

-   [ ] Voice input
-   [ ] WhatsApp integration
-   [ ] Mobile app
-   [ ] Booking integration
-   [ ] Progress tracking

------------------------------------------------------------------------

**Built with ❤️ by \[Your Team Name\]**

------------------------------------------------------------------------

## Quick Links

-   Documentation
-   Report a Bug
-   Request a Feature
-   Changelog
