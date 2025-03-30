![Screenshot 2025-03-28 174337](https://github.com/user-attachments/assets/eaf23054-8b7a-41af-ae6a-2381d3a1dd5d)
*************************************************************************************************************************

📊 Industry Insights
*********************
![Screenshot 2025-03-30 124250](https://github.com/user-attachments/assets/42218305-27e4-4d4f-97c3-ce728f393fe5)
*************************************************************************************************************************

🎯 AI-Powered Interview Preparation
*************************************
![Screenshot 2025-03-30 124336](https://github.com/user-attachments/assets/b6600fe5-87ef-4e7a-8579-f5f06e0de3ab)
*************************************************************************************************************************

🌐 Live Demo : https://ai-career-coach-9u21.vercel.app/


🎯 AI Career Coach – Full-Stack Career Guidance Platform
A professional AI-powered career coaching platform built using Next.js, TailwindCSS, Prisma, Shadcn UI, and Gemini AI.
This platform offers resume building, AI-generated cover letters, interview preparation, and industry insights to help job seekers.

🚀 Tech Stack
Technology	Purpose
Next.js	Frontend framework (React + SSR)
TailwindCSS	Modern responsive UI design
Shadcn UI	Pre-built styled components
Prisma	ORM for PostgreSQL database
NextAuth.js	Secure authentication & authorization
Gemini AI	AI-powered resume & interview coaching
Axios	API calls and data fetching
Zod	Form validation
PostgreSQL	Scalable database


✨ Key Features
✅ AI-Powered Resume Builder

Generates professional resumes based on user input

Provides AI-driven improvement suggestions

✅ Cover Letter Generator

Tailors personalized cover letters based on job description

✅ Interview Preparation

AI mock interviews with real-time feedback

NLP-based analysis of user responses

✅ Industry Insights & Job Trends

Analyzes latest job trends, skills demand, and salaries

✅ Responsive UI with TailwindCSS & Shadcn UI

Fully responsive across mobile, tablet, and desktop

Styled with Shadcn UI components

✅ Optimized Backend with Prisma ORM

PostgreSQL-based scalable database

API endpoints for AI, authentication, and job data


🗂 Folder Structure

     /ai-career-coach
     ├── /client                      # Frontend (Next.js + TailwindCSS)
     │   ├── /src
     │   │   ├── /app                 # App router structure
     │   │   │   ├── /api             # API routes
     │   │   │   │   ├── /resume      # Resume AI API
     │   │   │   │   ├── /cover       # Cover Letter AI API
     │   │   │   │   ├── /interview   # Mock Interview API
     │   │   │   │   ├── /auth        # Authentication API (NextAuth.js)
     │   │   │   ├── /dashboard       # User Dashboard
     │   │   │   ├── /resume-builder  # Resume Builder Page
     │   │   │   ├── /cover-letter    # Cover Letter Page
     │   │   │   ├── /interview-prep  # Interview Prep Page
     │   │   │   ├── /insights        # Industry Insights Page
     │   │   ├── /components          # UI Components (Navbar, Buttons, Forms)
     │   │   ├── /lib                 # Utility functions (API calls, auth, validation)
     │   │   ├── /hooks               # Custom React hooks
     │   │   ├── /styles              # Tailwind CSS styles
     │   │   ├── /prisma              # Prisma schema & migrations
     │   │   ├── layout.tsx           # App layout (Navbar, Footer)
     │   │   ├── page.tsx             # Landing Page
     │   ├── .env                     # Environment variables
     │   ├── package.json             # Dependencies
     │   ├── next.config.js           # Next.js config
     │   ├── tailwind.config.js       # Tailwind CSS config
     │   ├── prisma/schema.prisma     # Prisma database schema
     │   ├── README.md                # Project documentation

    ├── /server                      # Backend (Node.js + Prisma + AI APIs)
    │   ├── /controllers             # Business logic functions
    │   ├── /routes                  # API endpoints
    │   ├── /models                  # Prisma models
    │   ├── /middleware              # Authentication middleware
    │   ├── /utils                   # Helper functions (validation, token handling)
    │   ├── /config                  # Database & AI API configuration
    │   ├── /server.ts               # Main backend entry file
    │   ├── .env                     # Backend environment variables
    │   ├── package.json             # Backend dependencies
    │   ├── tsconfig.json            # TypeScript config    

    ├── .gitignore                    # Files & directories ignored by Git
    ├── README.md                     # Project documentation




  📌 Detailed Folder Explanation
  
     Path	Description
    /client	Contains the frontend code (Next.js + TailwindCSS)
    /client/src/components	Reusable UI components (Buttons, Modals, Cards)
    /client/src/pages	Page components (Resume, Cover Letter, Interview, Insights)
    /client/src/services	Service functions for API calls using Axios
    /server	Contains the backend code (Node.js + Prisma)
    /server/controllers	Business logic functions for AI & user management
    /server/routes	API endpoints (e.g., /api/resume, /api/auth)
    /server/models	Prisma schemas for database tables
    /server/middleware	Auth middleware (JWT, OAuth, role-based access)
    /server/utils	Helper functions for token handling & validation
    .env	Environment variables (DB connection, API keys, JWT secrets)
    .gitignore	Specifies ignored files/folders in Git
    README.md	Project documentation

🔥 Core API Endpoints
 Auth Routes 
    
    Endpoint	Method	Description
    /api/auth/signup	POST	Register new user
    /api/auth/login	POST	Login user
    /api/auth/logout	POST	Logout user
    /api/auth/session	GET	Check user authentication
    Resume & Cover Letter Routes
    Endpoint	Method	Description
    /api/resume/generate	POST	AI-powered resume builder
    /api/cover/generate	POST	AI-powered cover letter generator
    Interview Prep & Insights
    Endpoint	Method	Description
    /api/interview/mock	POST	AI-based interview feedback
    /api/insights/trends	GET	Fetch industry job trends

3️⃣ Set Environment Variables

    DATABASE_URL=
    NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
    CLERK_SECRET_KEY=
    NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
    NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
    NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/onboarding
    NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/onboarding
    GEMINI_API_KEY=


🛠️ 1. Project Setup
📌 Initialize Next.js App

    npx create-next-app@latest ai-career-coach --typescript --tailwind --eslint --app

🛠️ Database Setup (PostgreSQL + Prisma)

    npm install prisma @prisma/client

📌 6. Run The Project   

    npm run dev

🔗 Contact
 Email: vikassrathod2002@gmail.com






