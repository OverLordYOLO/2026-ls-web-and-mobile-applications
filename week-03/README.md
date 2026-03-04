# Week 03: The Skin (Mobile-First CSS)

## 🎯 Objective
Today, we turn your "ugly" HTML skeleton into a beautiful mobile landing page. You will learn how to use CSS to control colors, fonts, spacing, and layout, focusing on a **Mobile-First** approach.

---

## 🛠 Task 1: Setup & Linking
We need to create a style sheet and tell the HTML file to use it.

1.  Open your GitHub Codespace.
2.  Create a new folder called `week-03`.
3.  Inside `week-03`, create two files:
    - `index.html` (Copy the content from your `week-02/index.html` into this one).
    - `style.css` (This is where our design goes).
4.  **Link them:** Inside the `<head>` of your `index.html`, add this line:
    ```html
    <link rel="stylesheet" href="style.css">
    ```

---

## 🎨 Task 2: Typography & Colors
Let's give "Erasmus Brew" a brand identity.

1.  **Google Fonts:** Go to [Google Fonts](https://fonts.google.com/), pick a nice font (like 'Poppins' or 'Playfair Display'), and follow the instructions to import it into your CSS.
2.  **Define Colors:** Use CSS variables to keep your "Coffee" theme consistent.
    ```css
    :root {
      --primary-coffee: #6F4E37;
      --light-cream: #F5F5DC;
      --dark-text: #2C1E12;
    }
    ```
3.  **Apply Basics:** Set the background color of the `body` and the default font.

---

## 📦 Task 3: The Box Model (Spacing)
Everything in web design is a box. We need to add "breathing room" to our coffee shop.

1.  **Padding:** Add space *inside* your buttons and sections.
2.  **Margin:** Add space *between* your sections (e.g., space between the Hero image and the Menu).
3.  **Centering:** Use `margin: 0 auto;` and `max-width` to ensure your content doesn't stretch too wide on larger screens.



---

## 🍱 Task 4: Layout with Flexbox
Your "Menu" is currently a vertical list. Let's make it look more like a mobile app menu.

1.  Target the `<ul>` in your Menu section.
2.  Use `display: flex;` to align items.
3.  Use `justify-content: space-around;` to spread them out evenly across the phone screen.

---

## 📱 Task 5: Mobile-First Hero Image
Make sure your coffee photo looks good on a small screen.

1.  Target your `img` tag.
2.  Set `width: 100%;` and `height: auto;`.
3.  Add a `border-radius: 15px;` to give it a modern, "app-like" feel.

---

## 🏁 Expected Results
By the end of this seminar, your `week-03` folder should look like this:
```text
/week-03/
  ├── index.html
  └── style.css