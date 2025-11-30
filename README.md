Interview Agent:-

Your Smart Guide for Professional Success

An AI-powered platform offering personalized interview preparation, industry insights, performance analytics, and intelligent resume building.

✨ Key Features
🔐 Secure Authentication

Sign-in/Sign-up using Clerk

OAuth support

Protected routes and session handling

📊 Industry Insights Dashboard

AI-generated salary insights by role & location

Skill demand analysis

Growth rate predictions

Trending skills & domain patterns

🎤 AI Interview Preparation

Dynamic Question Generation

Topic-wise (JavaScript, Python, DS, ML, etc.)

Difficulty levels: Beginner → Advanced

Industry-based scenarios

AI Answer Evaluation

Real-time scoring (1–10)

Detailed feedback

Improvement recommendations

Modes

Single Question

Full Interview Session

Timer Mode

Voice input support

📈 Performance Analytics

Progress tracking

Topic-wise scores

Historical performance charts

Weak area identification

🎮 Gamification

XP & Points system

Level-up progression

Daily streaks

Achievement badges

(Leaderboard coming soon)

📄 AI Resume Builder

ATS-friendly templates

Auto-generated content

Editable sections

Clean and structured output

🎨 Modern UI/UX

Smooth animations

Responsive design

Dark mode

Clean, accessible components

🚀 Quick Start Guide
Prerequisites

Node.js 18.17+

PostgreSQL 14+

npm / pnpm

Installation
git clone https://github.com/Supritha-09-byte/Major_Project.git
cd Major_Project/ai-career-coach
npm install

cp .env.example .env   # Add your values here

npx prisma generate
npx prisma migrate deploy

npm run dev


Open: http://localhost:3000

📋 Environment Variables (.env)
# Database
DATABASE_URL="postgres://user:password@localhost:5432/ai_career_coach"

# Clerk
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY="pk_test_..."
CLERK_SECRET_KEY="sk_test_..."
NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up

# Gemini AI
GEMINI_API_KEY="your_gemini_api_key"

# Inngest (optional)
INNGEST_EVENT_KEY="your_event_key"
INNGEST_SIGNING_KEY="your_signing_key"

API Keys Source

PostgreSQL → Neon / Supabase

Clerk → clerk.com dashboard

Gemini AI → Google MakerSuite

Inngest → inngest.com

🏗 Project Structure (Clean Overview)
ai-career-coach/
├── app/
│   ├── (auth)/          # Sign-in/Sign-up
│   ├── (main)/
│   │   ├── dashboard/   # Insights
│   │   ├── interview/   # Q&A, scoring
│   │   ├── resume/      # Resume builder
│   │   └── onboarding/  # Initial setup
│   └── api/             # API endpoints
├── actions/             # Server-side functions
├── components/          # UI and features
├── lib/                 # Utilities
├── prisma/              # Schema & migrations
├── public/              # Assets
└── data/                # Static files

🛠 Tech Stack
Category	Technology
Framework	Next.js 15
Frontend	React 19
Database	PostgreSQL + Prisma
Auth	Clerk
AI	Google Gemini + LangChain
UI	Shadcn/UI + Radix
Styling	Tailwind CSS
Forms	React Hook Form + Zod
Notifications	Sonner
Deployment	Vercel
🎯 How It Works
Interview Preparation Flow

Sign in

Choose topic + difficulty

Generate question

Type or speak your answer

Receive AI evaluation

View analytics and improve

Insights Flow

Complete onboarding

Explore industry dashboard

Check salary + growth + skills

Updated every 7 days

Development Commands
npm run dev
npm run build
npm start
npm run lint

npx prisma studio
npx prisma migrate dev
npx prisma db push

🚢 Deployment
Deploy to Vercel

Push to GitHub

Import in Vercel

Add environment variables

Deploy → Auto builds

Manual
npm run build
npm start

🐛 Common Fixes
Prisma client error
npx prisma generate

Unique constraint error
npx prisma migrate reset

Port already in use
npm run dev -- -p 3001

📝 Version 1.0.0 (Nov 2025)

AI interview system

Resume builder

Industry insights

Gamification

Analytics.

Command to run : npm run dev

Current Stack: PERN + Next.js
Component	MERN Traditional	This Project
Frontend	React	Next.js 15 (React 19)
Backend	Express.js	Next.js API Routes + Server Actions
Database	MongoDB	PostgreSQL (with Prisma ORM)
Runtime	Node.js	Node.js



