# Week 03: The Skin (Mobile-First CSS)

## 🎯 Objective
Today, we turn your HTML skeleton into a branded mobile landing page. You will learn how to use CSS to control colors, fonts, spacing, and layout using a **Mobile-First** approach.

---

## 🛠 Task 1: Setup & External Styling
We don't write CSS inside HTML files because it gets messy. We use an **External Stylesheet**.

1.  Open your GitHub Codespace and enter your `week-03` folder.
2.  Create a file named `styles.css`.
3.  **Link them:** In the `<head>` of your `index.html`, add this line to connect your visuals to your skeleton :
    ```html
    <link rel="stylesheet" href="styles.css">
    ```

---

## 🎨 Task 2: Brand Identity & Variables
Using a value multiple times? Use a variable!  This makes implementing "Dark Mode" later as easy as changing one line of code.

1.  **Set your variables** at the top of `styles.css`:
    ```css
    :root {
      --primary-color: #3b1f0a;   /* Coffee Brown */
      --bg-color: #f5f0e8;        /* Cream Background */
    }
    ```
2.  **Apply Basics:** Set your `body` font and background. Use `display: flex;` and `flex-direction: column;` to ensure your page sections stack correctly.

---

## 📱 Task 3: Mobile-First Rules
Since we are building for phones, we must follow these essential rules:

* **Width is 100%:** Never give an image a fixed width (like 500px). Use `width: 100%;` so it doesn't cut off on small screens.
* **No Horizontal Scroll:** If a user has to scroll left-to-right, the site is "broken".
* **Thumb-Zone:** Ensure buttons/links are at least 44px tall for easy tapping.

---

## 📦 Task 4: The Box Model & Centering
Everything on the web is a box! These boxes have **Content, Padding, Border, and Margin**.

1.  **Centering content:** To make your app look good on larger screens, center your containers:
    ```css
    body > * {
        max-width: 600px;
        margin-left: auto;
        margin-right: auto;
    }
    ```
2.  **Add Padding:** Add spacing to your `<header>`, `<main>`, and `<footer>` so text doesn't touch the very edge of the screen.
3.  **Debug Tip:** If you can't see your boxes, add `border: 1px solid red !important;` to all elements.


---

## 🍱 Task 5: Layout & Lists
1.  **Flexbox:** Use Flexbox to align items on the main or cross axis .
2.  **Custom Lists:** Make your "Menu" stand out by changing the bullet point style:
    ```css
    ul {
        list-style-type: "► ";
        padding-left: 20px;
    }
    ```

---

## 🏁 Expected Results
Your `week-03` folder must contain:
```text
/week-03/
  ├── index.html
  └── styles.css
  └── coffee.jpg (or some other image)