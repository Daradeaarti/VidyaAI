# VidyAI++ — AI-Powered Multilingual Smart Learning Platform

VidyAI++ is an AI-powered educational platform designed to make learning accessible, personalized, and interactive for students across India. It supports 12 languages and combines AI tutoring, emotion-aware learning, offline access, gamified quizzes, mentor booking, and certificate generation.

## Key Features

- **Multilingual Learning:** Supports English and 11 Indian languages.
- **AI Tutor:** Provides contextual explanations through an AI-powered tutoring interface.
- **Emotion-Aware Learning:** Uses browser-based facial emotion recognition to help identify possible confusion or distraction.
- **Offline Learning:** Uses IndexedDB to store learning resources and progress locally.
- **Interactive Quizzes:** Supports practice and learning progress tracking.
- **Mentor Booking:** Provides mentor-related booking functionality.
- **Certificates:** Generates downloadable course completion certificates.
- **Learning Analytics:** Displays progress, study streaks, and subject performance.

## Technology Stack

| Category | Technologies |
|---|---|
| Languages | TypeScript, JavaScript, HTML5, CSS3 |
| Frameworks | Next.js 16, React 19, Node.js |
| Styling | Tailwind CSS v4, PostCSS |
| UI Components | Radix UI, Lucide React |
| AI Integration | Vercel AI SDK, face-api.js |
| Multilingual Support | React Context, custom translation dictionaries |
| Data Fetching | SWR |
| Offline Storage | IndexedDB, idb |
| Data Management | Typed in-memory mock database |
| Validation | Zod |
| Charts and Analytics | Recharts |
| PDF Generation | jsPDF |
| Date Utilities | date-fns |

## Supported Languages

English, Hindi, Marathi, Tamil, Telugu, Bengali, Gujarati, Kannada, Malayalam, Punjabi, Odia, and Assamese.

## Architecture

The frontend uses React and TypeScript with Next.js App Router. API route handlers provide backend functionality. The AI tutoring interface uses the Vercel AI SDK, while face-api.js supports browser-based emotion recognition. IndexedDB provides local offline storage, and a typed in-memory database manages application data.

## Future Scope

- Integrate a production-ready persistent database.
- Improve offline synchronisation and multilingual content coverage.
- Evaluate emotion-recognition accuracy and accessibility.
- Enhance personalized learning recommendations.
- Strengthen authentication, privacy, and data security.

## Author

Daradeaarti



