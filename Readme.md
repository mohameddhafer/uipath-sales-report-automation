# 📊 Executive Sales Reporting Automation with UiPath

<p align="center">

![UiPath](https://img.shields.io/badge/UiPath-RPA-orange)
![Excel](https://img.shields.io/badge/Microsoft-Excel-success)
![PowerPoint](https://img.shields.io/badge/Microsoft-PowerPoint-red)
![Automation](https://img.shields.io/badge/Automation-End--to--End-blue)
![Data Visualization](https://img.shields.io/badge/Data-Visualization-purple)
![License](https://img.shields.io/badge/License-MIT-green)

</p>

---

> **Enterprise-grade reporting automation that transforms raw Excel sales data into executive PowerPoint presentations with automated KPI calculation, charts, and business insights.**

---

# 🎥 Demonstration

Refer to Documentation/ to watch the demonstration video.

---

# 📖 Overview

Executive reporting often requires analysts to manually consolidate sales data, calculate KPIs, generate charts, update dashboards, and prepare presentation-ready reports.

This project automates the entire reporting lifecycle using **UiPath**, transforming raw Excel sales data into a professional PowerPoint presentation ready for management review.

The solution automatically:

* Reads sales data
* Calculates key performance indicators (KPIs)
* Performs revenue analysis
* Generates business insights
* Creates charts
* Updates PowerPoint slides
* Produces executive-ready reports

The project demonstrates enterprise automation best practices through modular workflows, reusable components, and structured logging.

---

# 🚀 Features

| Feature                  | Description                                 |
| ------------------------ | ------------------------------------------- |
| 📄 Excel Processing      | Reads and validates sales data              |
| 📊 KPI Calculation       | Calculates business KPIs automatically      |
| 📈 Revenue Analysis      | Computes sales performance metrics          |
| 📉 Performance Tracking  | Measures target achievement                 |
| 🏆 Product Analysis      | Identifies top-performing products          |
| 🌍 Regional Analysis     | Highlights underperforming regions          |
| 💡 Business Insights     | Automatically generates management insights |
| 📑 PowerPoint Automation | Updates presentation templates              |
| 📝 Logging               | Tracks execution progress                   |
| ❗ Exception Handling     | Production-ready automation                 |

---

# 🏗 Solution Architecture

```text
                    SalesData.xlsx
                           │
                           ▼
               ReadExcelData.xaml
                           │
                           ▼
                Validate & Load Data
                           │
                           ▼
               ProcessKPIs.xaml
                           │
                           ▼
            KPI Calculation Engine
                           │
                           ▼
             GenerateInsights.xaml
                           │
                           ▼
        Business Insight Generation
                           │
                           ▼
             FillPresentation.xaml
                           │
                           ▼
        Executive PowerPoint Report
                           │
                           ▼
                     Output Folder
```

---

# 🔄 Workflow

The automation orchestrates the following workflows:

```text
Main.xaml

↓

ReadExcelData.xaml

↓

ProcessKPIs.xaml

↓

GenerateInsights.xaml

↓

FillPresentation.xaml

↓

ExecutiveSalesReport.pptx
```

---

# 📊 KPI Engine

The automation calculates business indicators such as:

* Total Revenue
* Total Sales Target
* Achievement Percentage
* Revenue by Product
* Best Performing Product
* Lowest Performing Region
* Executive Business Insights

---

# 📈 Business Insights

Based on KPI calculations, the automation automatically generates management insights, for example:

* Revenue performance
* Product contribution
* Regional performance

These insights are automatically inserted into the presentation.

---

# 📊 Dynamic Visualizations

The solution generates a professional chart (Revenue by Product) which is automatically populated into the PowerPoint presentation.

---

# 📑 PowerPoint Automation

The automation updates a PowerPoint template by automatically inserting:

* Report Month
* KPI Cards
* Revenue Metrics
* Business Insights
* Regional Performance

The final output is a presentation ready for executive meetings.

---

# 🛠 Technologies

## Automation

* UiPath Studio
* UiPath Excel Activities
* UiPath Presentations Activities
* UiPath System Activities

## Reporting

* Microsoft Excel
* Microsoft PowerPoint

## Programming

* VB.NET

## Design

* Modular Workflow Architecture
* Reusable Components
* DataTables

---

# 📂 Repository Structure

```text
.
├── Assets/
├── Data/
├── Documentation/
├── Output/
├── Workflows/
│   ├── ReadExcelData.xaml
│   ├── ProcessKPIs.xaml
│   ├── GenerateInsights.xaml
│   └── FillPresentation.xaml
│
├── Main.xaml
├── project.json
├── LICENSE
└── README.md
```

---

# ⚙ Configuration

Project resources are stored under the **Data** and **Assets** folders.

Typical configurable items include:

* Input Excel workbook
* PowerPoint template
* Output directory

---

# 📥 Input

The automation expects a structured Excel workbook containing sales information.

Example:

```text
SalesData.xlsx
```

Typical fields:

* Date
* Month
* Product
* Region
* Revenue
* Target

---

# 📤 Output

The automation generates:

```text
KPI_Report_MMM_dd.pptx
```

containing:

* Executive dashboard
* KPI summary
* Revenue analysis
* Product performance
* Regional analysis
* Revenue by Product chart

---

# 📈 Business Benefits

This solution enables organizations to:

* Reduce manual reporting effort
* Improve reporting consistency
* Eliminate repetitive PowerPoint updates
* Produce executive-ready reports within minutes
* Increase reporting accuracy
* Standardize KPI calculations
* Improve decision-making through visual analytics

---

# 🚀 Usage

## Prerequisites

* UiPath Studio
* Microsoft Excel
* Microsoft PowerPoint

## Steps

1. Clone the repository.
2. Open the project in UiPath Studio.
3. Update the input Excel dataset if required.
4. Run `Main.xaml`.
5. Retrieve the generated PowerPoint presentation from the **Output** folder.

---

# 📚 Skills Demonstrated

## Robotic Process Automation

* UiPath
* Excel Automation
* PowerPoint Automation
* Workflow Orchestration

## Data Processing

* KPI Calculation
* Revenue Analysis
* Data Transformation

## Data Visualization

* Executive Dashboards
* Business Reporting

## Software Engineering

* Modular Design
* VB.NET
* Logging
* Exception Handling
* Reusable Components

---

# 📄 License

Copyright © 2026 Mohamed Dhafer HADJ AMOR

This repository is provided for educational and portfolio purposes.

If you reuse this project or any part of it, please ensure compliance with the licenses of UiPath components and third-party packages used by the solution.

---

# 📝 Notes

* This project demonstrates an enterprise reporting automation scenario built with UiPath.
* The solution follows a modular architecture using reusable workflows.
* The generated PowerPoint presentation can be customized by modifying the template and business rules.

---

### Highlights

* End-to-end Excel-to-PowerPoint automation
* Automated KPI calculation
* Revenue analysis
* Executive PowerPoint reporting
* Business insight generation
* Modular workflow architecture
* Structured logging

---

# 👤 Author

## Mohamed Dhafer HADJ AMOR

**Software Engineer | UiPath Certified Professional | Intelligent Automation Developer**

### Areas of Expertise

* UiPath
* Intelligent Automation
* Reporting Automation
* Data Visualization
* Python Automation
* Low-Code Development
* Business Process Automation

### LinkedIn

https://www.linkedin.com/in/mohamed-dhafer-hadj-amor-17a7b1176/
