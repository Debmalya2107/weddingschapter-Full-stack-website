#  The Weddings Chapter 

A modern, full-stack web application designed for premium wedding vendor management. This project was built to showcase comprehensive full-stack development skills, focusing on unique UI/UX, responsive design, secure authentication, and seamless frontend-backend integration.

##  Live Deployment
- **Frontend (Vercel):** [https://wedding-frontend-flax.vercel.app/](https://wedding-frontend-flax.vercel.app/)
- **Backend API (Render):** [https://weddings-backend.onrender.com](https://weddings-backend.onrender.com)
- The backend server is hosted on render free service - you may have to wait for 5 mins after opening backend api.

##  Tech Stack (Mandatory Requirements Met)

**Frontend:**
- **React.js** (Core framework)
- **TanStack Router / React Router** (Client-side routing)
- **Tailwind CSS** (Utility-first styling & responsive design)

**Backend:**
- **Node.js** (Runtime environment)
- **Express.js** (REST API framework)

**Database:**
- **PostgreSQL** (Relational database hosted via Render)

##  Enhancements & Divergence from the Inspiration Concept

While the core concept was inspired by *The Weddings Chapter*, I made several deliberate, custom UI/UX and architectural improvements to elevate the premium feel, boost user engagement, and demonstrate advanced frontend techniques:

* **Dynamic Statistics Counters:** Added animated, increasing numeric counters on the home page hero section to instantly highlight business metrics and build customer trust.
* **Scroll-Triggered Animations:** Integrated smooth fade-in and slide-up animations (via Bootstrap/AOS) tied to the user's scroll depth, creating a highly modern and fluid browsing experience.
* **Premium Typography Strategy:** Curated a custom, multi-font pairing system to distinctly separate headings, body text, and accents, giving the interface a highly sophisticated, editorial feel.
* **Global Marquee Banners:** Engineered infinite-scrolling text marquees across the application to seamlessly highlight key brand taglines without disrupting the page flow.
* **Asymmetrical Collage Galleries:** Expanded the vertical height of the web pages to accommodate richer, story-driven imagery. Instead of basic grid layouts, I designed modern, overlapping photo collages for higher visual engagement.
* **Feature Comparison Chart & Social Proof:** Overhauled the "Plans" section by building a side-by-side feature comparison matrix for easier decision-making. I also integrated "Couple Stories" alongside explicit "X/5" numeric ratings in the reviews section to maximize quantitative social proof.
* **Animated History Timeline:** Designed a vertical, animated timeline in the "About" section to visually map out the brand's legacy and commitment over the years.
* **Dedicated Vendors Directory:** Architected a brand new standalone Vendors webpage to expand the platform's utility (currently structured with static UI, prepped for dynamic database fetching).
* **Exclusive Admin Dashboard:** Built a dedicated Admin Portal to track user bookings and inquiries in one centralized table. 
    * *Note for Evaluators: For the sake of this assignment's testing process, the Admin login link is temporarily visible in the main navigation, and test credentials are provided on the login screen. In a production environment, this route would be hidden and completely secured behind strict role-based access control.*

##  Implemented Features

- **User Signup & Login:** Secure authentication flow using JWT (JSON Web Tokens) and password hashing with bcrypt. Secure, cross-domain HTTP-only cookies are implemented.
- **Home Page:** A highly responsive, modern landing page built with custom UI/UX, entirely unique to this project and optimized for all screen sizes.
- **Vendor / Service Listing:** A dynamic directory fetching live vendor data (photographers, venues, decor, etc.) directly from the PostgreSQL database.
- **Vendor Details Page:** Dedicated dynamic pages for each vendor, showcasing specific business details, pricing, and descriptions.
- **Contact / Inquiry Form:** Integrated form allowing logged-in users to send direct inquiries to specific vendors.
- **Simple User Dashboard:** A protected route where authenticated users can manage their profile information, view their submitted inquiries, and track their bookings.

##  Project Architecture & Guidelines Followed
- **Originality:** The design is conceptually inspired by premium wedding collectives but features a 100% custom UI/UX layout and feature implementation.
- **Clean Code Structure:** Strict separation of concerns. The backend utilizes a modular MVC-style architecture (Routes, Controllers, DB Config), while the frontend uses reusable React components.
- **Production-Ready Deployment:** Successfully handles CORS configurations and Cross-Site cookie policies between Vercel and Render.
 
---
