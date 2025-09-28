
![alt text](<Screenshot (203).png>)

![alt text](<Screenshot (204).png>)

# alx-project-0x03-setup

This project is part of the ALX Next.js setup tasks.
It demonstrates how to handle unknown routes in a **file-based routing system** by creating a **custom 404 error page**.

---

## 📌 Objective

When a user navigates to a route that doesn’t exist in the `pages/` directory, Next.js will resolve to a **404 page not found**.
By default, Next.js provides a simple 404 page, but here we override it with a custom styled error page.

---

## 🛠️ Features

* Custom 404 error page (`pages/404.tsx`)
* Tailwind CSS styling
* Funny error message with emoji support 👽
* Button to navigate back to the home page 🏠
* Integrated **react-icons** for a clean design

---

## 📂 Project Structure

```
alx-project-0x03-setup/
│── pages/
│   ├── index.tsx
│   ├── 404.tsx   <-- Custom error page
│── package.json
│── tailwind.config.js
│── README.md
```

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/FaisalMohammedElorm/alx-project-0x03-setup.git
cd alx-project-0x03
```

### 2. Install dependencies

```bash
npm install
```

### 3. Run the development server

```bash
npm run dev
```

### 4. Open the app

Visit:

```
http://localhost:3000
```

Try navigating to a random path, e.g.

```
http://localhost:3000/unknown-pathname
```

---

## 📸 Preview

* Large heading: **Oops! 😱**
* Description of missing page
* Funny alien abduction message 👽
* "Go Back Home" button with a home icon

---

## 🧑‍💻 Technologies Used

* [Next.js](https://nextjs.org/)
* [Tailwind CSS](https://tailwindcss.com/)
* [React Icons](https://react-icons.github.io/react-icons/)

---

## ✅ Task Checklist

* [x] Create `pages/404.tsx`
* [x] Add custom error message
* [x] Style with Tailwind CSS
* [x] Add navigation button with icon
* [x] Test on unknown routes

---

## 📜 License

This project is for learning purposes under the ALX program.
Feel free to use and customize it.

