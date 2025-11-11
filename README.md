🧮 Counter App

A simple and interactive **Counter App** built using **React.js**.
It allows users to increment, decrement, and reset a counter with a clean and responsive UI.

---

## 🚀 Features

* ➕ **Increment** the counter
* ➖ **Decrement** the counter
* 🔁 **Reset** the counter to zero
* 💻 **Responsive design** — works on all devices
* ⚡ **Fast and lightweight** using React functional components and hooks

---

## 🛠️ Tech Stack

* **React.js**
* **HTML5**
* **CSS3**
* **JavaScript (ES6+)**
* **Vite** (optional if you used it for setup)

---

## 📂 Project Setup

### 1️⃣ Clone the repository

```bash
git clone https://github.com/Yashika-code/Counter.git
```

### 2️⃣ Navigate to the project folder

```bash
cd counter
```

### 3️⃣ Install dependencies

```bash
npm install
```

### 4️⃣ Run the app

```bash
npm run dev
```

Then open your browser and go to:

```
http://localhost:5173
```

---

## 📸 Screenshot

![Counter App Screenshot](https://github.com/Yashika-code/Counter/blob/main/counter/src/assets/Counter.png?raw=true)

---

## 🧩 Example Code

```jsx
import { useState } from 'react';
import './App.css';

function App() {
  const [count, setCount] = useState(0);

  return (
    <div className="App">
      <h1>React Counter App</h1>
      <h2>{count}</h2>
      <div className="buttons">
        <button onClick={() => setCount(count + 1)}>Increment</button>
        <button onClick={() => setCount(count - 1)}>Decrement</button>
        <button onClick={() => setCount(0)}>Reset</button>
      </div>
    </div>
  );
}

export default App;
```

---

## 💡 Future Improvements

* Add dark/light theme toggle 🌗
* Save counter value in **localStorage**
* Add animations or transitions
* Include sound or haptic feedback

---

## 👩‍💻 Author

**Yashika**
🔗 [GitHub Profile](https://github.com/Yashika-code)
