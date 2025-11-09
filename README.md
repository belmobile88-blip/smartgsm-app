# smartgsm-app
SmartGSM is a full-stack AI-powered business management platform designed for mobile phone retail and repair shops. It includes modules for point-of-sale, inventory, CRM, repair tracking, and buyback of used devices — all enhanced with intelligent automation and predictive analytics.

🚀 Features

💳 POS System: Fast checkout, VAT handling, discounts, and receipt printing<br>
🔧 Repair Management: Ticket creation, status tracking, and AI-assisted diagnostics<br>
📦 Inventory Control: Real-time stock updates, supplier integration, and alerts<br>
👥 CRM: Customer profiles, purchase history, and personalized offers<br>
🔁 Buyback Module: Estimate device value based on condition and market trends<br>
📊 Analytics Dashboard: Sales insights, margin analysis, and predictive reports<br>
🔐 Authentication & Roles: Secure login with admin, technician, and cashier roles<br>
🌐 Responsive UI: Built with React and Tailwind CSS<br>
🤖 AI Integration: OpenAI-powered diagnostics and pricing suggestions<br>

🧰 Tech Stack

Frontend: React, Tailwind CSS<br>
Backend: Node.js, Express<br>
Database: MongoDB<br>
AI Services: OpenAI API (optional)<br>

📦 Installation

# Clone the repository
git clone https://github.com/yourusername/smartgsm-app.git
cd smartgsm-app

# Install backend dependencies
cd server
npm install

# Install frontend dependencies
cd ../client
npm install

# Start backend
cd ../server
npm run dev

# Start frontend
cd ../client
npm start

🔐 Environment Variables

Create a .env file in the server directory with the following:<br>
PORT=5000<br>
MONGO_URI=your_mongodb_connection_string<br>
JWT_SECRET=your_jwt_secret<br>
OPENAI_API_KEY=your_openai_api_key (optional)<br>

📁 Folder Structure

smartgsm-app/<br>
├── client/         # React frontend<br>
├── server/         # Express backend<br>
├── README.md<br>

🤝 Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you’d like to change.<br>

📄 License

This project is licensed under the MIT License.<br>
