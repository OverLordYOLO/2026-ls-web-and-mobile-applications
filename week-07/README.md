# Week 07: Lead Generation & Performance Audit

## 🎯 Objective
Today, you stop being just a "designer" and start being a **Web Manager**. Your goal is to turn your Erasmus Brew site into a lead generation machine by creating a "Value Exchange" and ensuring your site runs at professional speeds.

---

## 📋 Task 1: The "Value Exchange" (Lead Magnet)
People don't give away their data for free. You must offer a "Lead Magnet."
1.  **Install WPForms:** Search for the "WPForms" plugin in WordPress and activate it.
2.  **Create your Form:** Create a "Loyalty Club" or "Student Guide" form.
3.  **Required Fields:**
    - **Name**
    - **Email Address**
    - **University Dropdown** (e.g., Charles University, CTU, VSE)
4.  **⚖️ GDPR Check:** You **must** add a "Checkbox" field at the bottom that says: *"I agree to the Privacy Policy and to receive coffee-related updates."* This makes your collection legal.

---

## 🤖 Task 2: Automation & "The Thank You"
A professional site talks back to its users instantly.
1.  **Confirmations:** Inside WPForms settings, change the "Confirmation Message" to something on-brand.
    - *Example:* "Welcome to the Brew Crew! Your 2-for-1 coffee voucher is being roasted and will arrive in your inbox shortly."
2.  **Notifications:** Ensure the "Admin Email" is set to your email so you get a notification every time a student signs up.

> This task is possible only if you have your own domain

---

## ⚡ Task 3: The Performance Audit (Lighthouse)
High-res AI images look great but can make your site too slow for mobile users.
1.  Open your website in a **Chrome/Edge Incognito window**.
2.  Right-click -> **Inspect** -> **Lighthouse** tab.
3.  Select **"Mobile"** and click **"Analyze page load"**.
4.  **Screenshot:** Save a screenshot of your score gauges (Performance, Accessibility, SEO). This will be your `lighthouse-report.png`.

> You would normally run Lighthouse in incognito, but because we are using Pantheon hosting, when generating the report, do not open Incognito

---

## 🖼️ Task 4: Image Optimization (WebP)
If your Performance score was low (Red or Orange), it’s likely your images.

What you would do on your website (you cannot do this when using Pantheon hosting):
1.  Install a plugin like **Ewwwww Image Optimizer**.
2.  Convert your large JPG/PNG images into **WebP** format (a modern format that is 30% smaller but looks the same).
3.  Re-run the Lighthouse audit. Your score should improve significantly.

When using pantheon hosting do this instead:
1. Download the images
2. Convert them to webp format and compress them using an online service (search for it using a search engine)
3. Upload it to your website, and delete the old large images (if this was your real website, you might want to keep the HD images on your drive)

---

## 🏁 Expected Results
Your `/week-07/` folder on GitHub should contain:
```text
/week-07/
  ├── lighthouse-report.png
  └── conversion-strategy.txt
```

## 📝 Structure of conversion-strategy.txt

Answer the following:

1. **The Value Exchange:** What did you offer the user in exchange for their email? (e.g., a PDF guide, a coupon, or a birthday treat).
2. **Data Minimization:** Why did you choose the specific fields in your form? How are they useful for the business?
3. **Audit Results:** What was your initial Performance score? What was the "biggest offender" (slowest element) identified by Lighthouse?

## 🚀 Submission

1. Save your files in your repository.
2. Commit message: `Implement Conversion Funnel and Performance Audit`.
3. Sync Changes to GitHub.
