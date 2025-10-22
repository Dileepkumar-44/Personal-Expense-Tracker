# Personal Expense Tracker
Welcome to my Personal Expense Tracker, a sleek and robust web application designed to help you manage your finances effortlessly! Built with modern web technologies and optimized for performance and accessibility, this project showcases my skills as a software developer.
# Overview
This app allows users to track daily expenses, set budgets, analyze spending patterns, and switch between light/dark themes. It’s a fully responsive, offline-capable tool, with data stored locally in the browser, making it perfect for personal use. I developed this project to demonstrate my ability to build practical, user-friendly applications with a strong focus on performance optimization, web accessibility, and clean, maintainable code.
# Features
**Add & Edit Expenses:** Log expenses with amount, description, category, date, and currency.

**Delete & Clear:** Remove individual or all expenses with a custom confirmation modal for enhanced user experience.

**Filter & Search:** Easily filter expenses by category or search through descriptions for quick retrieval.

**Budget Management:** Set and monitor your monthly budget with real-time status updates, indicating remaining funds or overspending.

**Dynamic Analytics:** View insightful spending analytics including top categories, daily averages, and total spending for various periods (Last 7 Days, Last 30 Days, All Time) visualized with an interactive pie chart.

**Theme Toggle:** Seamlessly switch between light and dark modes for comfortable viewing in any environment.

**Multi-Currency Support:** Track expenses in INR (₹), USD ($), and EUR (€).
**Responsive Design:** Optimized for optimal viewing and interaction across all devices, from desktop to tablet and mobile.

**Motivational Quotes**: A dynamic motivational quote is displayed on larger screens to inspire financial discipline.
#Technologies Used
This project highlights a range of concepts and tools I’ve mastered, with a strong emphasis on modern web development practices:

✨ **Project Highlights — Modern Web Development Practices**

► **HTML5:** Structured the application using semantic HTML5 tags to enhance accessibility and SEO.

► **CSS3:** Utilized custom CSS variables for theme management, applied gradients for visual appeal, implemented media queries for responsive design, and added subtle animations for a polished interface.

► **JavaScript (ES6+):** Developed the core application logic, ensured efficient event handling, and managed data flow robustly.

► **Chart.js:** Integrated dynamic and responsive pie chart visualizations for spending data with optimized performance.

► **Local Storage API:** Implemented client-side data persistence to securely store expenses, budgets, theme preferences, and currency settings offline.

► **DOM Manipulation:** Dynamically updated the user interface in real-time based on user interactions and data changes.

► **Event Listeners:** Handled multiple user interactions such as form submissions, button clicks, and dynamic content updates.

► **Responsive Design:** Achieved with a combination of CSS Grid, Flexbox, and adaptive media query breakpoints (768px, 480px).

► **Web Accessibility (A11y):**

* Correct usage of ARIA attributes (*role, aria-modal, aria-labelledby, aria-live*) for screen reader compatibility.
* Enhanced color contrast ratios for better readability across themes.
* Focus management for modals to maintain logical tab order and prevent focus trapping.

► **Performance Optimization:**

* Used the *defer* attribute for non-critical scripts to boost page load speed.
* Cached computed CSS styles to minimize forced reflows and enhance runtime performance.
* Embedded inline SVG icons to reduce HTTP requests and optimize image delivery.

► **Vercel Deployment:** Leveraged Vercel for seamless and efficient deployment, demonstrating strong understanding of modern CI/CD workflows.

# Project Structure
**index.html:** The main HTML file, providing the overall structure of the application, including navigation, expense forms, summary, analytics, and expense list sections.

**styles.css:** Contains all custom CSS rules, defining theme variables, preloader animations, and comprehensive responsive styling for all components.

**script.js:** Houses the core JavaScript logic, managing expense data, handling user interactions, updating analytics, and controlling UI elements like the theme toggle and custom modals.

# Usage
📋**Expense Tracker — How to Use**

**1. Add an Expense:**

• Fill in the form with the **amount**, **description**, **category**, **date**, and      **selected currency**.

• Click **“Add Expense”** to log your spending instantly.

