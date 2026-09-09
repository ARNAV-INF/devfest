# Pastel Bean / Mellow Brews ☕

* **GDG Fest 2026 / Prototype to Product**
  * Created as part of **GDG Fest 2026 at Thapar University**.
  * Showcases the **"Prototype to Product"** workflow using **Google Stitch** (Google Labs' AI-powered UI design tool) and **GitHub Codespaces** to translate a design concept and a `DESIGN.md` guideline into a fully functional web application.

* **Project Overview & Origin**
  * The frontend was originally designed via Google Stitch and imported into GitHub Codespaces.
  * The application features an artisanal coffee shop web application named **Mellow Brews** (also known as **Pastel Bean**) with a pastel aesthetic, smooth Framer Motion animations, a functional cart, a secure order-locking mechanism, and a 1-minute live preparation tracker.

* **Architecture & Technologies**
  * The frontend is built with React/Vite, styled with Tailwind CSS, and animated using Framer Motion.
  * The backend is powered by a Node.js & Express server handling API routes, session-based order locking, and status milestones.

* **Core Features**
  * **Active Order Lock:** Prevents users from placing multiple orders simultaneously while an active order is being prepared.
  * **Live Progress Tracker:** Simulates a 60-second coffee preparation lifecycle with dynamic status milestones.
  * **Server-Side Validation:** Price calculation and order state verification are handled securely on the backend.

* **Local Setup Prerequisites**
  * Requires **Node.js** (v18 or higher recommended) installed on the local machine.

* **Local Execution Steps**
  * **1. Clone the Repository:** Clone using `git clone https://github.com/ARNAV-INF/devfest.git` and navigate into the folder using `cd devfest`.
  * **2. Install Dependencies:** Run `npm install` in the root or navigate into the server folder via `cd server && npm install && cd ..` depending on the project structure.
  * **3. Configure Environment Variables:** Create a `.env` file in the root directory or server folder with `PORT=3000` and `FRONTEND_URL=http://localhost:3000`.
  * **4. Run the Application:** Run `npm run dev` for a combined/concurrent setup, or start the backend via `cd server && npm run start` and the frontend via `npm run dev` separately.
  * Access the application in a browser by navigating to `http://localhost:3000` (or the port specified in the Vite output), or open it directly in **GitHub Codespaces** with zero local setup.
