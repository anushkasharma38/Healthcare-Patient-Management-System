🏥 Healthcare Patient Management System










A secure, full-stack hospital management application designed to manage patients, roles, and analytics with Flask (Python), React.js, and MongoDB.

🚀 Features

🔐 Authentication & Security: JWT, RBAC, bcrypt hashing, audit logs

🏥 Patient Management: CRUD operations, advanced search, file uploads

📊 Analytics: Demographics, diseases, revenue & performance metrics

🖥️ Admin Tools: User management, monitoring, backups, audit trails

🎨 Frontend: Responsive UI (React + Tailwind), route protection, real-time updates

🛠️ Tech Stack

Frontend: React.js, Tailwind CSS, Axios
Backend: Flask, Flask-JWT-Extended, Flask-CORS, Flask-PyMongo
Database: MongoDB (with indexing)

⚙️ Quick Start
Backend
cd backend  
python -m venv venv  
source venv/bin/activate   # Windows: venv\Scripts\activate  
pip install -r requirements.txt  
python app.py  


👉 Runs at: http://localhost:5000

Frontend
cd frontend  
npm install  
npm start  


👉 Runs at: http://localhost:3000

👤 Roles & Access

Admin → Full access, manage users & patients

Nurse → View & edit patient records

Receptionist → Add/view patients

🧩 Roadmap

✅ Email verification & password reset

✅ Deploy on Render/Netlify + MongoDB Atlas

⏳ Doctor role & appointment scheduling

⏳ Export data (PDF/Excel)

⏳ Role-based dashboards

🏁 Conclusion

A modern, secure, and scalable healthcare management solution—ideal for hospitals, clinics, and medical institutions.
