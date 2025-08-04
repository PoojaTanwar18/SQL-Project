# SQL-Project
🌍 Tour Package Planner with Price Estimator (SQL Project)
🚀 Just published my new project!
This is a Tour Package Planner built using SQL that enables users to design and customize their own travel packages by selecting destinations, hotels, and activities — with real-time cost estimation.
🧾 Extended Project Summary: Tour Package Planner with Price Estimator
The Tour Package Planner with Price Estimator is a comprehensive SQL-based project designed to replicate a real-world travel management system. It enables users—such as travelers, travel agents, or tour companies—to build custom travel packages by selecting from a curated list of destinations, hotels, and activities. The system then calculates the total trip cost based on the choices made by the user, giving them a clear and detailed financial estimate for their tour.

This project combines the fundamental and advanced concepts of relational database design and structured query language (SQL). It is perfect for learners and professionals who want to apply SQL to solve real-world problems involving multiple entities, relationships, and data analysis.

🔍 What This System Can Do
📦 Custom Package Creation: Users can create personalized tour packages by choosing destinations, selecting hotels for accommodation, and adding sightseeing or adventure activities.

💵 Real-time Cost Estimation: As users choose their preferences, the system dynamically calculates the total trip cost, including hotel stays (based on duration and per-night pricing) and activity fees.

📊 Insightful Analytics: Using SQL queries, the system can answer real-time business questions such as the most booked destinations, the highest-spending users, and which packages are trending.
🧾 Data Integrity and Organization: Through the use of foreign keys and normalized table design, the database ensures data consistency and eliminates redundancy.
📁 Historical Records: It stores all packages created and their associated costs, enabling review and insights into past trends and bookings.

🛠️ Tables Used in the Project
Users – Stores traveler data like name, email, and contact information.
Packages – Contains details of the package including destination, user, and travel dates.
Hotels – Stores accommodation options with per-night rates and location.
Activities – Lists various leisure and adventure activities with associated costs, tied to destinations.
Costs – Calculates and stores the final cost of a tour package by combining hotel stays and selected activities.

🧠 Concepts Covered in SQL
This project thoroughly applies core and advanced SQL concepts:
DDL (Data Definition Language): CREATE, ALTER, MODIFY, DROP to define and update table structures.
DML (Data Manipulation Language): INSERT, UPDATE, DELETE to manage data inside tables.
DQL (Data Query Language): SELECT with various clauses to retrieve meaningful data.
Operators: Arithmetic, Logical, Comparison, Range (BETWEEN), Pattern Matching (LIKE), and Sorting (ORDER BY).

Functions:
String Functions: UPPER(), LOWER(), etc.
Mathematical Functions: ROUND(), MAX(), MIN()
Date Functions: DATEDIFF(), CURDATE(), DATE_ADD()
Aggregate Functions: COUNT(), SUM(), AVG()
Joins: INNER JOIN, LEFT JOIN, RIGHT JOIN, and simulated FULL OUTER JOIN using UNION.
Subqueries: Including single-row, multi-row, multi-column, and nested subqueries.
Views: Virtual tables created using SQL queries to combine and simplify data representation.
Clauses: GROUP BY, HAVING, IN, LIMIT to refine query results.

📈 Insightful Use Cases (SQL Query Examples)
This project includes dozens of real-world SQL query examples that answer meaningful questions such as:
👥 Which users have booked trips to specific countries?
💰 What is the total amount each user has spent across all their packages?
🏆 Who is the highest-spending traveler in a single package?
📅 Which packages are scheduled to begin in the next 30 days?
📌 What is the average hotel price per destination?
🔢 How many users have booked more than one package?
🔍 List all hotel-activity combinations under a certain cost threshold.
📊 Rank destinations based on number of packages booked.
These insights make the system not just a backend database, but a powerful decision-making tool for travel businesses.
🎓 Learning Outcomes
This project is a perfect capstone for SQL learners and aspiring data professionals. You will:
Learn how to structure a real-world relational database from scratch
Gain expertise in all major categories of SQL: DDL, DML, DQL, functions, joins, and subqueries
Practice generating reports and data insights
Understand how to estimate costs using mathematical operations in SQL
Explore how SQL can support business logic and user-driven data interactions
👥 Who Can Benefit from This Project
💼 Business Analysts & Data Analysts: Looking to practice real-time SQL use cases
🎓 Students: Working on academic SQL projects or internships
🧠 Educators: Wanting an applied example to teach core SQL concepts
🧳 Travel Businesses: Who want to model, analyze, and optimize travel package offerings
🧪 SQL Learners: Who want to go beyond theory and apply SQL to simulate a working system
✅ Conclusion
The Tour Package Planner with Price Estimator is not just a database project — it's a complete simulation of a real-world travel booking and analysis platform, showcasing the depth and power of SQL in organizing, managing, and deriving insights from structured data. Whether you’re a beginner in SQL or looking to test your advanced skills, this project offers a challenging yet practical experience.
