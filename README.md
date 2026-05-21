# Abdulsalam Al-Ashwal
### Data Analyst & Data Engineer | Systems & Software Developer

[LinkedIn](https://www.linkedin.com/in/abdulsalam-alashwal/) | [Email](mailto:abdulsalamalashwal@outlook.com) | [GitHub](https://github.com/abdulsalamfaiz2024-cmd) | [Live Portfolio](https://abdulsalam-portfolio.vercel.app/en)

---

## About Me

I am a Data Analyst and Data Engineer specializing in ETL/ELT pipeline automation, database design, and custom software systems. My background spans designing enterprise relational databases, decoupling complex business applications into lightweight standalone versions, and building robust data monitoring dashboards. I focus on translating complex data structures into clear, reliable systems that improve business operations.

*   Based in: Yemen
*   Languages: Arabic (Native) & English (Professional)
*   Approach: If a business workflow is manual and repeated, it can and should be automated.

---

## Technical Toolbox

*   **Business Intelligence**: Power BI (DAX / Modeling), Tableau, Excel & VBA, KPI Tracking, Monitoring & Evaluation Frameworks
*   **Data & Systems Engineering**: Python (ETL / Pandas / NumPy), PostgreSQL, SQL Server, SQLite, Flask, FastAPI, Docker
*   **Web & Mobile Development**: Next.js, React, TypeScript, Flutter, Tailwind CSS, HTML5/CSS3

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

### 5. [Customer Survival Analysis & Churn Prediction](https://github.com/abdulsalamfaiz2024-cmd/customer-survival-analysis)
*A statistical modeling pipeline built to forecast customer churn and evaluate retention factors.*
*   **Analysis**: Uses Kaplan-Meier curves and Cox Proportional Hazards regression to model customer survival lifespans.
*   **Modeling**: Combines survival models with Random Forest classifiers, applying SHAP values to explain feature contributions clearly.
*   **Dashboard**: Serves predictions through a Flask web application with interactive charts and parameter sliders.
*   **Technologies**: `Python`, `lifelines`, `scikit-learn`, `SHAP`, `Flask`, `Matplotlib`.

### 6. [Mini-ERP — Sales and Inventory Management System](https://github.com/abdulsalamfaiz2024-cmd/mini-erp-system)
*A desktop business application that handles sales checkouts, inventory valuation, and basic financial reporting.*
*   **Logic**: Implemented first-in, first-out (FIFO) inventory valuation, a transaction checkout workflow, and an in-memory cache to optimize database reads.
*   **Usability**: Includes keyboard shortcuts (Ctrl+K), dual themes, automated database structure checks on boot, and PDF invoice generation.
*   **Technologies**: `Python`, `Tkinter`, `SQLite`, `ReportLab`.

### 7. [Podcast Text Extractor — Audio Transcription Pipeline](https://github.com/abdulsalamfaiz2024-cmd/podcast-text-extractor)
*A file-monitoring pipeline that automatically extracts audio from media files, transcribes it, and formats the output.*
*   **Workflow**: Detects new video/audio files, uses FFmpeg for audio normalization, and calls a local Whisper model to transcribe the speech.
*   **Formatting**: Post-processes transcriptions for punctuation, timestamps, and formatting, exporting the final transcripts in Markdown and JSON.
*   **Technologies**: `Python`, `Whisper`, `FFmpeg`, `FastAPI`.

### 8. [PDF Pro Scanner — Web and Mobile Utility App](https://github.com/abdulsalamfaiz2024-cmd/pdf-pro-scanner)
*A document utility suite featuring a lightweight web interface and a cross-platform mobile application.*
*   **Web Client**: Built with React and Vite to support fast client-side PDF merging, image adjustments, and simple text recognition.
*   **Mobile Client**: A Flutter-based mobile application designed for document scanning, offline folder organization, and multi-language support.
*   **Technologies**: `Flutter`, `React`, `Vite`, `TypeScript`.

### 9. [Hotline — Bilingual Shipping & Logistics Web Portal](https://github.com/abdulsalamfaiz2024-cmd/hotline-logistics-web)
*A multi-page landing page and customer portal developed for a logistics and shipping company.*
*   **Live Link**: [hotline-web-three.vercel.app](https://hotline-web-three.vercel.app/)
*   **Design**: A responsive frontend featuring custom animations, full English/Arabic translation support, and interactive shipping inquiry forms.
*   **Performance**: Optimized for page loading speeds using image processing utilities, search engine optimization best practices, and lazy-loaded elements.
*   **Technologies**: `Next.js 15`, `React`, `Tailwind CSS`, `Lucide`.

### 10. [TNSC Relational Database Design](https://github.com/abdulsalamfaiz2024-cmd/tnsc-database-schema)
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

*   **B.Sc. in International Business Management** - *International University of Technology Twintech (IUTT), Yemen*
*   **IBM Data Engineering Specialization** (16-course program) - *IBM via Coursera*
*   **Advanced Business Analytics Specialization** - *University of Colorado via Coursera*
*   **Modern Big Data Analysis with SQL Specialization** - *Cloudera via Coursera*
*   **HND in Educational Leadership** - *Youth Leadership Development Foundation (YLDF)*

---

## My GitHub Status

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=abdulsalamfaiz2024-cmd&show_icons=true&theme=nord&count_private=true" alt="Abdulsalam's GitHub Stats" />
  <br/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=abdulsalamfaiz2024-cmd&layout=compact&theme=nord" alt="Top Languages" />
</div>

---

<div align="center">
  <h3>Let's Connect</h3>
  <p>Feel free to reach out for collaborations on Data Engineering projects, business intelligence dashboards, or systems automation.</p>
  
  [Email Me](mailto:abdulsalamalashwal@outlook.com) | [Connect on LinkedIn](https://www.linkedin.com/in/abdulsalam-alashwal/) | [View Live Web Portfolio](https://abdulsalam-portfolio.vercel.app/en)
</div>
