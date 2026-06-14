# Points and Reward DBMS

A comprehensive **Points and Reward Database Management System (DBMS)** developed for **The Foodie**, a fast-food brand under the Grand Wooly conglomerate. This system is designed to enhance customer loyalty by providing an engaging platform for managing point-based transactions, membership tiers, and reward redemptions through both mobile and web platforms.

---

## 📌 Scope of Work
Our team has been tasked to design and implement a **Reward and Point Management System** for **The Foodie**. The system supports seamless customer interactions by handling point accumulation, tier progression, and reward redemption, ultimately boosting long-term engagement and loyalty.

---

### ⚙️ Functional Scope

The system offers 10 key features:

1. **Customer-Initiated Transactions**  
   - Customers can earn points through purchases and redeem available rewards using accumulated points.

2. **Customer Payment Management**  
   - Multiple payment options supported: e-wallets, credit/debit cards, and online banking.  
   - Customers can review all past payments for transparency and personal tracking.

3. **Point Management System**  
   - Points are categorized as active or expired.  
   - Earned and expired points are updated automatically following defined rules.

4. **Membership Assignment**  
   - Tiered membership (Bronze, Silver, Gold, etc.) is assigned based on customer engagement and accumulated points.

5. **Tier-Based Benefits**  
   - Higher tiers unlock greater benefits (e.g., exclusive promotions, vouchers, free gifts).

6. **Transaction Information Access**  
   - Customers can view transaction details (Earn, Redeem) and statuses (Completed, Pending, Failed) with full history for transparency.

7. **Reward Redemption Using Points**  
   - Redeemable rewards are validated against stock availability and customer point balance.

8. **Real-Time Redemption Tracking**  
   - Customers can monitor the status of their redemptions (Pending, Completed, Cancelled).

9. **Reward Catalog Browsing**  
   - Customers can explore all available rewards, including descriptions and required points.

10. **Reward Restocking Management**  
    - Admins can monitor and manage reward stock levels to prevent over-redemption.

---

### 📋Requirement Analysis & Business Rules

#### ✅ Transaction Rule  
- **Rule**: Points are only processed for completed transactions.  
- **Purpose**: Ensures legitimacy and prevents exploitation or system abuse.

#### 🎁 Reward Rule  
- **Rule**: Out-of-stock rewards are marked as "Inactive".  
- **Purpose**: Prevents redemption of unavailable rewards and improves customer experience.

#### 🧮 Point Rule  
- **Rule**: Customers earn **1 point per RM1 spent**; points expire after a certain period.  
- **Purpose**: Drives consistent engagement and timely redemptions.

#### 🔄 Redemption Rule  
- **Rule**: Redemption requests must have a status (Pending, Completed, Cancelled).  
- **Purpose**: Supports tracking and refund mechanisms for failed redemptions.

#### 🏅 Membership Rule  
- **Rule**: 1000 points required for each tier upgrade (except Diamond, which requires 5000).  
- **Purpose**: Encourages customer loyalty and incentivizes higher engagement levels.

---

## 🛠️ Skills & Technologies Utilized

This project showcases a broad range of database development and management skills, including:

- **🔢 Oracle SQL**  
- **🧠 PL/SQL for Automation**  
- **📐 ER & EER Modeling**  
- **📏 Database Normalization & Integrity Constraints**  
- **📋 Business Rule Enforcement**
- **⏱️ Triggers, Stored Procedures & Functions**  
- **📈 Real-Time Transaction Logging & Auditing **  

---


## 👨‍💻 Authors

Developed by:  
- **Owi Wilson**  
- **Tan Cheng Lock**
- **Ng Wei Jie**
- **Yee Hao Zhe**

This project is part of the Database Technology coursework for academic purpose.

---

