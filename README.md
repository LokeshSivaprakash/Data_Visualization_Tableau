# Data_Visualization_Tableau
Project Overview

Bookshop Data Modeling & Analytics (Tableau)
Overview

This project uses Tableau to model and analyze the Bookshop dataset. It combines relational data modeling with exploratory visualization to answer open-ended questions about books, publishers, sales, and customer engagement. The project reflects a real-world analytics workflow: preparing data correctly first, then using visualization to derive insight.

Dataset

The Bookshop dataset is a multi-table relational dataset containing information on:

Books and editions

Authors and publishers

Sales transactions (Q1–Q4)

Ratings, checkouts, series, and awards

A key concept is the distinction between a Book (the abstract work) and an Edition (a physical version identified by ISBN).

Objectives

Build a correct relational data model in Tableau

Apply calculated joins and table relationships

Explore publishing trends, book popularity, and customer behavior

Answer analytical questions using effective visualizations

Practice clear analytical reasoning and visualization design

Data Modeling (Part 1)

Edition is the central table

Publisher and Sales tables are related to Edition

Book and Info are joined using a calculated field:

BookID = [BookID1] + [BookID2]


Join type: Inner Join

Series is available only after Info is included

ISBN uniquely identifies each edition

Sales data follows an Order → Item hierarchy

This structure ensures accurate aggregation and prevents duplication.

Analysis & Visualization (Part 2)

Visualizations were created to answer the following questions:

Publisher specialization: Do publishers focus on specific genres, formats, or markets?

Book popularity: Which books are most and least popular based on sales, ratings, and checkouts?

Publication timing: When are most books published, and are there anomalies?

Ratings distribution: How do ratings vary by book, genre, and awards?

Each question was answered using appropriate charts selected for clarity and insight.

Deliverables

Packaged Tableau Workbook (.twbx)

Exported visualization screenshots

README.md (this file)

Conclusion

This project demonstrates how strong data modeling supports meaningful visualization. By combining accurate table relationships with thoughtful visual analysis, the project provides insight into publishing behavior, book performance, and customer engagement—mirroring the type of analytical work expected in professional settings.
