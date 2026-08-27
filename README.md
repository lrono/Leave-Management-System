# Automated Leave Management System

## 📌 Project Overview
The Automated Leave Management System is a centralized human resources platform designed to replace manual record-keeping with a secure, digital workflow. Engineered to automate employee leave requests, approvals, and cumulative leave tracking, the system ensures data integrity and streamlines administrative operations for enterprise environments. 

## 🛠️ Tech Stack & Architecture
*   **Backend:** PHP (Custom Modular Architecture)
*   **Database:** MySQL (`leave_db`)[cite: 7]
*   **Server:** Apache (Configured with `mod_rewrite` for dynamic routing)[cite: 2]
*   **Frontend:** HTML5, CSS3, JavaScript, Bootstrap (Modals & UI components)[cite: 6]

## 🚀 Core Features & Technical Implementation
*   **Dynamic Routing Engine:** Architected a custom URL rewriting engine using Apache's `mod_rewrite` to securely handle dynamic page requests and shield internal directory structures from direct access[cite: 2, 6].
*   **Modular UI Interface:** Engineered a dynamic modal system (integrated with JavaScript) to handle user inputs, content viewing, and deletion confirmations without requiring full page reloads, ensuring a seamless user experience[cite: 6].
*   **Centralized Configuration:** Implemented robust session management and environment configuration, utilizing object-oriented database connection structures (`DBConnection`) and system settings management[cite: 4].
*   **Device Responsive Delivery:** Integrated server-side mobile device detection to optimize asset delivery and user interface rendering across desktop, iOS, and Android platforms[cite: 4].
*   **Secure Admin Portal:** Developed an isolated administrative dashboard accessible via the `/admin` route for elevated privilege management and system oversight[cite: 5].

