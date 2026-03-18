# Week 05: Data Collection, GDPR & Events

## 🎯 Objective
Today, you will transform your "Erasmus Brew" site into a data-driven business. You will set up a professional tracking stack that is 100% GDPR compliant.

---

## 🛠 Task 1: The "Power Strip" (GTM Setup)
1.  Go to [Google Tag Manager](https://tagmanager.google.com/).
2.  Create a "Web" container for your site.
3.  **In WordPress:** Install the plugin **GTM4WP**.
4.  Paste your **GTM-XXXXXX** ID into the plugin and set it to **"On"**.

---

## 🛡️ Task 2: GDPR Compliance (Cookie-Script)
1.  Go to [Cookie-Script.com](https://cookie-script.com/) and create a free account.
2.  Add your Pantheon URL.
3.  In the "Integration" tab, find the **GTM code** or use their WordPress plugin to link it.
4.  **Goal:** Your website must show a cookie banner before any tracking starts.

---

## 📈 Task 3: GA4 Installation & Conversion
1.  Go to [Google Analytics](https://analytics.google.com/) and create a **Property**.
2.  Copy your **Measurement ID** (G-XXXXXXXX).
3.  **In GTM:** - Create a new **Tag** -> **Google Tag**.
    - Paste your Measurement ID.
    - Set Trigger to **"All Pages"**.
4.  **Define a Conversion:**
    - Create a second Tag (GA4 Event).
    - Event Name: `view_menu_page`.
    - Trigger: "Page View" where Page URL contains `/menu`.

---

## 🔥 Task 4: Visual Analytics (Microsoft Clarity)
1.  Go to [Microsoft Clarity](https://clarity.microsoft.com/).
2.  Create a project and "Install with GTM" (it’s a 1-click connection).
3.  **Test:** Open your site, click around, and see if your session appears in the Clarity "Live" dashboard.

---

## 👁️ Task 5: The Debugger (GTM Preview)
1.  In GTM, click the blue **"Preview"** button.
2.  Enter your website URL.
3.  **The Challenge:** Click your "Menu" link. Does the GTM Debugger show that your `view_menu_page` tag fired? If yes, you've succeeded!

---

## 🏁 Expected Results
Your `/week-05/` folder on GitHub should contain:
```text
/week-05/
  └── analytics-report.txt
```

**The `analytics-report.txt` file must contain:**

1. Your GTM ID.
2. Your GA4 Measurement ID.
3. A description of the one conversion you set up (e.g., "I am tracking clicks on the Contact button").

### 📝 Submission

1. Save your `analytics-report.txt`.
2. Commit message: `Implement GTM, GA4, and GDPR Consent`.
3. Sync Changes to GitHub.