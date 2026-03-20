# Transcript Pro | Academic Ledger 🎓

[![Live Demo](https://img.shields.io/badge/Live-Demo-brightgreen.svg)](https://paskonline.github.io/academic-transcript-generator/)

**Transcript Pro** is a high-fidelity academic record and GPA management system designed for students and professionals who require coordinate-perfect transcript simulation.[cite: 1] This tool provides a professional, "dashboard-style" interface that simplifies the tracking of academic performance across multiple years and semesters.[cite: 1, 3]

---

## 🔒 Privacy & Security

*   **Zero-Server Architecture**: Your academic data is never uploaded to a cloud or external database.[cite: 1]
*   **Purely Client-Side**: All calculations and PDF generations happen strictly within your browser's memory.[cite: 1]
*   **Local Processing**: Your grades and personal info are cleared upon page refresh, ensuring complete privacy.[cite: 1]

---

## ✨ Key Features

*   **Professional A4 PDF Export**: Generates a coordinate-perfect academic transcript ready for official planning or printing.[cite: 3]
*   **Smart Bulk Import**: Supports advanced parsing of **Excel (.xlsx, .xls)** and **CSV** files with intelligent header mapping.[cite: 1]
*   **Chronological Natural Sorting**: Automatically re-orders modules by Year and Semester (e.g., ensuring "Year 2" follows "Year 1") using a natural sorting algorithm.[cite: 1]
*   **Customizable Grading Scale**: Users can fully edit GPA values to match specific institutional standards, such as those used by NSBM or the University of Kelaniya.[cite: 1, 3]
*   **Automatic Year Dividers**: Visually organizes the record with professional double-line dividers whenever the academic year changes.[cite: 3]
*   **Mobile Responsive UI**: Built with a modern Tailwind CSS dashboard that adapts perfectly to desktop and mobile screens.[cite: 1]

---

## 🚀 Usage Guide

### 1. Manual Entry
*   **Profile Setup**: Complete the Academic Profile section (Name, Student ID, Degree, etc.) to brand your final transcript.[cite: 1, 3]
*   **Adding Modules**: Use the "+ Add Module Row" button to enter module titles, credits, and grades manually.[cite: 1]
*   **Dynamic Dividers**: Enter the Year (e.g., "1" or "Y1") to trigger automatic chronological grouping.[cite: 1]

### 2. Bulk Upload
*   Click **Import Results** and choose a CSV or Excel file.[cite: 1]
*   **Compulsory Headers**: Your file must include headers for **Module Name** and **Result**.[cite: 1]
*   **Optional Headers**: Year, Semester, and Credits can be included or adjusted manually after upload.[cite: 1]

---

## 📊 GPA Calculation Logic

Transcript Pro utilizes a weighted average logic to ensure academic precision:[cite: 1]

$$GPA = \frac{\sum (\text{Grade Points} \times \text{Credits})}{\text{Total Credits Attempted}}$$

*   **Grade Points**: Numerical values derived from your custom Grading Scale (e.g., A = 4.0).[cite: 1, 3]
*   **Quality Points (PTS)**: The product of the Grade Points and the specific Credit value of a module.[cite: 1, 3]

---

## 🛠️ Technical Stack

*   **Tailwind CSS**: For high-end, utility-first UI design.[cite: 1]
*   **SheetJS (XLSX)**: For robust binary Excel and CSV data parsing.[cite: 1]
*   **html2pdf.js**: For generating high-fidelity A4 PDF documents.[cite: 1]

---

## 📄 Disclaimer

> This project is intended for academic planning and simulation purposes only.[cite: 1] It is not an official university-issued transcript and should not be used as a substitute for official documentation.[cite: 1, 3]

---
