# CartFlow 🛒
A full stack e-commerce web application built with React and Django REST Framework.

##  Tech Stack
- **Frontend:** React, React Router, Context API, Tailwind CSS, Vite
- **Backend:** Django, Django REST Framework
- **Database:** PostgreSQL
- **Authentication:** JWT (JSON Web Tokens)

##  Features
- User Registration & Login with JWT Auth
- Browse Products by Category
- Product Detail Page
- Add to Cart / Remove from Cart
- Update Cart Quantity
- Checkout Page (Protected Route)
- REST API with DRF

##  Setup Instructions
### Backend
```bash
cd backend
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
```
### Frontend
```bash
cd frontend
npm install
npm run dev
```
