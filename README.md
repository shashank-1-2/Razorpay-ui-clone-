# Razorpay-ui-clone-

A fully responsive Razorpay homepage clone built using **HTML** and **Tailwind CSS**. This project replicates the official Razorpay website's UI with clean, modern design and utility-first styling.

## 🚀 Features

- Fully responsive layout (mobile/tablet/desktop)
- TailwindCSS utility classes for rapid styling
- Pixel-perfect Razorpay homepage replica
- Sticky navigation bar with dropdown
- Animated buttons and smooth hover transitions
- Modular section structure for easy scalability

---

## 🛠️ Technologies Used

- **HTML5**
- **Tailwind CSS v3.x**

---

## 📂 Folder Structure

razorpay-clone/
│
├── index.html # Main HTML file
├── style.css # Tailwind compiled CSS (optional if CDN used)
├── tailwind.config.js # Tailwind config file (if using local setup)
├── /assets # Images, logos, icons
│ └── logo.svg
│ └── hero.png
│ └── ...


## 🧑‍💻 Installation 

You can use either the CDN method or install Tailwind locally.

### 📦 Option 2 : Setup Tailwind Locally (Advanced)
# 1. Clone the repo
git clone https://github.com/yourusername/razorpay-clone.git
cd razorpay-clone

# 2. Install Tailwind & dependencies
npm install -D tailwindcss
npx tailwindcss init

# 3. Create your input CSS
echo '@tailwind base;\n@tailwind components;\n@tailwind utilities;' > style.css

# 4. Build Tailwind output
npx tailwindcss -i ./style.css -o ./dist/output.css --watch


### 📦 Option 2: Use Tailwind via CDN (Recommended for beginners)

Just include the Tailwind CDN link in your `<head>`:

```html
<script src="https://cdn.tailwindcss.com"></script>

