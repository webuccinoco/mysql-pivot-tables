# Smart Pivot Table – Open-Source PHP MySQL Pivot Table Builder (MIT License)

![License](https://img.shields.io/badge/license-community-blue)
![PHP](https://img.shields.io/badge/php-7.4%2B-blue)
![MySQL](https://img.shields.io/badge/Database-MySQL%20%7C%20MariaDB-orange)
![No Code](https://img.shields.io/badge/No%20Code-Yes-success)
![Status](https://img.shields.io/badge/status-active-brightgreen)
![Verified Domain](https://img.shields.io/badge/domain-verified-brightgreen)

Transform your MySQL data into insightful pivot tables with **Smart Pivot Table** — a completely free, open-source **PHP MySQL pivot table builder** that eliminates the need for coding.  
Its intuitive visual interface lets you connect your database and define pivot data sources quickly, making pivot-table analysis accessible to developers, analysts, and business users.

---

##  Official Project

Official Website: https://www.mysqlreports.com/  
Pivot Tables Info Page: https://mysqlreports.com/php-mysql-pivot-tables/  
official Repository: https://github.com/webuccinoco/mysql-pivot-tables  

⚠️ This is the original and official repository of Smart Pivot Table.

---

## 📑 Table of Contents

- [What is Smart Pivot Table](#-what-is-smart-pivot-table)
- [What is a Pivot Table](#what-is-a-pivot-table)
- [Ways to Create MySQL Pivot Tables](#ways-to-create-mysql-pivot-tables)
- [Main Features of Smart Pivot Table](#main-features-of-smart-pivot-table)
  - [Core Functionality](#core-functionality)
  - [Data Analysis & Logic](#data-analysis--logic)
  - [Management & Deployment](#management--deployment)
  - [UI & Performance](#ui--performance)
- [Benefits & Who It's For](#benefits--who-its-for)
- [Smart Pivot Table vs Smart Report Maker](#smart-pivot-table-vs-smart-report-maker)
- [Getting Started](#-getting-started)
  - [Installation](#-installation)
  - [Signup Page](#-signup-page)
  - [Create Your Admin Account](#-create-your-admin-account)
  - [Build Pivot Tables with Ease](#-build-pivot-tables-with-ease)
- [Need More Features](#-need-more-features)
- [Frequently Asked Questions (FAQ)](#-frequently-asked-questions-faq)
- [Related Links](#-related-links)
- [Ownership](#ownership)
- [Trademark](#-trademark)

---

## 📊 What is Smart Pivot Table

**Smart Pivot Table** is an open-source **PHP tool for building pivot tables for MySQL and MariaDB** using a visual workflow.  
Instead of writing complex SQL, you can build pivot tables through a wizard-like UI that helps you:

- Connect to a MySQL/MariaDB database  
- Choose tables or views  
- Define rows, columns, and values  
- Apply aggregations  
- View summarized results instantly  

---

## What is a Pivot Table?

A pivot table is a powerful data processing tool used to summarize, sort, reorganize, group, count, total, or average data stored in a database. It allows you to transform rows of raw data into a meaningful multidimensional summary without changing the original data.

Pivot tables provide powerful summarization of data, allowing you to condense thousands of rows into a few key metrics. They are essential for identifying trends, comparing large datasets, and turning overwhelming amounts of information into actionable insights. Instead of scrolling through endless records, a pivot table gives you a bird's-eye view of your business performance in seconds.

---

## Ways to create MySQL Pivot Tables

- **Manual Coding:** You can write complex SQL queries using CASE statements and GROUP BY clauses. This "do-it-yourself" approach requires deep SQL expertise and significant time to maintain.  
  Check this blog post for more details: https://mysqlreports.com/php-mysql-pivot-tables/
- **Free Visual Tools:** Use a tool like Smart Pivot Table to build these tables visually. It’s a great way to skip the coding process entirely while keeping your project budget-friendly.
- **Commercial Solutions:** A professional tool like **Smart Report Maker** offers more advanced features, enhanced security, and premium support:  
  https://mysqlreports.com/mysql-reporting-tools/the-best-mysql-report-builder/

---

## Main Features of Smart Pivot Table

### Core Functionality

- **Visual Pivot Builder:** Create complex MySQL pivot tables without writing SQL. Connect to databases, select tables or views, and map fields to axes using an intuitive graphical interface.
- **No-Code Data Shaping:** Define rows, columns, and metrics through a simple wizard.
- **Flexible Data Sources:** Combine multiple tables or views with simplified join rules managed entirely through the UI.

### Data Analysis & Logic

- **Advanced Aggregations:** Apply operations including Sum, Count, Average, Min, Max, Distinct Count, and custom expressions.
- **Dynamic Filtering & Slicing:** Implement row/column filters, date/numeric ranges, and interactive slices for real-time data exploration.
- **Column Management:** Hide and show any columns from the table to focus on the data that matters most.

### Management & Deployment

- **Developer Friendly:** While no-code by default, the tool is lightweight and fast, and allows PHP code customization for advanced users.
- **Easy Installation:** Upload the PHP files and it works out of the box.
- **Basic Permissions:** Protect pivot definitions with a simple permission model for secure team collaboration.

### UI & Performance

- **Accessibility:** A modern interface allowing you to easily browse even large pivot tables.
- **Lightweight Architecture:** Designed for rapid deployment on standard PHP/MySQL stacks with local storage for pivot repositories.
- **Instant Summaries:** View data transformations immediately within a clean, themed UI optimized for speed.

---

## Benefits & Who It's For

- **Maximize Productivity:** Save hours of manual work by generating visual MySQL pivot tables instantly without writing any code.
- **Customized Summaries:** Summarize your data using the functions you need and collaborate seamlessly with your team on shared insights.
- **Versatile Audience:** Whether you are a developer, data analyst, or business owner, this tool makes it easy to explore and understand your MySQL data regardless of technical skill level.

Built entirely using **native PHP**, it’s lightweight, easy to set up, and released under the **MIT License** — giving you full freedom to **use**, **modify**, and **distribute** it even in commercial projects.

---

## Smart Pivot Table vs Smart Report Maker

If you’re looking for a more advanced and modern experience — including a **drag-and-drop pivot table builder**, dynamic filters, parameters, and enhanced features — check out the pivot tables module in **Smart Report Maker**:

[![Smart Report Maker - MySQL Pivot Table Drag and Drop Editor](https://mysqlreports.com/wp-content/uploads/2021/01/srm10_bigprof.gif)](https://mysqlreports.com/php-mysql-pivot-tables/)
<h5 align="center">Drag-and-Drop MySQL Pivot Table Builder Module in Smart Report Maker</h5>

More info about the drag-and-drop editor:  
https://mysqlreports.com/php-mysql-pivot-tables/

Try the demo:  
https://demo.mysqlreports.com/pivot-tables/create

---

## 🚀 Getting Started

### 🔧 Installation

To install **Smart Pivot Table**:

- Place the `MPT` directory inside a folder located within your web server's root directory (e.g., `htdocs` or `www`).
- Open your browser and navigate to the following link after replacing `path-to-MPT` with the actual path:

  `http://localhost/path-to-MPT/MPT`

- This should take you to the login setup page:

  `http://localhost/path-to-MPT/MPT/wizard/login.php?from=setconfig`

---

### 📝 Signup Page

You’ll see a signup page where you can create your **Admin profile**.

<img src="MPT/images/signup.png" alt="Signup Page" width="50%" />

---

### 👤 Create Your Admin Account

After signing up:

- The system will instruct you to delete the signup file for security reasons.
- Once done, log in using the Admin account you created.

---

### 🧩 Build Pivot Tables with Ease

After logging in, you’ll be greeted with a simple, intuitive interface to visually build your first MySQL Pivot Table:

- Connect to your MySQL or MariaDB database.
- Choose a data source: one or more tables or views.
- Define the rows: select the fields that will form the row axis.
- Define the columns: select the fields that will form the column axis.
- Define the values: select the fields and aggregation functions to summarize.

![Pivot Table Wizard](MPT/images/wizard.png)

---

## 🛠 Need More Features?

If you need advanced filtering options, custom parameters, or a more powerful pivot table builder, check out the upgraded module in Smart Report Maker:

https://mysqlreports.com/mysql-reporting-tools/the-best-mysql-report-builder/

Try the demo:  
https://demo.mysqlreports.com/pivot-tables/create

More info:  
https://mysqlreports.com/php-mysql-pivot-tables/

---

## ❓ Frequently Asked Questions (FAQ)

### What is the difference between Smart Pivot Table and Smart Report Maker?

**Smart Pivot Table** is a lightweight, free tool focused exclusively on creating **MySQL pivot tables**. It is ideal if your only requirement is building pivot tables quickly and simply.

**Smart Report Maker**, on the other hand, is a full-featured reporting platform that goes far beyond pivot tables:

1. **Multiple Modules & Advanced Reporting Features**  
   Smart Report Maker includes multiple modules for building reports, dashboards, charts, KPIs, and pivot tables—making it a complete reporting solution.  
   https://mysqlreports.com/mysql-reporting-tools/the-best-mysql-report-builder/

2. **Drag-and-Drop Pivot Table Builder**  
   Smart Report Maker provides a visual drag-and-drop editor for designing pivot tables with advanced options such as dynamic filters, parameters, and calculated fields.  
   https://mysqlreports.com/php-mysql-pivot-tables/

3. **Embed Manager for Secure Integration**  
   Smart Report Maker includes an Embed Manager that allows you to securely embed pivot tables and other generated resources into your own applications and websites.  
   https://mysqlreports.com/srm-modules-embed-manager/

### Can I use this on a shared hosting environment?

Yes. Since the tool is built with native PHP and requires only a standard MySQL connection, it works perfectly on any shared hosting provider.

### Does this tool support large MySQL datasets?

Absolutely. The architecture is designed to be lightweight and fast, allowing you to browse and summarize large tables through an optimized UI.

### Is this PHP pivot table tool really free?

Yes! Smart Pivot Table is open-source and released under the MIT License. You can use it for both personal and commercial projects at no cost.

### Can I customize the source code?

Yes. The MIT License allows you to modify the PHP code to fit your specific needs or integrate it into your existing web applications.

### Is MariaDB supported, or only MySQL?

Yes, MariaDB is fully supported. Since MariaDB is a drop-in replacement for MySQL, Smart Pivot Table works seamlessly with MariaDB databases using the same connection settings.

---

## 🔗 Related Links

- Explore the drag-and-drop editor for building MySQL Pivot Tables effortlessly:  
  https://mysqlreports.com/php-mysql-pivot-tables/
- Try the Demo version of Smart Report Maker:  
  https://demo.mysqlreports.com/pivot-tables/create
- Smart Report Maker Home Page:  
  https://mysqlreports.com/mysql-reporting-tools/the-best-mysql-report-builder/
- Embed Manager of Smart Report Maker (embed pivot tables in your own app or website):  
  https://mysqlreports.com/srm-modules-embed-manager/

---

## Ownership

Smart Pivot Table is developed and maintained by **Webuccino Inc**.  
The software is licensed, not sold. All intellectual property rights remain with Webuccino Inc.

---

## 🏷 Trademark

Smart Pivot Table™ is a trademark of Webuccino Inc.  