**2. View Summary:**

• The **summary section** displays your **total expenses** and the **number of recorded   expenses** at a glance.

**3. Set Budget:**

• Enter your desired **monthly budget amount** in the input field.

• Click **“Set Budget”** to activate **budget tracking**.

• Monitor your spending against your budget with **real-time status updates**.

**4. Analyze Spending:**

• Navigate to the **“Analytics”** section

• Switch between **“Last 7 Days”**, **“Last 30 Days”**, and **“All Time”** tabs to view   spending trends.

• Explore **top categories** and **daily averages** through a clear and interactive        **pie chart visualization**.

**5. Filter/Search Expenses:**

• Use the **category dropdown** to filter your expense list by specific categories.

• Utilize the **search bar** to quickly find expenses by **description** or **date**.

**6. Toggle Theme:**

• Click the **sun/moon icon** in the header to switch effortlessly between **light**      and **dark** modes.

# Deployment
This project is live at https://personal-expense-tracker-free.vercel.app/, deployed using Vercel's powerful platform. The deployment process is streamlined through Continuous Deployment (CD) directly from the GitHub repository, ensuring that every code update is automatically built and deployed.

# ⚙️Challenges & Solutions

**1. Performance Optimization (TBT, INP, Reflows):**

• **Challenge:** Initial Lighthouse audits revealed high **Total Blocking Time (TBT)**    and **Interaction to Next Paint (INP)** during user interactions, indicating a           sluggish UI due to JavaScript execution and forced reflows. 

• **Solution:** Implemented the **defer** attribute for script loading to prevent           render blocking. Refactored JavaScript to cache computed styles and use                  **requestAnimationFrame** for DOM updates, reducing layout thrashing and improving        responsiveness. Replaced external image assets with **inline SVGs** to minimize           HTTP requests.

**2. Web Accessibility (A11y):**
• **Challenge:** Issues were found with **ARIA attribute usage** and **insufficient       color contrast**, affecting usability for assistive technologies and visually           impaired users.
• **Solution:** Enhanced color contrast for key text elements (e.g., `--text-secondary`) across both themes. Implemented proper **ARIA roles** (*dialog, aria-modal, aria-labelledby*) and **focus management** for the confirmation modal, ensuring full screen-reader accessibility. Added `aria-live="polite"` to dynamic message alerts.

**3. Chart Loading:**

• **Challenge:** Needed to ensure **Chart.js** loads efficiently and updates smoothly      without degrading performance.

• **Solution:** Dynamically loaded **Chart.js** with the **defer** attribute and           optimized chart re-rendering logic to update only when necessary, using **cached        theme colors**.

**4. Theme Consistency:**

• **Challenge:** Maintaining consistent visual design and readability across **light**    and **dark** modes.

• **Solution:** Used **CSS variables** (`:root` and `[data-theme="dark"]`) to define      theme-specific colors and properties, enabling seamless and consistent theme             switching.

**5. Data Persistence:**

• **Challenge:** Ensuring user data (expenses, budgets, and preferences) remained          persistent across sessions.

• **Solution:** Implemented the **Local Storage API** for robust offline data storage     and reliable session recovery.

**6. Responsiveness:**

• **Challenge:** Adapting the layout and functionality for a wide range of screen sizes   and devices.

• **Solution:** Designed with a **mobile-first approach**, leveraging **CSS Grid**,       **Flexbox**, and **media queries** to create a fully responsive and adaptive            interface.

# Future Improvements
• Add export/import functionality for data backup and migration.

• Implement bank sync or API integration for real-time transaction updates (requires backend development).

• Enhance analytics with more detailed reports, trend analysis over longer periods, and predictive insights.

• Add user authentication for multiple profiles and cloud synchronization of data.

• Explore advanced accessibility features for even broader inclusivity.

# Contributing
Feel free to fork this repository, submit issues, or send pull requests. I’d love to collaborate and improve this tool!

# Contact
Built with 💖 by Dileep Kumar Mangali. Connect with me on LinkedIn or email me at dileep.air44@gmail.com for feedback or opportunities.

