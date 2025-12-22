# Data_Visualization_Tableau
Project Overview

This project is a Tableau-based data modeling and visualization exercise using the Bookshop dataset. The objective is to understand and implement proper data relationships across multiple tables, distinguish between conceptual entities such as books and editions, and answer an analytical question through visualization.

The project emphasizes relational data modeling in Tableau, exploratory analysis, and clear visual communication using a packaged Tableau workbook.

Dataset Description

Dataset Name: Bookshop

Data Structure: Multi-table relational dataset

Key Concept:

A Book represents the abstract work (title, author, genre).

An Edition represents a physical version of a book (format, publication date, pages, price).

Core Tables Used

Book – Book identifiers, title, author

Info – Genre, series, volume number, staff comments

Edition – ISBN, format, publication details, price

Author – Author demographics and writing attributes

Publisher – Publishing house and location details

Sales (Q1–Q4) – Transaction-level sales data

Ratings – Customer ratings (1–5 scale)

Series – Series-level metadata

Checkouts / Awards – Engagement and recognition data

Objectives

The objectives of this project are to:

Correctly connect multiple related tables in Tableau using relationships and joins

Apply a calculated join condition between the Book and Info tables

Understand hierarchical and transactional data (Orders and Items)

Create a meaningful visualization that answers a self-defined analytical question

Export and submit a packaged Tableau workbook and supporting image

Tools Used

Tableau Desktop

Bookshop dataset (provided with exercise)

Data Preparation & Relationships

The data source was prepared according to the provided relationship diagram and instructions:

Edition is the central table

Publisher and Sales tables are related to Edition

Book and Info tables are joined using the calculated field:

BookID = [BookID1] + [BookID2]


Join type: Inner Join

Series is only available after Info is included in the data model

Sales data uses hierarchical identifiers:

One OrderID can contain multiple ItemID values

ISBN is treated as a unique identifier for each edition

Visualization Task

After reviewing and understanding all fields, a visualization was created to answer a user-defined analytical question using the Bookshop dataset. The worksheet was:

Appropriately named and titled

Designed using relevant measures and dimensions

Saved as part of the Tableau workbook

Notes

This project focuses on data modeling accuracy and visualization clarity

Results are exploratory and descriptive

Conclusions depend on the analytical question posed by the user
