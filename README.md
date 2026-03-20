# Transcript Pro | Academic Ledger 🎓

[![Live Demo](https://img.shields.io/badge/Live-Demo-brightgreen.svg)](https://paskonline.github.io/academic-transcript-generator/)

**Transcript Pro** is a high-fidelity academic record and GPA management system designed for students and professionals who require coordinate-perfect transcript simulation. This tool provides a professional, "dashboard-style" interface that simplifies the tracking of academic performance across multiple years and semesters.

---

## 🔒 Privacy & Security

*   **Zero-Server Architecture**: Your academic data is never uploaded to a cloud or external database.
*   **Purely Client-Side**: All calculations and PDF generations happen strictly within your browser's memory.
*   **Local Processing**: Your grades and personal info are cleared upon page refresh, ensuring complete privacy.

---

## ✨ Key Features

*   **Professional A4 PDF Export**: Generates a coordinate-perfect academic transcript ready for official planning or printing.
*   **Smart Bulk Import**: Supports advanced parsing of **Excel (.xlsx, .xls)** and **CSV** files with intelligent header mapping.
*   **Chronological Natural Sorting**: Automatically re-orders modules by Year and Semester (e.g., ensuring "Year 2" follows "Year 1") using a natural sorting algorithm.
*   **Customizable Grading Scale**: Users can fully edit GPA values to match specific institutional standards, such as those used by NSBM or the University of Kelaniya.
*   **Automatic Year Dividers**: Visually organizes the record with professional double-line dividers whenever the academic year changes.
*   **Mobile Responsive UI**: Built with a modern Tailwind CSS dashboard that adapts perfectly to desktop and mobile screens.

---

## 🚀 Usage Guide

### 1. Manual Entry
*   **Profile Setup**: Complete the Academic Profile section (Name, Student ID, Degree, etc.) to brand your final transcript.
*   **Adding Modules**: Use the "+ Add Module Row" button to enter module titles, credits, and grades manually.
*   **Dynamic Dividers**: Enter the Year (e.g., "1" or "Y1") to trigger automatic chronological grouping.

### 2. Bulk Upload
*   Click **Import Results** and choose a CSV or Excel file.
*   **Compulsory Headers**: Your file must include headers for **Module Name** and **Result**.
*   **Optional Headers**: Year, Semester, and Credits can be included or adjusted manually after upload.
*   **Testing**: If you want to see how the system works instantly, you can test it using our **[sample_import.csv](sample_import.csv)**. Simply download it and upload it via the Import button.

---

## 📊 GPA Calculation Logic

Transcript Pro utilizes a weighted average logic to ensure academic precision.

$$GPA = \frac{\sum (\text{Grade Points} \times \text{Credits})}{\text{Total Credits Attempted}}$$

*   **Grade Points**: Numerical values derived from your custom Grading Scale (e.g., A = 4.0).
*   **Quality Points (PTS)**: The product of the Grade Points and the specific Credit value of a module.

---

## 🛠️ Technical Stack

*   **Tailwind CSS**: For high-end, utility-first UI design.
*   **SheetJS (XLSX)**: For robust binary Excel and CSV data parsing.
*   **html2pdf.js**: For generating high-fidelity A4 PDF documents.

---

## 📄 Disclaimer

> This project is intended for academic planning and simulation purposes only. It is not an official university-issued transcript and should not be used as a substitute for official documentation.
