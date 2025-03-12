Full Stack Project Management Tool - TrackIt

Overview

TrackIt is a full-stack project management tool built using modern web technologies to streamline task tracking, sprint planning, and issue management. It provides a structured way to manage projects, users, and issues efficiently.

Tech Stack

Frontend: Next.js, React, Tailwind CSS

Backend: Prisma, Neon (PostgreSQL)

Auth: Clerk

UI Components: Shadcn UI

Features

✅ User Authentication – Secure login and user management with Clerk.
✅ Project & Sprint Management – Organize projects and track sprints.
✅ Issue Tracking – Create, assign, and prioritize issues with ease.
✅ Database Integration – Powered by PostgreSQL with Prisma ORM.
✅ Modern UI – Beautiful, responsive design with Tailwind CSS & Shadcn UI.

Environment Variables

Make sure to create a .env file with the following variables:

DATABASE_URL=
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/onboarding
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/onboarding

How to Run

git clone
cd my-app
npm install
npx prisma migrate deploy
npm run dev

⚠️ Note

🚫 Do not run in PSG WiFi (Neon DB won't connect).
