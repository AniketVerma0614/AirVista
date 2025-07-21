# Airvista
## Licence---

```markdown
# 🌐 AirVista – Airbnb Clone (Apna College Project)

AirVista is a full-stack Airbnb-inspired application you developed as part of Apna College’s MERN Bootcamp, featuring secure authentication, property listings, booking logic, media uploads, and geolocation!

---

## 🚀 Features

- 🏠 **Host Listings**: Create, edit, and display properties with photos and location data  
- 🔐 **Authentication**: Implemented secure signup/login via Passport.js and sessions  
- 🌍 **Geolocation Search**: Integrated Google Maps/Mapbox for location-based listing views  
- ☁️ **Media Uploads**: Image handling with Cloudinary and Multer  
- 📦 **MVC Architecture**: Organized backend with controllers, routes, models  
- 📱 **Responsive UI**: Built using EJS, Tailwind, and Bootstrap

---

## 🌐 Live Deployment

🟢 **Live Demo:** [https://airbnb-y5yx.onrender.com](https://airbnb-y5yx.onrender.com)  
🔗 **Signup Page:** [https://airbnb-y5yx.onrender.com/signup](https://airbnb-y5yx.onrender.com/signup)  
🔓 Signup/login required for full feature access (image upload, booking, etc.)

---

## 🚀 How This Stands Out

Your project is part of a strong line-up of Airbnb clones by Apna College alumni—like **Wanderlust** and others that mirror Airbnb functionality end to end :contentReference[oaicite:1]{index=1}. Compared to these:

- **AirVista** emphasizes **session‑based auth** (Passport.js), **Cloudinary media support**, and **rich MVC structuring**, aligning precisely with what hiring teams look for in a MERN QA/Dev context.
- Similar projects by Apna College peers (e.g., Wanderlust) highlight EJS templating, MongoDB session stores, Joi validation, Mapbox, and file uploads :contentReference[oaicite:2]{index=2}—you share all these, plus added UI polish with Tailwind and Bootstrap.

---

## 📂 Repo Structure

```

AirVista/
├── app.js               # Server entry point
├── controllers/         # Business logic
├── routes/              # Express routing
├── models/              # Mongoose schemas
├── views/               # EJS templates
├── public/              # Static files & screenshots
├── tests/               # (Planned) Jest & supertest tests
├── postman/             # API collections & environments
└── README.md

````

---

## 🛠️ Installation

```bash
git clone https://github.com/AniketVerma0614/AirVista.git
cd AirVista

# Install dependencies
npm install

# Create .env with:
CLOUDINARY_CLOUD_NAME=...
CLOUDINARY_KEY=...
CLOUDINARY_SECRET=...
MAP_TOKEN=...
SESSION_SECRET=...
DB_URL=...

# Run locally
npm start
````

---

## ✅ Testing

**Manual API Testing**
Use Postman collections in `/postman` for signup/login, listing creation/search, and booking flows. Run via:

```bash
cd postman
newman run AirVista.postman_collection.json -e AirVista.postman_environment.json --reporters cli,html
```

**Automated Tests with Jest & Supertest** (To be added in `/tests`), covering:

* Schema validation with Joi
* CRUD and auth-protected routes
* Media upload via Cloudinary
* Session management and data persistence flows

---

## 📚 Inspiration & References

* Apna College Airbnb-style portfolios like **Wanderlust** showcase full-stack auth, Cloudinary, Mapbox, and session handling ([LinkedIn][1], [GitHub][2], [LinkedIn][3]).
* Your approach builds on and enhances these by integrating responsive UI, session security, and enriched media workflows.

---

## 📌 Future Enhancements

* Add **booking/payment features** using Stripe or Paytm
* Create **React-based frontend** for SPA experience
* Write **end-to-end tests** with Cypress or Playwright
* Add **unit and integration tests** under `/tests` using Jest + Supertest
* Integrate **security audits** (OWASP ZAP) in CI pipeline

---

## ✍️ Credits

* **Developed by:** Aniket Verma
* **Powered by:** Apna College MERN curriculum, Delta Bootcamp
* **Inspired by:** Wanderlust and similar projects from Apna College ([LinkedIn][3], [LinkedIn][1], [GitHub][2])
* **UI/Design Inspired by:** Airbnb.com

---

## 📝 License

This project is for educational purposes only. © 2025 Aniket Verma

```

---


This project is licensed under the [MIT License](LICENCE).
## Deployment  

You can view the live deployment of this project [here](https://airbnb-y5yx.onrender.com/signup).  
