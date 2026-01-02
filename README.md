# LawHub MVP - Legal Literacy Platform for India

## Overview

LawHub is a comprehensive legal literacy web application designed to solve India's legal access crisis. With over 4 crore pending cases and complex legal language barriers, LawHub serves as an accessible companion for understanding Indian laws.

## Key Features

### 1. **Language Selection** (22 Scheduled Indian Languages)
Access legal content in your preferred language including Hindi, Bengali, Tamil, Telugu, Gujarati, Marathi, Kannada, Malayalam, Odia, Punjabi, and more.

### 2. **Smart Legal Assistant**
AI-powered guidance that explains legal concepts without providing legal advice. The assistant follows a structured approach:
- **ACKNOWLEDGMENT**: Recognizes your question
- **CONTEXT**: Provides relevant background
- **KNOWN VS DEPENDS**: Clarifies certainty levels
- **OPTIONS**: Presents alternatives
- **PROFESSIONAL REMINDER**: Guides when to seek lawyer help

### 3. **Lawyer Profiles & Directory**
Connect with verified legal professionals with their specializations and contact information.

### 4. **Case Explorer**
Learn from real-world case examples and legal scenarios.

### 5. **Law Section Explainer**
Breakdown of Indian Legal Code sections in simple, understandable language.

## Tech Stack

### Frontend
- **React 18** with TypeScript
- **React Router** for navigation
- **Tailwind CSS** for styling
- **Framer Motion** for subtle animations
- **shadcn/ui** for accessible components
- **LocalStorage** for case saving

### Backend
- **Node.js** with Express.js
- **MongoDB Atlas** for data storage
- **RESTful API** architecture

## Getting Started

### Installation

```bash
npm install
```

### Development

```bash
npm run dev
```

This will start:
- Frontend development server on `http://localhost:5173`
- Backend on `http://localhost:3000`

### Build

```bash
npm run build
```

## Project Structure

```
LawHub-MVP/
├── src/
│   ├── components/        # Reusable UI components
│   ├── pages/            # Route pages
│   ├── lib/              # Utilities and configuration
│   ├── hooks/            # Custom React hooks
│   ├── App.tsx           # Main app component
│   └── main.tsx          # Entry point
├── server/               # Backend services
│   ├── index.ts          # Express server
│   ├── routes.ts         # API routes
│   └── db.ts             # Database configuration
├── public/               # Static assets
└── package.json          # Dependencies
```

## Demo Flow

1. **Home Page**: Language selection and topic search
2. **Topic Selection**: Browse legal topics (e.g., Rent Notice)
3. **Guided Walkthrough**: 4-step explanation process
4. **AI Assistant Response**: Structured legal guidance
5. **Save Case**: Store for future reference

## Core Philosophy

LawHub is NOT a legal advice application. It is a **legal literacy companion** for Indian laws that:
- Guides thinking, not decisions
- Never provides verdicts or certainty
- Always shows uncertainty
- Connects users with professionals when needed

## Accessibility

- WCAG 2.1 compliant
- Dark mode with gold and lavender accents
- Support for 22 Indian languages
- Mobile-responsive design

## For the Exam

This MVP demonstrates:
- Full-stack architecture
- State management with React
- Responsive UI/UX design
- Integration of AI guidance
- Accessibility best practices

## Contributing

This is a hackathon project. Contributions and improvements are welcome!

## License

MIT License - See LICENSE file for details

---

**Made with ❤️ for India's legal accessibility**
