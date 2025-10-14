---
title: Jeonju Cultural Tourism Integrated System Database Design
summary: A project to design a relational database for providing personalized services by integrating scattered tourism information in the Jeonju area.
featured: featured.png
tags:
  - Database Design
  - SQL
  - ERD
  - Normalization
  - System Design
date: 2025-06-20
external_link: ''
---
<div class="justify-text">
As a final project for the Database Design course at Jeonbuk National University, SookYoung In (인숙영) **designed a database for the 'Jeonju Cultural Tourism Integrated System'**. The goal was to collect information about cultural facilities, restaurants, festivals, weather, etc., scattered across various Jeonju City websites and provide useful customized information to tourists.

The project followed a systematic database design lifecycle:
1. **Requirements Analysis**: Analyzed Jeonju City-related websites to collect requirements for core data such as tourists, cultural facilities, and programs, and created specifications.
2. **Conceptual Design**: Created an **ER Diagram (ERD)** by deriving core entities and their relationships based on collected requirements.
3. **Logical Design**: Converted ERD into relational schema and performed **normalization up to 3NF (Third Normal Form)** to minimize data redundancy and inconsistency, ensuring data integrity.
4. **Physical Design**: Based on the final relation schema, wrote `CREATE TABLE` scripts using Oracle SQL and defined constraints and indexes. Also, built the database by `INSERT`ing actual data.

Through this project, I gained experience in the entire process of database design, going beyond simply using SQL to analyzing complex real-world requirements and turning them into systematic data models.
</div>