# 🔄 React Class Component with Lifecycle Methods  

A **React application** built using a **class-based component** to demonstrate the usage of lifecycle methods such as `componentDidMount` and `componentDidUpdate`.  
This app fetches user data from an external API and allows searching, filtering, and refreshing of data dynamically.  

---

## ✨ Features  
- Uses **class-based component** with lifecycle methods  
- Fetches user data from [JSONPlaceholder API](https://jsonplaceholder.typicode.com/users)  
- `componentDidMount` → Fetches data when the component first loads  
- `componentDidUpdate` → Updates displayed data when search query changes  
- Displays user data in a **table format** (Name, Email, City)  
- **Search functionality** for filtering results  
- **Refresh button** to re-fetch data from API  
- **Error handling** for failed API requests  
- **Loading state** with user feedback  

---

## 📦 Installation & Usage  

```bash
# 1️⃣ Create a new Vite + React project
npm create vite@latest lifecycle-demo -- --template react

# 2️⃣ Navigate into the project folder
cd lifecycle-demo

# 3️⃣ Install dependencies
npm install

# 4️⃣ Start the development server
npm run dev

lifecycle-demo/
├── src/
│   ├── App.jsx        # Class-based component with lifecycle methods
│   ├── App.css        # Styling for the app
│   ├── main.jsx       # Entry point for React
│   └── assets/        # (optional) static assets if needed
├── index.html
├── package.json
└── vite.config.js

