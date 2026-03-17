# Task 2: Host a Personal Site with GitHub Pages

GitHub Pages turns a repository into a live website — for free. In this task, you will create a simple personal site that anyone can visit.

---

## Steps

1. On GitHub, click the **+** button (top right) and select **New repository**.
2. Name the repository **`your-username.github.io`** (replace `your-username` with your actual GitHub username, e.g., `janedoe.github.io`).
3. Make it **Public**.
4. Check **"Add a README file"**.
5. Click **Create repository**.
6. In your new repository, click **Add file** > **Create new file**.
7. In the "Name your file" field, type `index.html`.
8. Copy the starter HTML below and paste it into the editor. Replace the placeholder text in `[brackets]` with your own information:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Personal Site</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            max-width: 700px;
            margin: 50px auto;
            padding: 0 20px;
            line-height: 1.6;
            color: #333;
        }
        h1 {
            border-bottom: 2px solid #0366d6;
            padding-bottom: 10px;
        }
        a {
            color: #0366d6;
        }
        .section {
            margin-bottom: 30px;
        }
    </style>
</head>
<body>
    <h1>Welcome! I'm [Your Name]</h1>

    <div class="section">
        <h2>About Me</h2>
        <p>I'm a student currently learning [your field of study].
           I'm interested in [your interests].</p>
    </div>

    <div class="section">
        <h2>What I'm Learning</h2>
        <ul>
            <li>Git and GitHub</li>

