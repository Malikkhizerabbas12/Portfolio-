
# ShopEase - University E-commerce Project

This package contains a full-stack e-commerce project scaffold suitable for a university assignment.

## Structure
- backend/ - Express server, Mongoose models, API routes
- frontend/ - Static frontend (HTML/CSS/JS) that consumes backend APIs
- report.md - A detailed project report draft you can convert to PDF
- assets/ - placeholder images

## Quick start (local)
1. Install MongoDB and start it.
2. Backend:
   - cd backend
   - npm install
   - copy .env.example to .env and set values
   - npm run dev
3. Frontend:
   - open frontend/index.html in a browser
   - OR serve the frontend folder with a static server (optional)

## Notes
- The frontend expects backend at http://localhost:5000/api when running locally.
- User registration and login endpoints are provided. Passwords are hashed.
- This is a project scaffold — extend as needed (admin panel, payments, UI polish).

