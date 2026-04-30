# Week 10: Retention, Loyalty & Maintenance

## 🎯 Objective
A business that doesn't grow, dies. Today you will implement a "Loyalty Program" and set up the automated systems that keep your Erasmus Brew customers coming back for more.

---

## 🎟️ Task 1: The "First Brew" Discount (Coupons)
We need to incentivize that first purchase.
1.  In your WordPress Dashboard, go to **Marketing** -> **Coupons**.
2.  Create a coupon code: `FRESHMAN26`.
3.  **Discount Type:** "Percentage Discount" (15%).
4.  **Usage Restriction:** Set it so it only applies to orders over 100 CZK.
5.  **Expiry:** Set it to expire in 30 days.

---

## 📧 Task 2: Newsletter Integration
You have a list of emails from Week 07. Now, let's give them a professional home.
1.  **Option A:** Install the **MailPoet** plugin (easiest for WordPress).
2.  **The Welcome Email:** Create an automated "Welcome" email that triggers as soon as someone joins your "Brew Crew" list.
3.  **Design:** Use your **AI Brand Persona** (Week 06) to ensure the email looks like your website. Include your `FRESHMAN26` coupon code in the text!

> [!NOTE]
> Personalize the coupon, you does not have to follow these steps literally.

---

## 🛡️ Task 3: The "Disaster Plan" (Backups)
A manager's biggest fear is the "White Screen of Death."
1. Install the **UpdraftPlus** plugin.
2. Perform a **Manual Backup** of your entire site (Database + Files).
3. **Download** the backup to your local computer or connect it to your Google Drive.

> [!TIP]
>*Now, if you break your site during the final weeks, you can teleport back in time!*

---

## 🧪 Task 4: Personalization Check
1. Go to your "Loyalty Club" form from Week 07.
2. Add a new field: **"What is your favorite coffee?"** (Radio buttons: Espresso, Latte, Cappuccino).
3. **The Logic:** In your `automation-notes.txt`, explain how you would use this specific data to send a better email to your users.

---

## 🏁 Expected Results
Your `/week-10/` folder on GitHub should contain:
```text
/week-10/
  ├── backup-success.png (Screenshot of your successful UpdraftPlus backup)
  └── automation-notes.txt
```

---

## 📝 Structure of automation-notes.txt

1. **The Coupon:** What is your coupon code and what is the "business logic" behind it?
2. **The Automation:** Describe the "Welcome Email" you designed. What is the subject line?
3. **The Data Strategy:** How will you use the "Favorite Coffee" info to sell more coffee? (e.g., *"If they like Lattes, I will email them when we have new Oat Milk."*)

---

## 🚀 Submission

1. Save your files.
2. Commit message: `Implement Loyalty Loop and Site Backups`.
3. **Sync Changes** to GitHub.