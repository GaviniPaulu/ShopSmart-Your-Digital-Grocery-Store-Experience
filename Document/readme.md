🛒 ShopSmart: Your Digital Grocery Store

📌 Description ShopSmart is a full-stack web application that offers a seamless digital grocery shopping experience. Customers can explore a wide range of products, view categories, add items to the cart, and complete purchases securely. It also supports seller and admin functionality for product management and inventory control.

Built using React, Node.js, Express, and MongoDB, ShopSmart is optimized for speed, user-friendliness, and scalability.

🧰 Tech Stack

Technology  ----- Purpose
React	      ----- Frontend UI
Tailwind CSS-----	Responsive styling
Express.js  -----	Backend API
Node.js	    ----- Server-side JavaScript runtime
MongoDB	    ----- NoSQL database
Mongoose	  ----- MongoDB object modeling
Axios	      ----- HTTP client for API requests
Vite	      ----- React build tool (for fast dev)

📁 Folder Structure grocery-aisle-digital-hub-main/ │ ├── client/ # Frontend (React) │ ├── src/ │ │ ├── components/ # Shared components (Header, Footer, UI) │ │ ├── contexts/ # Cart context │ │ ├── pages/ # Pages (AllProductsPage, Cart, etc.) │ │ ├── data/ # Dummy item utils (fallback) │ │ └── main.tsx # Entry point │ ├── backend/ # Backend (Node.js + Express) │ ├── models/ # Mongoose models │ ├── routes/ # API routes │ ├── scripts/ # DB seeding script │ ├── data/ # seedProducts.json │ └── server.js # Main server file

✅ Features 🛍️ For Users Browse 25–30 grocery items by category

Filter and sort by name or price

Add to cart with real-time notifications

View item image, description, unit, and discount

🧑‍💼 For Admins Add, update, or remove products (future scope)

Inventory and sales insights (future scope)

🧩 Tech Highlights Cart context using React Context API

Backend API with Express & MongoDB

Product seeding script (seed.js)

Responsive design using TailwindCSS

Modular code structure

🚀 Getting Started

Clone the repository
git clone https://github.com/yourusername/shopsmart.git cd grocery-aisle-digital-hub-main ⚙️ Backend Setup cd backend npm install Seed Products: node scripts/seed.js Start Server: node server.js Backend API will run at: http://localhost:5000/api/products
💻 Frontend Setup cd client npm install npm run dev App will run at: http://localhost:5173

📝 Future Improvements User authentication (JWT)

Admin panel for sellers

Payment gateway integration

Product reviews and ratings

Order history and tracking
