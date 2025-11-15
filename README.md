# Google-Play-Store-Apps-Insights-
# 📊 App Store Insights Dashboard — Power BI Project

A complete end-to-end Power BI analysis project built using the Google Play Store App Dataset.
This dashboard helps stakeholders understand app performance across installs, ratings, categories, pricing, genres, and user engagement.

# Project Overview

This project focuses on analyzing mobile applications from the Google Play Store to identify:

Top-performing categories

Rating & install trends

App pricing analysis

Content rating insights

Genre-level performance

Business opportunities and market patterns

The dashboard is built for Product Managers, App Developers, and Marketing Teams to make data-driven decisions.

# 1. Data Cleaning (Excel & Power Query)

Performed major cleaning steps before modeling:

Removed duplicates

Removed unnecessary characters ($, commas)

Fixed data types (numeric, text, date)

Handled missing values (NaN → 0 or blank)

Cleaned special characters in app names

Split genres properly

Standardized category & type values

# 2. Data Modeling (Star Schema)

A clean star schema was designed using:

Fact Table

Fact_Apps

Dimension Tables

Dim_Category

Dim_Type

Dim_ContentRating

Dim_Genres

All required relationships were built using 1-to-many and many-to-1 connections.

# 3. Key DAX Measures

Created custom measures, including:

Total Installs

Average Rating

Total Apps

Total Reviews

Price Category (Free / Paid)

Top N Apps

Rating Category Buckets

These measures helped build interactive visuals.

# 4. Dashboard Overview

Dashboard 1 — App Performance Overview Dashboard	

Provides high-level performance insights:

KPIs (Total Apps, Total Installs, Average Rating by Category, Paid vs Free Ratio)

Top 10 apps by Category Using Top 10

Average Reviews Using Donut Chart

Total installs by Categories Using Bar Chart

Total apps by Content rating distribution

# Dashboard 2 — App Insights & Performance Analysis

More detailed analysis with:

KPIs (Total Apps, Average Rating by Category)

Estimated Revenue X Expression Using Cluster Bar Chart

Top 10 Apps by Category Using Area Chart

Total Apps by Rating Category Using Cluster Bar Chart

Total Apps by Content Rating Using Ribbon Chart

Average Rating greater then or equal to 4 or greater then or equal to 3 by Top 10 Category Using Stacked Bar Chart


# 5. Insights & Findings

Some sample insights:

Free apps dominate installs but paid apps maintain stable ratings.

Categories like Games, Productivity, and Tools lead in overall installs.

Apps with higher review counts correlate with higher install volumes.

Content rating Everyone performs best across most categories.

# 6. Future Enhancements

Add time-series trends using “Last Updated” column

Combine Google Play + Apple Store datasets

Add sentiment analysis for user reviews

Build a prediction model for install forecasting

Include bookmarks for interactive storytelling

Create mobile-optimized dashboard for phones

# Tools Used
* Tool Purpose
* MS Excel Initial data cleaning
* Power Query	Advanced transformations
* Power BI Data modeling & dashboard creation
* DAX	Custom measure creation

# Dataset Source

Google Play Store Dataset (Apps + Reviews)

# Author
JANGAM VINAY CHARY Data Analyst | Power BI Developer
