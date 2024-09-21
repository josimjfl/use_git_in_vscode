Here's the complete guide to hosting a webpage using GitHub Pages by JFLitLab:

# How to Deploy a Webpage on GitHub Pages

Follow these steps to take your code from a GitHub repository and display it as a live webpage using GitHub Pages.

## 1. Create a GitHub Repository
- Go to [GitHub](https://github.com) and log in.
- Click the **+** in the top-right corner and select **New repository**.
- Name your repository (e.g., `my-webpage`) and set it to **Public**.
- Optionally, add a **README** file.
- Click **Create repository**.

## 2. Add Your Webpage Code to the Repository
If you haven’t added your code yet, you can either:
- **Upload files manually** through the GitHub interface.
- **Push code via Git** using these steps:

```bash
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/your-username/my-webpage.git
git push -u origin main
```

## 3. Create an `index.html` File
Ensure that your repository contains an `index.html` file, as GitHub Pages uses it as the entry point for your website. Here's an example:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Webpage</title>
</head>
<body>
    <h1>Welcome to My Webpage</h1>
    <p>This is my first GitHub Pages deployment!</p>
</body>
</html>
```

## 4. Enable GitHub Pages
- Go to the **Settings** tab of your repository.
- Scroll down to the **Pages** section (on the left sidebar under "Code and automation").
- Under **Source**, select the `main` branch (or `gh-pages` branch if you are using it).
- Choose the folder for the root, typically `/root` if your `index.html` is in the root of the repository.
- Click **Save**.

## 5. Access Your Website
Once GitHub Pages is enabled, GitHub will provide a URL for your website. The URL generally follows this format:

```text
https://your-username.github.io/repository-name/
```

Example: `https://josimuddin.github.io/my-webpage/`

*Note:* It may take a few minutes for the website to go live.

## 6. Update Your Webpage
Whenever you make changes to your code, you can push the updates to GitHub, and your site will automatically update. Use the following commands to commit and push changes:

```bash
git add .
git commit -m "Updated webpage"
git push origin main
```

---

Your webpage is now live on GitHub Pages!
```

This Markdown guide will help you set up a live webpage using GitHub Pages. Let me know if you need further assistance!
