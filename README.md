# Socially - A Modern Social Media Platform

A full-featured social media web application built with Next.js, TypeScript, Prisma, and PostgreSQL.

https://socially-lemon.vercel.app

## 🌟 Features

- **Authentication**: Secure user authentication system
- **Dark/Light Mode**: Elegant UI with theme switching
- **Social Interactions**: Create, like, comment, and delete posts
- **Real-time Notifications**: Stay updated with activity on your content
- **User Profiles**: Customizable user profiles with image uploads
- **Suggested Users**: Discover new people to follow
- **Responsive Design**: Works seamlessly on mobile, tablet, and desktop

## 🚀 Tech Stack

- **Frontend**: Next.js 15, React, TypeScript, Tailwind CSS
- **UI Components**: shadcn/ui
- **Backend**: Next.js API Routes
- **Database**: PostgreSQL with Prisma ORM
- **Authentication**: Clerk
- **File Storage**: UploadThing
- **Styling**: Tailwind CSS
- **Deployment**: Vercel

## 📋 Prerequisites

- Node.js 18+ and npm
- PostgreSQL database

## 🛠️ Installation

1. Clone the repository
   ```bash
   git clone https://github.com/winnwy/socially.git
   cd socially
   ```

2. Install dependencies
   ```bash
   npm install
   ```

3. Set up environment variables
   ```bash
   cp .env .env.local
   ```
   
4. Configure your `.env.local` with your database and authentication credentials

5. Run database migrations
   ```bash
   npx prisma migrate dev
   ```

6. Start the development server
   ```bash
   npm run dev
   ```

7. Open [http://localhost:3000](http://localhost:3000) in your browser
