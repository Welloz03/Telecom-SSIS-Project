# Telecom SSIS Project
# 🚀 Automated ETL Solution for Customer Activity Data 🚀

## 🧐 Problem Statement

A telecommunications company faces challenges in efficiently processing and analyzing the vast customer activity data generated every 5 minutes. The current manual process is error-prone and time-consuming, hindering the company's ability to gain timely insights from this valuable data.

## ✨ Project Description

### 🎯 Objective

The primary goal of this project is to develop and deploy an automated ETL solution to seamlessly ingest, validate, transform, and load customer activity data from CSV files into a structured database. This solution will ensure data accuracy, completeness, and availability for analysis, empowering the company to make data-driven decisions and enhance its services.

### ⚙️ Scope

* **Extract:**
    * 🔄 Periodically read and parse CSV files generated every 5 minutes.
    * 🛡️ Handle file access, variations, and errors robustly.

* **Transform:**
    * ✅ Implement data validation and cleansing rules.
    * 🔗 Enrich data through joins with external references.
    * 🔒 Apply data masking or anonymization for privacy.
    * 🏷️ Generate metadata for tracking and auditing.

* **Load:**
    * 🏗️ Design and create a target database schema.
    * ♻️ Employ incremental loading to prevent duplicate data.
    * 📥 Load valid records into the main table, and rejected records into an error table.
    * 🔍 Establish traceability between stored data and CSV files.
    * 🗄️ Archive processed CSV files.

## 📦 Package Design

* **Control Flow:** 🧠 Manages the overall package execution.
* **Data Flow:** 🔀 Handles the actual data processing and movement.
* **Audit Dimension:** 📝 Stores crucial information about each package run.

[**Image: Control Flow Diagram**]

[**Image: Data Flow Diagram**]

[**Image: Database Schema**]

## 🎉 Result

[**Image: Example of processed data or dashboard**]

## 📚 References

* [ETL - Telecom - Garage Education](https://docs.google.com/document/d/1CsG6QS6Hh-T6x-luJoGlx2eJq6CXvfbwKB7977bjc8o/edit)
* [Al-Moatasem](https://github.com/Al-Moatasem/ETL-Telecom-SSIS)
