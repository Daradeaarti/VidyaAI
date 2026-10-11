# VidyAI++ – AI-Powered Multilingual Learning Platform

**An AI-powered educational platform designed to make learning accessible, interactive, and inclusive for students across India.**

## About the Project

VidyAI++ is an AI-powered multilingual educational platform designed to support students, especially learners in underserved areas of India. Many students face difficulties due to language barriers, limited access to personal tutoring, and unreliable internet connectivity.

VidyAI++ aims to address these challenges by providing multilingual AI learning assistance, interactive educational videos, offline learning support, and peer collaboration. The platform is designed to make education more accessible and engaging for students from different linguistic and educational backgrounds.

## Features

- **Multilingual Learning:** Supports learning assistance in 10+ Indian languages.
- **AI Learning Assistant:** Provides AI-based explanations to help students understand difficult concepts.
- **Interactive Video Learning:** Supports learning through educational videos and interactive content.
- **Emotion-Aware Learning:** Includes an emotion-overlay interface with a demonstration fallback.
- **Offline Learning Support:** Uses IndexedDB to support local data storage and offline access.
- **Courses and Dashboard:** Provides a dashboard for accessing courses and learning activities.
- **Quizzes and Bookmarks:** Helps students practise concepts and save useful learning materials.
- **Learning Analytics:** Displays learning progress and activity information.
- **Certificates:** Includes certificate-related functionality.
- **Community and Mentorship:** Provides community features and mentor-related functionality to encourage collaborative learning.

## Technology Stack

### Frontend
- Next.js
- React.js
- TypeScript
- Tailwind CSS v4
- Radix UI

### Backend
- Next.js App Router
- Next.js API Routes

### AI and Learning
- AI-based explanation interface
- Multilingual learning prompts
- Emotion-aware interface with demonstration fallback
- Educational video integration using YouTube

### Database and Storage
- In-memory database implementation
- IndexedDB for local browser storage and offline support

### Additional Libraries
- Recharts for charts and analytics
- jsPDF for PDF generation

## Installation and Setup

### Prerequisites
- Node.js
- npm or pnpm
- Git
- A code editor such as VS Code or Antigravity

### Step 1: Clone the Repository

```bash
git clone https://github.com/Daradeaarti/VidyaAI.git
cd VidyaAI
```

### Step 2: Install Dependencies

Using npm:

```bash
npm install
```

Alternatively, if the project uses pnpm:

```bash
pnpm install
```

### Step 3: Configure Environment Variables

Check the project documentation and source code for required environment variables. If any are needed, create a local `.env.local` file and add the required values.

Do not upload API keys, passwords, or other secrets to GitHub.

### Step 4: Run the Application

For npm:

```bash
npm run dev
```

For pnpm:

```bash
pnpm dev
```

### Step 5: Open the Application

Open the following URL in your browser:

```text
http://localhost:3000
```

The application will run locally if the required dependencies and project scripts are configured correctly.

## Project Structure

The project uses the Next.js App Router structure. Important directories and files include:

```text
VidyaAI/
├── app/
│   ├── api/
│   │   └── ai/
│   │       └── explain/
│   │           └── route.ts
│   └── ...
├── lib/
│   └── db/
│       └── index.ts
├── public/
├── package.json
├── README.md
└── ...
```

**Folder descriptions:**

- `app/` – Contains application pages and layouts.
- `app/api/` – Contains API route handlers.
- `app/api/ai/explain/` – Handles the AI explanation interface.
- `lib/db/` – Contains database-related logic and curriculum data.
- `public/` – Stores public assets, if present.
- `package.json` – Defines dependencies and application scripts.
- `README.md` – Provides project documentation and setup instructions.

The structure above is representative; retain the actual files and folders present in your local project.

## Future Scope

- Integrate a production-ready AI model for more reliable explanations.
- Expand multilingual content and curriculum coverage.
- Improve emotion-awareness capabilities and accessibility.
- Strengthen offline synchronisation and learning-resource availability.
- Add more personalised learning paths and adaptive quizzes.
- Improve mentor-student interaction and community features.
- Introduce secure authentication and persistent database storage.
- Evaluate learning outcomes and platform performance.

## Project Objective

The main objective of VidyAI++ is to make quality education more accessible through multilingual AI assistance, interactive learning resources, and technology that supports students with limited connectivity.


