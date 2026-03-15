# Pixora AI

Pixora AI is a full-stack AI-powered image processing SaaS platform that allows users to upload images and apply advanced AI-based transformations such as background removal, object recoloring, generative fill, and image restoration.  
The platform includes secure authentication, a credit-based usage system, and Stripe payment integration for purchasing additional credits.

---

## 🚀 Live Demo
https://pixora-ai-ntgh.vercel.app

## 📂 GitHub Repository
https://github.com/Amar-Gupta-721/pixora_ai

---

# 📌 Features

- AI-powered image transformations
- Background removal using AI
- Object recoloring
- Generative fill
- Image restoration
- Secure user authentication
- Credit-based SaaS model
- Stripe payment integration
- Image upload and storage
- Responsive UI for all devices
- Protected routes for authenticated users
- Real-time image preview

---

# 🧠 AI Capabilities

Pixora AI integrates AI-powered image transformations using Cloudinary APIs:

- Background Removal
- Object Recoloring
- Generative Fill
- Image Restoration

These transformations allow users to easily edit images without requiring manual design tools.

---

# 💳 SaaS Credit System

- New users receive **10 free credits** upon registration.
- Each AI transformation **deducts 1 credit**.
- Users can **purchase additional credits through Stripe payments**.
- Credits are securely stored and managed in the database.

---

# 🔐 Authentication & Security

The platform uses **Clerk Authentication** which provides:

- Secure login & signup
- Protected routes
- User session management
- Webhook support for syncing users with the database

---

# 🛠️ Tech Stack

## Frontend
- Next.js
- React
- TypeScript
- Tailwind CSS
- React Hook Form
- Zod

## Backend
- Next.js Server Actions
- Node.js

## Database
- MongoDB

## Authentication
- Clerk Authentication

## Payments
- Stripe

## AI & Media Processing
- Cloudinary

## Tools & Platforms
- Git
- GitHub
- Vercel
- VS Code

---

# 🌐 Deployment

This project is deployed using **Vercel**.

To deploy:

- Push your project to GitHub
- Import the repository into Vercel
- Add environment variables
- Deploy

---

# 📦 Installation & Setup

### 1️⃣ Clone the repository

```bash
git clone https://github.com/your-username/pixora_ai.git
```

### 2️⃣ Navigate into the project directory

```bash
cd pixora_ai
```

### 3️⃣ Install dependencies

```bash
npm install
```

### 4️⃣ Create environment variables

```bash
NEXT_PUBLIC_SERVER_URL=

MONGODB_URL=

NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=

NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/

NEXT_PUBLIC_CLOUDINARY_CLOUD_NAME=
CLOUDINARY_API_KEY=
CLOUDINARY_API_SECRET=

STRIPE_SECRET_KEY=
NEXT_PUBLIC_STRIPE_PUBLISHABLE_KEY=
WEBHOOK_SECRET=
```

### 5️⃣ Run the development server

```bash
npm run dev
```
