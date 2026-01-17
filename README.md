# InfoSphere 🌐

**InfoSphere** is a futuristic, AI-powered news aggregation platform designed to deliver verified, high-quality news updates tailored to your region and interests. Built with **React**, **Vite**, and **Google's Gemini API**, it offers a seamless and visually stunning experience for both news readers (Citizens) and contributors (Reporters).

![InfoSphere Banner](https://via.placeholder.com/1200x400/050505/00f2ff?text=InfoSphere+AI+News)

## ✨ Features

*   **Role-Based Access:**
    *   **Citizen Mode:** Browse aggregated news from State, National, or International sources.
    *   **Reporter Mode:** Contribute stories with an integrated identity verification system.
*   **AI-Powered Content:**
    *   Utilizes **Google Gemini 2.0 Flash** to fetch, summarize, and categorize news in real-time.
    *   Intelligent news filtering by fields like **Technology / AI** and **Jobs / Daily Information**.
*   **Identity Verification:**
    *   Secure reporter onboarding with AI-based document verification (supports Indian Government IDs).
*   **Immersive UI/UX:**
    *   Cyberpunk/Futuristic aesthetic with neon accents and smooth animations.
    *   Responsive design powered by **Tailwind CSS**.
*   **Verified Sources:**
    *   Automatically validates news sources and provides links to original articles.

## 🛠️ Tech Stack

*   **Frontend:** [React 19](https://react.dev/), [Vite](https://vitejs.dev/)
*   **Styling:** [Tailwind CSS](https://tailwindcss.com/)
*   **AI Integration:** [Google GenAI SDK](https://www.npmjs.com/package/@google/genai)
*   **Language:** [TypeScript](https://www.typescriptlang.org/)
*   **Icons:** FontAwesome

## 🚀 Getting Started

Follow these steps to set up the project locally.

### Prerequisites

*   **Node.js** (v18 or higher recommended)
*   **npm** or **yarn**
*   A **Google Gemini API Key** (Get it from [Google AI Studio](https://aistudio.google.com/))

### Installation

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/Harsha754-ml/infosphere.git
    cd infosphere
    ```

2.  **Install dependencies:**
    ```bash
    npm install
    ```

3.  **Configure Environment Variables:**
    *   Rename `.env.example` to `.env`.
    *   Open `.env` and paste your Gemini API Key.
    ```env
    GEMINI_API_KEY=your_actual_api_key_here
    ```

4.  **Run the Development Server:**
    ```bash
    npm run dev
    ```

5.  **Build for Production:**
    ```bash
    npm run build
    ```

## 📂 Project Structure

```
infosphere/
├── services/
│   └── geminiService.ts   # API logic for fetching news and verifying IDs
├── App.tsx                # Main application component and routing logic
├── components/            # (Inline components in App.tsx for this prototype)
├── constants.ts           # Static data (Countries, States, Font styles)
├── types.ts               # TypeScript interfaces and Enums
├── index.html             # Entry HTML file
├── tailwind.config.js     # Tailwind configuration (via CDN or config)
└── vite.config.ts         # Vite bundler configuration
```

## 🤝 Contributing

Contributions are welcome! Please fork the repository and submit a pull request for any enhancements or bug fixes.

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).
