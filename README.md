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
