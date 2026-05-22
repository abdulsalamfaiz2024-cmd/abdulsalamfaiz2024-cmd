# Abdulsalam Al-Ashwal
### Data Analyst & Data Engineer | Systems & Software Developer

<div align="center">
  <img src="profile-circle.png" alt="Abdulsalam Al-Ashwal" width="150" />
</div>

<br/>

<div align="center">
  <a href="README_AR.md"><b>العربية (Arabic Version)</b></a>
</div>

<br/>

<div align="center">
  <a href="https://www.linkedin.com/in/abdulsalam-alashwal/" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="mailto:abdulsalamalashwal@outlook.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
  <a href="https://github.com/abdulsalamfaiz2024-cmd" target="_blank">
    <img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
  </a>
  <a href="https://abdulsalam-portfolio.vercel.app/en" target="_blank">
    <img src="https://img.shields.io/badge/Portfolio-00C7B7?style=for-the-badge&logo=vercel&logoColor=white" alt="Live Portfolio" />
  </a>
</div>

---

## About Me

I am a Data Analyst and Data Engineer specializing in ETL/ELT pipeline automation, database design, and custom software systems. My background spans designing enterprise relational databases, decoupling complex business applications into lightweight standalone versions, and building robust data monitoring dashboards. I focus on translating complex data structures into clear, reliable systems that improve business operations.

*   Based in: Yemen
*   Languages: Arabic (Native) & English (Professional)
*   Approach: If a business workflow is manual and repeated, it can and should be automated.

---

## Technical Toolbox

