
# 📄 Host a Static Website with GitHub Pages

## 🎯 Objective
Deploy a static HTML website using GitHub Pages for free hosting.

---

## 🛠️ Tools Used
- GitHub
- GitHub Pages

---

## 📦 Deliverables
- ✅ GitHub Repository with the source code  
- ✅ Live Website Link (via GitHub Pages)

---

## ✅ Step-by-Step Workflow

### 1️⃣ Create a Simple HTML File
Create a file named `index.html` with basic content:

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>My GitHub Page</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <h1>Welcome to My GitHub Page</h1>
  <p>This is a simple static website hosted using GitHub Pages.</p>
</body>
</html>
```

### 2️⃣ (Optional) Add CSS Styling
Create a `style.css` file:

```css
body {
  font-family: Arial, sans-serif;
  background-color: #f2f2f2;
  text-align: center;
  padding-top: 50px;
}

h1 {
  color: #4CAF50;
}
```

### 3️⃣ Create a GitHub Repository
- Go to [GitHub](https://github.com)
- Click **New Repository**
- Name it something like `github-pages-demo`
- Initialize it **without** a README (you’ll push from local)

### 4️⃣ Push Code to GitHub
Open your terminal:

```bash
git init
git remote add origin https://github.com/YOUR_USERNAME/github-pages-demo.git
git add .
git commit -m "Initial commit with index.html"
git branch -M main
git push -u origin main
```

### 5️⃣ Enable GitHub Pages
- Go to your repo → **Settings** → **Pages**
- Under **Source**, choose `main` branch and `/ (root)` folder
- Click **Save**

> GitHub will generate a public URL like:  
> `https://your-username.github.io/github-pages-demo/`

---

## 🌐 Example Output
### ✅ GitHub Repo  
[🔗 GitHub Repository Link](https://github.com/YOUR_USERNAME/github-pages-demo)

### ✅ Live Website  
[🌍 Live GitHub Pages Site](https://your-username.github.io/github-pages-demo/)

---

## 📌 Outcome
By completing this task, you now know how to:
- Host static websites for free using GitHub Pages
- Deploy HTML/CSS projects quickly and easily
- Share a live website link with others

---

## 📁 Folder Structure
```
github-pages-demo/
├── index.html
└── style.css
```
