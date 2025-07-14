

  <h3 align="center">MOCK-MATE: A job interview preparation platform powered by Vapi AI Voice agents</h3>

   

## 📋 <a name="table">Table of Contents</a>

1. 🤖 [Introduction](#introduction)
2. ⚙️ [Tech Stack](#tech-stack)
3. 🔋 [Features](#features)

## <a name="introduction">🤖 Introduction</a>

Built with Next.js for the user interface and backend logic, Firebase for authentication and data storage, styled with TailwindCSS and using Vapi's voice agents, MOCK-MATE is a website project designed to help you learn integrating AI models with your apps. The platform offers a sleek and modern experience for job interview preparation.


## <a name="tech-stack">⚙️ Tech Stack</a>

- Next.js
- Firebase
- Tailwind CSS
- Vapi AI
- shadcn/ui
- Google Gemeni

## <a name="features">🔋 Features</a>

👉 **Authentication**: Sign Up and Sign In using password/email authentication handled by Firebase.

👉 **Create Interviews**: Easily generate job interviews with help of Vapi voice assistants and Google Gemini.

👉 **Get feedback from AI**: Take the interview with AI voice agent, and receive instant feedback based on your conversation.

👉 **Interview Page**: Conduct AI-driven interviews with real-time feedback and detailed transcripts.

👉 **Dashboard**: Manage and track all your interviews with easy navigation.

👉 **Responsiveness**: Fully responsive design that works seamlessly across devices.

and many more, including code architecture and reusability



**Installation**

Install the project dependencies using npm:

```bash
npm install
```

**Set Up Environment Variables**

Create a new file named `.env.local` in the root of your project and add the following content:

```env
NEXT_PUBLIC_VAPI_WEB_TOKEN=
NEXT_PUBLIC_VAPI_WORKFLOW_ID=

GOOGLE_GENERATIVE_AI_API_KEY=

NEXT_PUBLIC_BASE_URL=

NEXT_PUBLIC_FIREBASE_API_KEY=
NEXT_PUBLIC_FIREBASE_AUTH_DOMAIN=
NEXT_PUBLIC_FIREBASE_PROJECT_ID=
NEXT_PUBLIC_FIREBASE_STORAGE_BUCKET=
NEXT_PUBLIC_FIREBASE_MESSAGING_SENDER_ID=
NEXT_PUBLIC_FIREBASE_APP_ID=

FIREBASE_PROJECT_ID=
FIREBASE_CLIENT_EMAIL=
FIREBASE_PRIVATE_KEY=
```

Replace the placeholder values with your actual **[Firebase](https://firebase.google.com/)**, **[Vapi](https://vapi.ai/?utm_source=youtube&utm_medium=video&utm_campaign=jsmastery_recruitingpractice&utm_content=paid_partner&utm_term=recruitingpractice)** credentials.

**Running the Project**

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser to view the project.























   