*   **Business Intelligence**: <br/>
    ![](https://img.shields.io/badge/Power_BI-F2C811?style=flat-square&logo=powerbi&logoColor=black) ![](https://img.shields.io/badge/Tableau-E97627?style=flat-square&logo=tableau&logoColor=white) ![](https://img.shields.io/badge/Microsoft_Excel-217346?style=flat-square&logo=microsoftexcel&logoColor=white)
*   **Data & Systems Engineering**: <br/>
    ![](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![](https://img.shields.io/badge/SQL_Server-CC2927?style=flat-square&logo=microsoftsqlserver&logoColor=white) ![](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white) ![](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white) ![](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) ![](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)


---

## Highlighted Projects

### 1. [Financial Market Research Dashboard](https://github.com/abdulsalamfaiz2024-cmd/financial-intelligence-agent)
*A market analysis tool that collects real-time financial data to perform technical and sentiment analysis.*
*   **System**: Built with a modular Python backend that scrapes and integrates financial data streams from Yahoo Finance and Alpha Vantage.
*   **Data Store**: Uses ChromaDB and local caching for high-speed retrieval of historical analysis notes.
*   **UI & API**: Uses FastAPI to serve data to an interactive Streamlit dashboard with Plotly charts.
*   **Technologies**: `Python`, `FastAPI`, `Streamlit`, `ChromaDB`, `scikit-learn`.

### 2. [Yemen Analytics & Monitoring Command Center](https://github.com/abdulsalamfaiz2024-cmd/yemen-crisis-dashboard)
*A geospatial data platform that collects and displays real-time weather data and humanitarian indicators for Yemen's governorates.*
*   **Live Link**: [yemen-crisis-dashboard.vercel.app/health](https://yemen-crisis-dashboard.vercel.app/health)
*   **Visuals**: Integrates Leaflet.js maps with a custom HTML5 Canvas overlay that animates wind patterns dynamically based on live database values.
*   **Data Pipelines**: Automated background scripts fetch weather parameters every 5 minutes from the Open-Meteo API, combining them with RSS feeds from ReliefWeb (OCHA) and public population indicators.
*   **Analytics**: Interactive Chart.js radar charts and grids display atmospheric indices, medical caseload trends, and simulated school attendance metrics.
*   **Technologies**: `Python`, `Flask`, `SQLite`, `Leaflet.js`, `Chart.js`.

### 3. [PhonixPro — Data Analytics and Reporting Platform](https://github.com/abdulsalamfaiz2024-cmd/phonix-pro)
*A web application designed to simplify statistical modeling, data cleaning, and business reporting.*
*   **Live Link**: [phonixpro.ddns.net](https://phonixpro.ddns.net/)
*   **Features**: Supports drag-and-drop CSV/Excel file uploads, automatic data type detection, descriptive statistics (PCA, clustering, regression), and PDF exports.
*   **Interactivity**: Includes a natural-language data query assistant, automated layout structures, and smart recommendations for data cleaning.
*   **Technologies**: `Next.js 15`, `React`, `Python`, `PostgreSQL`, `Redis`, `Framer Motion`.

### 4. [COMS — Decoupled Business Management Core](https://github.com/abdulsalamfaiz2024-cmd/coms-standalone-core)
*Decoupled a complex consulting operations application from the heavy ERPNext/Frappe framework, converting it into a lightweight, standalone system.*
*   **Live Link**: [custom-system-copy.onrender.com](https://custom-system-copy.onrender.com)
*   **Core Logic**: Created a custom Python utility to replicate Frappe's database query methods and validators, eliminating the need to install or run the full Frappe bench environment.
*   **Database & Server**: Ported all data structures to SQLite and wrapped the system in a Flask/FastAPI REST server.
*   **Migrations**: Developed migration scripts to safely extract and import data from legacy systems while maintaining referential integrity.
*   **Technologies**: `Python`, `SQLite`, `Flask`, `FastAPI`.

### 5. [Mini-ERP — Sales and Inventory Management System](https://github.com/abdulsalamfaiz2024-cmd/mini-erp-system)
*A desktop business application that handles sales checkouts, inventory valuation, and basic financial reporting.*
*   **Logic**: Implemented first-in, first-out (FIFO) inventory valuation, a transaction checkout workflow, and an in-memory cache to optimize database reads.
*   **Usability**: Includes keyboard shortcuts (Ctrl+K), dual themes, automated database structure checks on boot, and PDF invoice generation.
*   **Technologies**: `Python`, `Tkinter`, `SQLite`, `ReportLab`.

### 6. [Podcast Text Extractor — Audio Transcription Pipeline](https://github.com/abdulsalamfaiz2024-cmd/podcast-text-extractor)
*A file-monitoring pipeline that automatically extracts audio from media files, transcribes it, and formats the output.*
*   **Workflow**: Detects new video/audio files, uses FFmpeg for audio normalization, and calls a local Whisper model to transcribe the speech.
*   **Formatting**: Post-processes transcriptions for punctuation, timestamps, and formatting, exporting the final transcripts in Markdown and JSON.
*   **Technologies**: `Python`, `Whisper`, `FFmpeg`, `FastAPI`.

### 7. [PDF Pro Scanner — Web and Mobile Utility App](https://github.com/abdulsalamfaiz2024-cmd/pdf-pro-scanner)
*A document utility suite featuring a lightweight web interface and a cross-platform mobile application.*
*   **Web Client**: Built with React and Vite to support fast client-side PDF merging, image adjustments, and simple text recognition.
*   **Mobile Client**: A Flutter-based mobile application designed for document scanning, offline folder organization, and multi-language support.
*   **Technologies**: `Flutter`, `React`, `Vite`, `TypeScript`.

### 8. [Hotline — Bilingual Shipping & Logistics Web Portal](https://github.com/abdulsalamfaiz2024-cmd/hotline-logistics-web)
*A multi-page landing page and customer portal developed for a logistics and shipping company.*
*   **Live Link**: [hotline-web-three.vercel.app](https://hotline-web-three.vercel.app/)
*   **Design**: A responsive frontend featuring custom animations, full English/Arabic translation support, and interactive shipping inquiry forms.
*   **Performance**: Optimized for page loading speeds using image processing utilities, search engine optimization best practices, and lazy-loaded elements.
*   **Technologies**: `Next.js 15`, `React`, `Tailwind CSS`, `Lucide`.

### 9. [TNSC Relational Database Design](https://github.com/abdulsalamfaiz2024-cmd/tnsc-database-schema)
*A normalized PostgreSQL database schema designed to migrate complex NGO operations from spreadsheet tracking into a structured, high-integrity database.*
*   **Structure**: Features 36 fully-normalized tables, optimized composite indexes, and 6 custom views for staff utilization and financial tracking.
*   **Rules & Triggers**: Utilizes UUID primary keys, bilingual columns, soft-delete rules, and triggers for automated audit logs.
*   **Technologies**: `PostgreSQL`, `Relational Schema Design`, `Query Optimization`.

---

## Professional Timeline

*   **Data Analyst & Engineer Trainee** @ *Hayel Saeed Anam (HSA) Group* *(Jan 2026 – Present)*
    *   Designed automated sales dashboards and KPIs using SAP ERP data, improving commercial reporting speed and efficiency.
*   **Monitoring & Evaluation Assistant** @ *Tamdeen Youth Foundation* *(Jan 2025 – Dec 2025)*
    *   Developed Results-Oriented Monitoring (ROM) frameworks and programmed custom Python scripts for data validation.
*   **Business Analyst (Part-Time)** @ *Triple Nexus Strategic Company (TNSC)* *(Jun 2024 – Dec 2024)*
    *   Crafted operation tracking matrices and business dashboards that modernized consulting delivery pipelines.

---

## Credentials & Education

### Academic Degree

> **Bachelor of Science (B.Sc.) in International Business Management**
> *International University of Technology Twintech (IUTT), Yemen*

---

### Certifications & Specialized Programs

*   **IBM Data Engineering Specialization** (16-course program) - *IBM via Coursera* | [Verify ↗](https://coursera.org/share/b92252a31c9217759bbdb98be201608e)
    <br/>
    <img src="IBM_Data_Engineering.png" alt="IBM Data Engineering Certificate" width="350" />
*   **Advanced Business Analytics Specialization** (5-course program) - *University of Colorado via Coursera* | [Verify ↗](https://coursera.org/verify/specialization/SS7MCGLM9B92)
    <br/>
    <img src="Advanced_Business_Analytics.png" alt="Advanced Business Analytics Certificate" width="350" />
*   **Modern Big Data Analysis with SQL Specialization** (3-course program) - *Cloudera via Coursera* | [Verify ↗](https://coursera.org/share/0814333adf33da90fe2725ac5adc5b91)
    <br/>
    <img src="Modern_Big_Data_Analysis.png" alt="Modern Big Data Analysis with SQL Certificate" width="350" />
*   **Entrepreneurship Mastery Program** (5-course program) - *Mohammed bin Rashid Foundation & UNDP via Coursera* | [Verify ↗](https://coursera.org/share/519ae898fa90c20a74d2589a8ae32aa9)
    <br/>
    <img src="Entrepreneurship_Mastery.png" alt="Entrepreneurship Mastery Program Certificate" width="220" />
*   **Youth Leadership Program** - *Youth Leadership Development Foundation (YLDF)*
    <br/>*(Includes: English Diploma, ICDL Diploma, and Leadership & Public Speaking Diploma)*
    <br/>
    <img src="HND_Educational_Leadership.png" alt="Youth Leadership Program Certificate" width="250" />



<div align="center">
  <h2>Contact & Collaboration</h2>
  <p>If you are looking to collaborate on data engineering projects, build business intelligence dashboards, or automate manual workflows, let's connect:</p>

  <table align="center">
    <tr>
      <td><b>Email</b></td>
      <td><a href="mailto:abdulsalamalashwal@outlook.com">abdulsalamalashwal@outlook.com</a></td>
    </tr>
    <tr>
      <td><b>Phone / WhatsApp</b></td>
      <td><a href="tel:+967775032054">+967 77 503 2054</a> / <a href="https://wa.me/967775032054">WhatsApp Message</a></td>
    </tr>
    <tr>
      <td><b>Professional Links</b></td>
      <td><a href="https://www.linkedin.com/in/abdulsalam-alashwal/">LinkedIn Profile</a> | <a href="https://abdulsalam-portfolio.vercel.app/en">Live Web Portfolio</a></td>
    </tr>
  </table>
</div>
