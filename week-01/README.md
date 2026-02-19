# Week 01: Foundations (UX & HTML)

## 🎯 Objective
To understand how a digital project begins. You will move from a "Client Brief" to a visual wireframe, and finally to a basic technical structure using HTML.

---

## 🛠 Task 1: The Design (Figma)
**Scenario:** A local coffee shop, "Erasmus Brew," needs a simple mobile landing page so students can see their menu and location.

1. **Log in to [Figma](https://www.figma.com).**
2. **Create a new Design File.**
3. **Add a Frame:** Press `F` and select "iPhone 14 & 15 Pro" from the right sidebar.
4. **Wireframe the following:**
   - A **Header** with the shop name.
   - A **Hero Image** placeholder (use a grey rectangle).
   - An **"About Us"** section with some text.
   - A **"Menu"** list (Coffee, Tea, Cake).
   - A **"Find Us"** footer with an address.

> **Tip:** Keep it simple! Use only grey boxes, circles, and basic text. We are focusing on *layout*, not pretty colors yet.

---

## 💻 Task 2: The Structure (HTML)
Now, translate your Figma design into code using **HTML semantics**.

1. **Open [vscode.dev](https://vscode.dev).**
2. **Create a new file** named `index.html`.
3. **Write the boilerplate:** Type `!` and hit `Tab` (or paste the standard HTML5 structure).
4. **Code your structure:**
   - Use `<header>` for the title.
   - Use `<main>` for the content.
   - Use `<ul>` and `<li>` for the menu list.
   - Use `<footer>` for the address.

**Example Snippet:**
```html
<header>
    <h1>Erasmus Brew</h1>
</header>
<main>
    <section>
        <h2>About Us</h2>
        <p>The best coffee for Erasmus students in the city!</p>
    </section>
</main>
```

---

## 🏁 Expected Results
By the end of the seminar, your project should look like this (conceptually):

### 1. The Wireframe (Figma)
Your Figma canvas should have a clear vertical layout optimized for a mobile screen. 


### 2. The Code (HTML)
Your `index.html` should look structured in the editor. Even though it won't have colors or images yet, the "skeleton" should be visible in the browser preview.

### 3. The File Structure
Your GitHub folder for this week should look like this:
```text
/week-01/
  ├── index.html
  └── design-link.txt  (Optional: a file containing your Figma URL)