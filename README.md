# ✅ TodoList Extension – Chrome Extension (React + Tailwind + LocalStorage)

**TodoList Extension** is a sleek and responsive browser extension that helps you manage your daily tasks efficiently. Built with **React** and **Tailwind CSS**, it stores your tasks locally using `localStorage`, so they persist across sessions without needing any server or login.

---

## ✨ Features

- 📝 Add and manage to-dos directly in the browser
- ✅ Mark tasks as completed
- ❌ Delete individual or all tasks
- 💾 Data is stored using `localStorage` (offline support)
- ⚡ Built with React + Tailwind CSS
- 📎 Extension UI optimized for compact view

---

## 📸 Screenshot

Here’s a preview of the extension in action:

![TodoList Extension Screenshot](https://github.com/hellman53/Todo-extension/blob/e9f3bfa44826f56fe1708b332cfa3fae8867bbf8/public/snapshot.png)

---

## 🚀 Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/todolist-extension.git
cd todolist-extension

```
2. Install Node Modules
Make sure you have Node.js installed.

Then install dependencies:
```bash
npm install
# or
yarn install
# or
pnpm install
```

💻 Run the Project in Development
To run the React app locally:
```bash
npm run dev
# or
yarn dev
# or
pnpm dev
```
This will start the app on http://localhost:5173 by default (if you're using Vite).

📦 Build for Production
To generate a production build (for deployment or Chrome extension packaging):
```bash
npm run build
# or
yarn build
# or
pnpm build
```
This will generate a dist/ folder containing the build output.

🧩 Load as Chrome/Brave Extension
To load the extension in Chrome or Brave, follow these steps:
1. Go to chrome://extensions/ (or brave://extensions/ for Brave).
2. Enable Developer Mode.
3. Click "Load unpacked".
4. Select the dist/ folder.
5. The extension should now be loaded and visible in the browser.
6. You can also load the extension directly from the `manifest.json` file by clicking the "Load unpacked" button and selecting the `manifest.json` file.
7. To update the extension, simply reload the extension by clicking the reload button in the extensions pag
8. To remove the extension, click the "Remove" button in the extensions page.
9. To load the extension in a different browser, follow the same steps as above.

📁 Folder Structure
The project follows a standard structure:

``` bash
src/
  ├── components/
  │   └── TodoForm.jsx
  │   └── TodoItem.jsx
  ├── App.jsx
  ├── main.jsx
  └── index.css
```

🧠 Tech Stack
1. React
2. Tailwind CSS
3. Vite
4. HTML5 LocalStorage
5. Chrome Extension APIs
