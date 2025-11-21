# 💪 FitForge – AI-Powered Fitness Coach

Your personal **AI fitness assistant** built with **Next.js, Tailwind, Shadcn UI, Vapi Voice AI, Convex DB, Clerk Auth, and Gemini LLM**.
Create fully personalized **workout** and **diet** plans through natural conversation.

---

## ✨ Highlights

* 🚀 **Tech Stack:** Next.js, React, Tailwind CSS, Shadcn UI
* 🎙️ **Voice AI Assistant:** Powered by Vapi
* 🧠 **LLM Integration:** Gemini AI for personalized program generation
* 🏋️ **Custom Workout Plans:** Tailored by fitness level & goals
* 🥗 **Diet Recommendations:** Personalized meal plans with allergy filtering
* 🔒 **Authentication:** Secure auth via Clerk (Google, GitHub, Email/Password)
* 💾 **Database:** Convex for real-time storage
* 🎬 **Live Program Generation:** Real-time UX with server & client components
* 💻 **Modern Layouts:** Clean UI with reusable components

---

## 🌟 Features

### 🤖 Smart AI Fitness Assistant

Talk to an intelligent voice assistant that understands your:

* Fitness goals
* Body condition & injuries
* Food preferences & allergies

### 🏋️ Personalized Workout Plans

Automatically generated routines based on your:

* Body type
* Fitness level
* Training goals (fat loss, muscle gain, mobility, etc.)

### 🥗 Custom Diet Programs

Receive AI-curated meal plans tailored to:

* Dietary preferences
* Allergies
* Lifestyle & goals

### 🔑 Authentication & Authorization

Login using:

* Google
* GitHub
* Email/Password

### 📚 Program Management

* Save multiple fitness programs
* Only the latest one remains active
* Beautiful dashboard to view your plans

### 📱 Fully Responsive

Optimized for mobile, tablet, and desktop.

---

## 🔧 Environment Variables

Create a `.env` file and add:

```env
# Clerk Authentication
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=

# Clerk Redirect URLs
NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up

# Vapi Voice AI
NEXT_PUBLIC_VAPI_WORKFLOW_ID=
NEXT_PUBLIC_VAPI_API_KEY=

# Convex Database
CONVEX_DEPLOYMENT=
NEXT_PUBLIC_CONVEX_URL=
```

---

## 🚀 Getting Started

### 1️⃣ Clone the repository

```sh
git clone <repo-url>
cd <project-folder>
```

### 2️⃣ Install dependencies

```sh
npm install
```

### 3️⃣ Set up environment variables

Add values to your `.env` file as shown above.

### 4️⃣ Run the development server

```sh
npm run dev
```

Open 👉 [http://localhost:3000](http://localhost:3000)

---

## 📦 Deployment (Vercel Recommended)

Build the production version:

```sh
npm run build
npm run start
```

Or simply connect your GitHub repo to **Vercel** for instant deployments.

---

## 🛠️ Tech Stack

| Technology       | Purpose                                 |
| ---------------- | --------------------------------------- |
| **Next.js**      | Frontend framework + API routes         |
| **React**        | UI components                           |
| **Tailwind CSS** | Fast styling                            |
| **Shadcn UI**    | Modern prebuilt UI components           |
| **Clerk**        | Authentication & user management        |
| **Vapi**         | Voice AI agent                          |
| **Convex**       | Real-time database                      |
| **Gemini AI**    | LLM for personalized program generation |

---

## 📚 Learn More

* Next.js Docs
* Clerk Docs
* Vapi Docs
* Convex Docs
* Gemini AI Docs

