# YEEPING - Tinder for Travelling in Thailand

## Problem Statement: The Challenge of Adaptive & Personalized Travel

**The Problem:**
Modern travelers often struggle to plan itineraries that genuinely reflect their personal travel styles and time constraints. Existing solutions tend to offer "one-size-fits-all" lists that don't account for a user's personality (ex. introvert seeking peace vs. extrovert seeking crowds) or the varying duration of their stay. 

Furthermore, static travel plans are fragile. Unexpected events—such as sudden flooding or closures—can leave travelers stranded without a backup plan. Finally, the travel experience itself often lacks engagement, becoming a passive checklist rather than an interactive journey.

**The Solution:**
**YEEPING** is a dynamic local travel web application focused on Chiang Mai, Thailand, that solves these issues by:
1.  **Personalized Routing:** Generates optimized itineraries based on the user's "Personality Mode" (Introvert, Extrovert, Adventure) and available time (1 Day, 2 Days, Custom).
2.  **Adaptive Safety:** Features an "Emergency Plan" system that instantly reroutes users away from affected areas (e.g., flood zones) to safe, suggested alternatives.
3.  **Gamified Exploration:** Encourages physical visits through a coin reward system where users upload photos at destinations to "check in," earn currency, and track their journey.

---

## How to Run the Code

This project is built with React, TypeScript, and Vite.

### Prerequisites
- Node.js (v18 or higher recommended)
- npm

### Installation & Setup

1.  **Clone the repository** (if you haven't already):
    ```bash
    git clone <repository-url>
    cd yeeping
    ```

2.  **Install dependencies**:
    ```bash
    npm install
    ```

3.  **Start the development server**:
    ```bash
    npm run dev
    ```

4.  **Open the application**:
    Click the link provided in the terminal (usually `http://localhost:5173`) to view the app in your browser.

### Build for Production

To build the application for production deployment:

```bash
npm run build
```

The build artifacts will be stored in the `dist` directory.
