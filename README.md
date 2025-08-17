# MongoDesk

MongoDesk is a web-based application that allows users to upload `.txt` or `.csv` files and send multiple emails efficiently.  
It is designed with simplicity and scalability in mind, providing a clean interface for bulk email handling.

---

## 🚀 Features
- Upload `.txt` or `.csv` files containing email addresses.
- Send multiple emails in one go.
- Clean and minimal user interface.
- Deployed with **Vercel** for easy access.

---

## 📂 Tech Stack
- **Frontend**: Next.js, React, TailwindCSS
- **Backend**: Node.js, Express.js, MongoDB
- **Deployment**: Vercel (Frontend), Render/Other (Backend)

---

## ⚙️ Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/ayush123-bit/MongoDesk.git
   cd MongoDesk
   ```

2. Install dependencies for frontend and backend:
   ```bash
   cd frontend && npm install
   cd ../backend && npm install
   ```

3. Create a `.env` file in both frontend and backend with the required configurations.

4. Run the development servers:
   ```bash
   # Frontend
   cd frontend && npm run dev

   # Backend
   cd backend && npm start
   ```

---

## 🌐 Deployment
The application is deployed on Vercel:  
👉 [MongoDesk Live](https://mongo-desk-frontend.vercel.app/)

---

## 🔑 Challenges Faced
1. Handling bulk email sending without hitting provider rate limits.  
2. Ensuring file validation and correct parsing for `.txt` and `.csv`.  
3. Managing environment configurations across local and production.  
4. Keeping UI minimal yet functional for better user experience.  

---

## 📌 Future Enhancements
- Add email templates with customization options.  
- Support for PDF file parsing and processing.  
- Admin dashboard for monitoring email history.  

---

## 📝 License
This project is licensed under the MIT License.
