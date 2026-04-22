# Week 08: The Transaction Layer (E-Commerce Basics)

## 🎯 Objective
Today, you will transform "Erasmus Brew" into a functional shop. You will set up a digital menu that allows students to pre-order coffee for local pickup.

---

## 🛠 Task 1: Installing the Engine (WooCommerce)
1.  In WordPress, go to **Plugins** -> **Add New** and search for **WooCommerce**.
2.  Install and Activate.
3.  **The Setup Wizard:** - Industry: Food & Drink.
    - Product Types: Physical Products.
    - **Business Details:** Select "Czech Republic" and your local currency (CZK).

> [!TIP]
> WooCommerce will try to install 5 other 'recommended' plugins like Jetpack or MailPoet. Tell it 'No thanks.' We are building a coffee shop, not a spaceship!

---

## ☕ Task 2: Creating your Digital Menu
You need to add at least 3 products to your shop.
1.  **Product 1 (Simple):** Espresso. Set a price (e.g., 55 CZK).
2.  **Product 2 (Variable):** Latte. Add "Attributes" for Milk Type (Cow, Oat, Soy).
3.  **Product 3 (Limited):** Chocolate Brownie. Set the "Inventory" to only 5 units to see the "Low Stock" warning.
4.  **AI Image:** Use your skills from Week 06 to generate a professional product photo for each!

---

## 🛒 Task 3: The "Frictionless" Checkout
We want to make it easy for students to order.
1.  **Payments:** Go to WooCommerce -> Settings -> Payments. Enable **"Cash on Delivery"** (Renamed to "Pay at Counter").
2.  **Shipping:** Go to Settings -> Shipping. Disable everything except **"Local Pickup"**.
3.  **The Menu Page:** Create a new page called "Order Online" and add the **"All Products"** block.

---

## 🧪 Task 4: The "Ghost" Order
1.  Open your site in a new window.
2.  Go to "Order Online," add a Latte (with Oat milk) to your cart.
3.  Go through the checkout process. 
4.  **The Result:** Check your WordPress Dashboard under **WooCommerce -> Orders**. Do you see your order?

---

## 🏁 Expected Results
Your `/week-09/` folder on GitHub should contain:
```text
/week-09/
  └── order-test.txt
```

## 📝 Structure of order-test.txt

Answer these questions:

1. **The Friction Test:** How many clicks does it take from landing on your homepage to completing an order?
2. **Product Logic:** Describe your "Variable" product. What options did you give the user?
3. **Inventory:** What happened to the "Brownie" page after you placed a test order for one?

---

## 🚀 Submission

1. Save your `order-test.txt`.
2. Commit message: `Implement WooCommerce Digital Menu and Checkout`.
3. **Sync Changes** to GitHub.