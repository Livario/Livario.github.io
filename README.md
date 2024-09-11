# Livario.github.io
Creating a free website with the name "Livario" can be done using various platforms that provide free hosting services like GitHub Pages, Netlify, or Google Sites. Here’s a step-by-step guide using **GitHub Pages** (one of the easiest and cost-free methods):

### 1. **Create a GitHub Account (if you don’t have one)**
- Visit [github.com](https://github.com) and sign up.

### 2. **Create a New Repository**
- After logging in, click on the **+** icon at the top right and select **New repository**.
- Name your repository `livario.github.io`. (The name of the repo should be `your_username.github.io` for GitHub Pages to automatically host it as a website).
- Check the box to **Initialize the repository with a README**.

### 3. **Set Up the Website Files**
Next, we’ll create a basic static HTML website for "Livario". 

#### Structure:
```plaintext
.
├── index.html
├── styles.css
└── script.js
```

#### **index.html**
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Livario</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Welcome to Livario</h1>
    </header>

    <main>
        <section>
            <h2>Your Gateway to Ideas and Inspiration</h2>
            <p>Livario is where creativity meets reality. Explore, innovate, and grow with us.</p>
        </section>
    </main>

    <footer>
        <p>© 2024 Livario</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>
```

#### **styles.css**
```css
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
}

header {
    background-color: #333;
    color: white;
    padding: 1em;
    text-align: center;
}

main {
    padding: 2em;
    text-align: center;
}

footer {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 1em;
    position: fixed;
    width: 100%;
    bottom: 0;
}
```

#### **script.js**
```javascript
document.addEventListener('DOMContentLoaded', () => {
    console.log("Livario site loaded successfully.");
});
```

### 4. **Push Code to GitHub**
- If you prefer, you can manually upload these files through the GitHub web interface.
- Alternatively, you can use Git to push your changes:
    ```bash
    git clone https://github.com/your_username/livario.github.io
    cd livario.github.io
    # Add your files here (index.html, styles.css, script.js)
    git add .
    git commit -m "Initial commit for Livario website"
    git push origin main
    ```

### 5. **View Your Website**
After pushing the code, your site will be live at `https://your_username.github.io`. Since we named the repository `livario.github.io`, the website will automatically be available at:
```
https://livario.github.io
```

That’s it! You've successfully created a free website named **Livario** using GitHub Pages.
