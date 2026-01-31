# DormDeal

> The trusted marketplace for campus commerce.

DormDeal is a full-stack application designed to facilitate safe and easy buying and selling within university campuses. It solves the "stranger danger" aspect of public marketplaces by focusing on localized, student-to-student transactions for items like textbooks, furniture, and electronics.

## Tech Stack

*   **Framework:** [TanStack Start](https://tanstack.com/start/latest) (React, SSR)
*   **Styling:** Tailwind CSS
*   **Database:** SQLite
*   **ORM:** Drizzle ORM
*   **Authentication:** Custom Session/Cookie-based

## Features

*   **Campus-Focused Auth:** Secure sign-up/login.
*   **Marketplace Listings:** Browse, search, and filter items by category and price.
*   **Selling:** Easily post items with descriptions and images.
*   **Messaging:** Built-in inbox to negotiate prices and arrange meetups safely.
*   **User Dashboard:** Manage your active listings and profile.

## Getting Started

1.  **Clone the repository**
    ```bash
    git clone https://github.com/yourusername/dormdeal.git
    cd dormdeal
    ```

2.  **Install dependencies**
    ```bash
    npm install
    ```

3.  **Setup Database**
    ```bash
    # Generate migrations and push to SQLite file
    npm run db:push
    ```

4.  **Run the development server**
    ```bash
    npm run dev
    ```
    Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## Documentation

*   [TASKLIST.md](./TASKLIST.md) - Tracking project progress.
*   [LEARNINGS.md](./LEARNINGS.md) - Developer notes and architectural decisions.
*   [.dev0/RULES.md](./.dev0/RULES.md) - AI Coding Agent rules.