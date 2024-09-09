# Telecom SSIS Project
# 🚀 Automated ETL Solution for Customer Activity Data 

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

![Control Flow](https://github.com/user-attachments/assets/02b695ee-104d-447d-91f5-ea08e21169fa)

![Data Flow 1](https://github.com/user-attachments/assets/e3a6f43a-de61-4ba6-8450-1d7b57bdfe19)

![Data Flow 2](https://github.com/user-attachments/assets/382c1c72-e2b9-45b6-a31a-6f4b95714eaa)

![Database Schema](https://github.com/user-attachments/assets/92e4f44b-f3bd-4aa9-ae76-1f86e572fa2e)

## 🎉 Result

![Result](https://github.com/user-attachments/assets/f5f091bf-b835-478e-8b23-c3c09e190a50)

## 📚 References

* [ETL - Telecom - Garage Education](https://docs.google.com/document/d/1CsG6QS6Hh-T6x-luJoGlx2eJq6CXvfbwKB7977bjc8o/edit)
* [Al-Moatasem](https://github.com/Al-Moatasem/ETL-Telecom-SSIS)
