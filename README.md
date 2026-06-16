📊 Student Performance & Behavior Analytics Dashboard (End-to-End Power BI Project)
📝 Project Overview
This project is an enterprise-grade academic analytics dashboard developed in Power BI to monitor and analyze student performance, attendance patterns, and behavioral trends. Built on a robust data architecture, it provides educational administrators and educators with actionable insights into student outcomes, term-wise progress, and subject-specific engagement.

🛠️ Key Features Implemented
1️⃣ Data Modeling & Academic Architecture
Star Schema Layout: Established a clean data model with optimized relationships between student demographical dimensions, academic tables, and performance fact records.

Streamlined Report View: Hidden technical system keys, indexes, and unnecessary columns from the end-user panel to keep the workspace clean and focused.

Standardized Conventions: Followed industry-grade naming conventions across all fields, tables, and custom measures.

2️⃣ Advanced Analytics & Performance Metrics
Dynamic Calculations: Developed critical metrics using CALCULATE, FILTER, ALL, SUMX, COUNTX, and AVERAGEX to compute rolling student averages and behavioral insights.

Contextual Data Mapping: Utilized relational DAX functions to integrate student metadata seamlessly into diverse academic performance evaluations.

Granular Calculations: Created tailored columns for descriptive student profiling, precise class-section mapping, and dynamic grade/pass-percentage segmentation.

3️⃣ Academic Time-Intelligence & Sessional Trends
Term & Monthly Progress Tracks: Configured analytical paths to evaluate sessional growth across multiple academic terms (Term 1, Term 2, and Term 3).

Attendance Trend Identification: Uncovered seasonal and month-over-month attendance drops to help administrators pinpoint behavioral shifts.

4️⃣ Dashboard Layout & Visualizations
The report architecture consists of 1 Main Analytics Sheet, 2 Deep-Dive Detail Pages, and a dedicated Student Drillthrough view:

Executive Performance Summary: Deployed prominent KPI cards capturing core metrics like Total Students (1000), Attendance Rate (90%), and Average Score per Subject (49.87).

Behavioral & Absence Trends: Integrated multi-layered column charts tracking student absences by subject & class alongside continuous monthly line trends.

Advanced Tabular Analysis: Formatted a structured Student Performance Matrix equipped with custom indicators for pass percentages, top achievers, and class distributions.

Top Performer Recognition: Engineered dynamic elements highlighting top-tier individuals (e.g., Top Performer card) alongside custom pass-rate gauge visuals.

5️⃣ Interaction, Filtering & UX Enhancement
Multi-Tier Slicers: Included responsive drop-down filters for Class, Section, Subject, and Academic Term.

Advanced Interactivity: Enabled intuitive cross-filtering, vertical drill-down hierarchies, and analytical drillthrough targets.

Custom Navigation System: Built a streamlined side-navigation dock featuring interactive buttons for smooth transitions between Overview, Performance, and Profile views.

One-Click State Reset: Embedded action buttons utilizing bookmarks to instantly clear active academic filters and restore the default canvas layout.

6️⃣ Mobile-Optimized Viewport
On-The-Go Analytics: Fully designed and restructured layouts engineered specifically for mobile devices.

Responsive Prioritization: Re-stacked key metrics to surface high-priority metrics like student count, core filters, and immediate attendance percentages sequentially on handheld screens.

📸 Dashboard Previews
1️⃣ Student Performance & Behavior Analytics Overview
The core executive layout illustrating macro metrics, monthly attendance patterns, and localized absenteeism across standard academic subjects like English, Geography, History, Math, and Science.

Screenshot 2026-06-16 160126.png

2️⃣ Performance Table & Achieve Analytics
A detail-oriented tabular matrix allowing educators to scan individual Student IDs, names, specific scoring metrics, and immediate tracking of top performers alongside total pass percentage gauges.

Screenshot 2026-06-16 160148.png

3️⃣ Student Profile & Term Breakdown
A granular drillthrough target page showing distinct profiles (e.g., Lara Simmons - Class 10), providing subject performance bar distributions, exam type splits, and historical term-over-term score progression lines.

Screenshot 2026-06-16 160203.png

4️⃣ Mobile-Optimized Viewport
Tailored handheld viewport prioritizing the core KPI blocks and immediate class filters cleanly for responsive administrative tracking outside the desktop workstation.

Screenshot 2026-06-16 160236.png

📂 Repository Structure & How to Run
Student-Performance-Behavior-Analytics.pbix - Core Power BI project file with the fully established data model, complete visual layout settings, and DAX calculations.

README.md - Comprehensive project overview and design brief.
