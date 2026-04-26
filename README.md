Iconic Esports

A full-stack, production-ready esports platform built with a scalable SaaS architecture.
It supports role-based access, tournament management, real-time updates, and secure verification systems.

🚀 Features
🔐 Authentication & Authorization
Single login system with role-based access:
User
Admin
Tournament Organizer
Sponsor
Secure authentication using JWT
Email verification (OTP + Magic Link)
Password reset system
👤 User Onboarding
Multi-step onboarding flow:
Select games (BGMI, Free Fire, Valorant)
Enter IGN, UID, Role
Upload profile proof (screenshot)
Profile management system
🆔 KYC Verification
Integration with DigiLocker / Aadhaar APIs
Admin approval workflow
Fraud detection system
Secure storage of sensitive data
🏆 Tournament Engine
Create and manage tournaments
Support for:
Single Elimination
Round Robin
Auto-generated brackets
Match scheduling & results tracking
⚡ Real-Time System
Live match updates
Notifications system
Team communication (chat)
Powered by WebSockets
📊 Dashboards
User Dashboard: stats, match history, performance
Organizer Dashboard: tournament analytics
Sponsor Dashboard: engagement & ROI tracking
Admin Panel: full platform control
💰 Payments & Monetization
Integration with Razorpay
Entry fees & prize pools
Wallet system
Transaction history
🏗️ Tech Stack
Frontend
React / Next.js
Tailwind CSS
Backend
Node.js (Express)
Database
PostgreSQL / Supabase
Realtime
WebSockets (Socket.io)
Integrations
Firebase (optional)
Razorpay (payments)
DigiLocker / Aadhaar (KYC)
📂 Project Structure
iconic-esports/
│
├── client/        # Frontend (React / Next.js)
├── server/        # Backend (Node.js API)
├── docs/          # API docs, architecture
├── README.md
⚙️ Installation & Setup
1. Clone the repository
git clone https://github.com/sunnyfarmana/iconic-esports.git
cd iconic-esports
2. Setup Backend
cd server
npm install
npm run dev
3. Setup Frontend
cd client
npm install
npm run dev
🔐 Environment Variables

Create a .env file in both client and server:

🧠 System Architecture
Role-based access control (RBAC)
RESTful API design
Modular backend structure
Scalable database schema
Real-time event-driven system
🚧 Future Enhancements
AI-based fraud detection
Advanced matchmaking system (ELO ranking)
Mobile app version
Live streaming integration
Leaderboard optimization
🤝 Contributing

Contributions are welcome!
Feel free to fork the repo and submit a pull request.

📜 License

This project is licensed under the MIT License.
