
# AI Splitwise Clone 💸🤖

A smart bill-splitting web application inspired by Splitwise, enhanced with AI features for better group expense management.

## 🚀 Features

- 🔐 User Authentication (Sign up, Log in, Log out)
- 🧾 Add and manage expenses within groups
- 📊 Dashboard to view balances and activity
- 🤖 AI-Powered suggestions for optimized settlements (optional feature)
- 🧑‍🤝‍🧑 Create and manage friend groups
- 📱 Responsive design for mobile and desktop
- 🌙 Dark/Light Mode Toggle (if applicable)

## 🛠️ Tech Stack

**Frontend:**
- React.js
- Tailwind CSS

**Backend:**
- Node.js
- Express.js

**Database:**
- MongoDB

**Authentication:**
- JWT (JSON Web Tokens)

**AI/ML Integration (optional):**
- OpenAI API (or other model integrations for smart settlements)

## 🧑‍💻 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/ramlalkumawat/ai-splitwise-clone.git
cd ai-splitwise-clone
````

### 2. Install dependencies

#### Frontend:

```bash
cd client
npm install
```

#### Backend:

```bash
cd ../server
npm install
```

### 3. Setup Environment Variables

Create a `.env` file in the `server` directory with the following variables:

```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret_key
OPENAI_API_KEY=your_openai_api_key (if using AI features)
```

### 4. Run the project

#### Start Backend:

```bash
cd server
npm run dev
```

#### Start Frontend:

```bash
cd ../client
npm start
```

### 5. Open in Browser

Navigate to: [http://localhost:3000](http://localhost:3000)

## 📂 Folder Structure

```
ai-splitwise-clone/
├── client/       # React frontend
├── server/       # Express backend
├── README.md
└── ...
```

## 🧠 Future Features

* Voice input for adding expenses
* Graphs and analytics of expenses
* Notification system
* Mobile app integration (React Native)

## 🙌 Contribution

Contributions are welcome! Please open an issue or submit a pull request.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

> Made with ❤️ by [Ramlal Kumawat](https://github.com/ramlalkumawat)

