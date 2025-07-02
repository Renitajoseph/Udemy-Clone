# Udemy-Clone

A fully-featured Udemy-style e-learning platform built with modern web technologies.

## 🚀 Features
- Responsive **Next.js + TypeScript** frontend styled with **Tailwind CSS** and server-side rendering.
- Secure **user authentication & authorization** using **Clerk**.
- Course purchase flow powered by **Stripe**, integrated with secure payment and webhook support.
- Database interaction via **Prisma ORM** connected to **PostgreSQL**.
- Role-based access control enforced through custom middleware.

## 🧩 Tech Stack
- **Frontend**: Next.js 14, TypeScript, Tailwind CSS  
- **Backend**: Prisma ORM, PostgreSQL, Clerk  
- **Payments**: Stripe  
- **Deployment**: Vercel

## ⚙️ Setup & Development
```bash
git clone https://github.com/Renitajoseph/Udemy-Clone.git
cd Udemy-Clone
npm install
npm run dev
Head to http://localhost:3000 to explore the platform.

📦 Environment Variables
Set the following in your .env:

makefile
Copy
Edit
DATABASE_URL=
NEXT_PUBLIC_APP_URL=
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY
CLERK_SECRET_KEY
CLERK_WEBHOOK_SECRET
STRIPE_WEBHOOK_SECRET
📄 License
Licensed under MIT – see the LICENSE file for details.
