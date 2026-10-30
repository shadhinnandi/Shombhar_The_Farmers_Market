

# 🌾 **Sombhar – The Farmers Market**

*A Digital Marketplace Connecting Farmers, Consumers & Technology*

---

## 📌 **Project Overview**

**Sombhar – The Farmers Market** is a web-based platform built to eliminate middlemen from the agricultural supply chain by connecting **farmers directly with customers and wholesalers**. It ensures fair pricing for farmers while offering fresh produce to buyers.

This system is developed as part of the **Database Management Systems Laboratory (CSE 2215)** course by **Team Void (Group 08)**.

🔗 **Video Demonstration:** [https://youtu.be/lyObKZjh4kI](https://youtu.be/lyObKZjh4kI)

---

## 👥 **Team Members – Team Void**

| Name                       | ID         |
| -------------------------- | ---------- |
| Md. Shakibul Hassan Prince | 0112230048 |
| Mahmudul Mashrafe          | 0112230115 |
| Shadhin Nandi              | 0112230604 |

This project was developed collaboratively by Team Void. The original team members are credited above; this repository is maintained and published by Shadhin Nandi.

---

## 🎯 **Key Objectives**

* Empower farmers with direct access to digital marketplaces.
* Reduce reliance on intermediaries.
* Provide fresh agricultural products to consumers.
* Integrate a secure and efficient DBMS-backed platform.
* Support knowledge sharing through blogs, articles, and communication tools.

---

## ⚙️ **Features**

### ✅ **Core Features**

* 👨‍🌾 Farmers can list and sell agricultural products.
* 🛒 Customers can browse and buy directly from farmers.
* 📩 Purchase request system (quantity, pricing checks).
* 💳 Secure transaction & payment records.
* 👥 Multiple roles: Farmer, Customer, Worker, Admin.
* 📚 Blog & article section for agricultural knowledge.
* 💬 Real-time chat between farmers and buyers.
* 👷 Workers can be hired by farmers.
* 🛠️ Farmers can purchase tools, fertilizers, and machinery.
* 📊 Admin-controlled reporting and printing system.

---

## ⭐ **Unique Selling Points**

| Feature                     | Description                                            |
| --------------------------- | ------------------------------------------------------ |
| 🛍️ Direct Marketplace      | Farmers sell directly to customers/wholesalers.        |
| 📦 Bulk Purchase Support    | Wholesalers and retailers can place large orders.      |
| 🔐 Role-Based Access        | Each user type gets tailored features and permissions. |
| 🗣️ Real-Time Communication | Instant chat between farmers and buyers.               |
| 📖 Knowledge Hub            | Blogs & articles for modern farming practices.         |
| 🧾 Comprehensive Reporting  | Admin can generate and print detailed system reports.  |

---

## 🗃️ **Database Design**

### **Main Tables**

* `users` – Login credentials & roles
* `products` – Product details
* `transactions` – Purchases, sales & payment records
* `articles` – Blogs & farming knowledge base
* `chats` – Real-time messaging between users

📌 Relationships include **one-to-many (farmer → products)** and **many-to-many (customer ↔ products via orders)**.

(Include ER Diagram & Schema Diagram in repo under `/docs` folder)

---

## 🛠️ **Tech Stack**

| Layer           | Technology               |
| --------------- | ------------------------ |
| Frontend        | HTML, CSS, JavaScript    |
| Backend         | PHP                      |
| Database        | MySQL                    |
| Tools           | XAMPP / WAMP, phpMyAdmin |
| Version Control | Git & GitHub             |

---

## 📂 **Folder Structure**

```
Somvaar-FarmersMarket/
│
├── /database/           # .sql files for schema & sample data
├── /src/                # PHP source files and logic
├── /assets/             # Images, CSS, JS files
├── /docs/               # ERD, Schema and Project Report
├── README.md
└── LICENSE
```

---

## 🚀 **How to Run the Project Locally**

1. **Clone the repository:**

   ```bash
   git clone https://github.com/shadhinnandi/Shombhar_The_Farmers_Market.git
   cd Shombhar_The_Farmers_Market
   ```

2. **Start Apache & MySQL via XAMPP/WAMP**

3. **Import the database:**

   * Open phpMyAdmin
   * Create a database (e.g. `farmers_market`)
   * Import the `.sql` file from `/database/`

4. **Place the project folder into:**

   * `htdocs/` (for XAMPP)
   * `www/` (for WAMP)

5. **Run in browser:**

   ```
   http://localhost/somvaar-farmers-market/
   ```

---

## 📉 **Limitations**

* ❌ No Bangla language support
* ❌ No review or rating system
* ❌ No notification system
* ❌ Limited mobile responsiveness
* ❌ Chat interface needs improvement
* ❌ No community discussion section

---

## 🔮 **Future Enhancements**

✔ AI-based product recommendations
✔ Mobile app for Android/iOS
✔ Multi-language support (Bangla, English, etc.)
✔ Notification system for orders & updates
✔ Review and rating system for products and sellers
✔ Advanced analytics/reporting for admins

---

## ✅ **Conclusion**

Somvaar – The Farmers Market is a **complete agricultural ecosystem** that bridges the gap between traditional farming and modern digital commerce. With its farmer-friendly features, real-time communication, knowledge-sharing capabilities, and secure database design, it stands as a promising system for empowering rural communities and transforming the agriculture sector.

---
## 🖼️ **Screenshots**
![1 1](https://github.com/user-attachments/assets/4cb06b0a-e02a-4054-96ae-6f14ec1d2e9c)
![1 3](https://github.com/user-attachments/assets/9cad1572-ce06-4a2e-b7c4-7c65df5ab57d)
![1 4](https://github.com/user-attachments/assets/1276ec60-b85e-4ff0-978f-54fb198ac2a4)
![1 5](https://github.com/user-attachments/assets/c313b9b1-a6![2 9](https://github.com/user-attachments/assets/e73e8236-2af8-4e60-aaee-fa259f3990e4)
![2 8](https://github.com/user-attachments/assets/f5fe14ad-65c8-421e-8a93-bb1da0eb9b0f)
![2 7](https://github.com/user-attachments/assets/06c0f038-2dcf-4248-9a70-19875e60d491)
![2 6](https://github.com/user-attachments/assets/ceeea9e5-c013-44e8-8497-758b08277200)
![2 5](https://github.com/user-attachments/assets/ebde32a3-6c0c-4b02-90d3-6ad1f8d1c73c)
![2 4](https://github.com/user-attachments/assets/ece6fb73-35cb-46d8-a33e-e5734e327d3f)
![2 3](https://github.com/user-attachments/assets/b4ff6b73-904f-44eb-bd8e-f1635e6cc5f5)
![2 2](https://github.com/user-attachments/assets/2d5dfa54-1d57-44b5-a96c-192f530758ec)
![2 1](https://github.com/user-attachments/assets/abb3fdb3-0c1d-4935-89ae-88e432931998)
![1 17](https://github.com/user-attachments/assets/8619117e-4ea0-4fbb-8a3e-e140da802f28)
![1 16](https://github.com/user-attachments/assets/3e757641-e479-4f65-b069-54038c83689a)
![1 14](https://github.com/user-attachments/assets/4d27e2ac-df05-460c-bfde-bd1932ee86c3)
![1 13](https://github.com/user-attachments/assets/f5b68801-f215-4031-9b8c-12232340cbe1)
![1 12](https://github.com/user-attachments/assets/d31912ea-44a6-4a93-9a0f-b1b3031a75b8)
![1 11](https://github.com/user-attachments/assets/d4463af5-b8e4-4653-8da8-cd8a1476bbc3)
![1 10](https://github.com/user-attachments/assets/27346a01-65fe-40a3-b340-e8710e2e5323)
![1 9](https://github.com/user-attachments/assets/f30afb7c-8091-499b-8bb4-3efaebfa9224)
![1 8](https://github.com/user-attachments/assets/59663269-8fe3-4844-a4e0-071ea9fde45e)
![1 7](https://github.com/user-attachments/assets/fe15db7d-d723-460a-83a2-e3f9e2130767)
![1 6](https://github.com/user-attachments/assets/c3dd1919-3428-4d9f-9a9d-1d62dcb82284)
![5 2](https://github.com/user-attachments/assets/89a4c485-d855-48da-ad93-43cea96a35c6)
![5 1](https://github.com/user-attachments/assets/4e01f05b-72a8-4786-bc51-0c236ec0fddf)
![4 5](https://github.com/user-attachments/assets/21134efa-6b2b-4960-a86a-fb4d264aca4c)
![4 4](https://github.com/user-attachments/assets/843bbd7f-c326-4f87-a5b6-5c4df238ae90)
![4 3](https://github.com/user-attachments/assets/772fa8db-8361-4163-9235-ad86e2f7649c)
![4 2](https://github.com/user-attachments/assets/6b9b9cdd-4a0d-4f6c-a642-d5d20081b5f7)
![4 1](https://github.com/user-attachments/assets/75f82be8-3f70-4893-b989-2d8807f6e7c1)
![3 7](https://github.com/user-attachments/assets/9abe89b1-2e45-4761-b454-c1decebb1238)
![3 5](https://github.com/user-attachments/assets/6d9da74a-d3ef-4570-891e-5679154c97b9)
![3 4](https://github.com/user-attachments/assets/4debf7ff-ea73-4934-8498-a8b1cab53a39)
![3 3](https://github.com/user-attachments/assets/c7b808ba-d421-4a18-8707-146fb540f126)
![3 2](https://github.com/user-attachments/assets/819b5d4a-92c4-417d-827f-f917d42517b0)
![3 1](https://github.com/user-attachments/assets/a488242e-7b3d-48c3-bda8-35b7db14977f)
![2 11](https://github.com/user-attachments/assets/999f8956-6944-4894-964e-8f2555811e19)
![2 10](https://github.com/user-attachments/assets/ec31ac04-0bfc-4de1-8df4-03365801d98a)
---
