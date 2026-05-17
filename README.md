# EduTrack-Modern-Class-Fee-Manager
**EduTrack** is a sleek, fully client-side web application designed to help students, parents, and educators effortlessly track, manage, and analyze educational expenses and class fees. 


## 📝 Description
**EduTrack** is a sleek, fully client-side web application designed to help students, parents, and educators effortlessly track, manage, and analyze educational expenses and class fees. 

Built with a beautiful, responsive glassmorphism UI, EduTrack requires **no backend or database**. It uses your browser's Local Storage to keep your data private and secure, while offering powerful features like automated billing, visual analytics, calendar tracking, and PDF reporting.

---

## ✨ Key Features

*   📊 **Interactive Dashboard**: Get a quick overview of your monthly and yearly spending, active classes, and recent transactions.
*   📚 **Class Management**: Create and manage classes, assign custom colors, and set monthly fees.
*   🤖 **Automated Billing**: Enable auto-billing to let the system automatically log recurring monthly fees on a specified date.
*   📅 **Payment Calendar**: A visual timeline of your expenditures, letting you click on specific days to view detailed transactions.
*   📈 **Reports & Analytics**: Deep dive into your spending habits with interactive charts (Spending Trends & Class Breakdowns) and advanced filters.
*   💾 **Data Management**: 
    *   **PDF Export**: Download printable reports of your transactions.
    *   **JSON Backup & Restore**: Download your database locally to prevent data loss, and upload it to restore across devices.
    *   **Factory Reset**: Easily wipe your data when starting fresh.
*   🌓 **Dark & Light Mode**: Seamless theme switching that remembers your preference.
*   📱 **Fully Responsive**: A fluid design that works perfectly on desktops, tablets, and mobile devices.

---

## 🛠️ Technologies Used

This project is a single-page application (SPA) built using modern web standards and lightweight libraries via CDN:

*   **HTML5 / CSS3 / JavaScript (ES6+)**: Core structure, styling, and application logic.
*   **Tailwind CSS**: For rapid, utility-first UI styling and responsive design.
*   **Chart.js**: For rendering beautiful, interactive analytics charts.
*   **jsPDF & jsPDF-AutoTable**: For generating and downloading PDF reports locally.
*   **FontAwesome**: For scalable, crisp vector icons.

---


## 🚀 Getting Started

Since EduTrack is completely client-side, there are no dependencies to install, no servers to configure, and no build processes.

### Installation

1. **Clone the repository** (or simply download the ZIP file):
   ```bash
   git clone https://github.com/yourusername/edutrack.git
   ```
2. **Navigate to the folder**:
   ```bash
   cd edutrack
   ```
3. **Open the app**:
   Simply double-click the `index.html` file to open it in your preferred web browser.

*That's it! You're ready to start tracking.*

---

## 📖 How to Use

1. **Create a Class**: Navigate to the "Classes" tab and click "New Class". Enter the subject name, fee, and choose whether you want to enable Auto-Billing.
2. **Record a Payment**: Go to the "Dashboard", select your class from the dropdown, verify the amount and date, and click "Save Transaction".
3. **View the Calendar**: Check the "Calendar" tab to see exactly which days payments were made.
4. **Analyze Spending**: Go to "Analytics", select your date range and specific classes, and click "Apply Filter" to see your visual breakdown.
5. **Backup Your Data**: Head to "Data & Export" periodically to download a JSON backup of your records.

---

## 🔒 Privacy & Data Storage

**Your data belongs to you.** EduTrack does not send any information to external servers. All classes, payments, and settings are stored locally in your browser's `localStorage`. 
*Note: If you clear your browser's cache/storage, your data will be lost. We highly recommend using the built-in **Backup to JSON** feature regularly!*

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! 

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 📜 License

Distributed under the MIT License. See `LICENSE` for more information.

---

## 💬 Acknowledgements

* [Tailwind CSS](https://tailwindcss.com/)
* [Chart.js](https://www.chartjs.org/)
* [jsPDF](https://github.com/parallax/jsPDF)
* [FontAwesome](https://fontawesome.com/)
```
