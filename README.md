# Data Visualization Lab

**Name:** Usman Hassan
**Roll No:** 1421-324032
**Course:** Data Visualization Lab, Department of Data Science, Preston University Islamabad (Fall 2026)

This repository contains my lab work for the Data Visualization course. Each lab is in its own folder.

## Labs

| Lab | Folder | Topic |
|---|---|---|
| Lab 01 | [lab01](lab01/) | Environment setup (Google Colab, GitHub), loading data with pandas, first bar chart with Matplotlib, and choosing the right chart type |

## Tools
- Google Colab
- Python (pandas, Matplotlib)
- GitHub
## Lab 02: From a Data File to a Chart with Python and JavaScript

Turned `students_marks.csv` into a bar chart in two ways: with Python + JavaScript in Google Colab, and with Power BI.

**Folder:** [`lab02/`](lab02/)

| File | What it is |
|---|---|
| `bridge.ipynb` | Colab notebook: Tasks 1–6 (pandas summary, JSON, JavaScript questions, SVG chart, comparison) |
| `chart.html` | Average Python by section, drawn with JavaScript as SVG. Opens in Chrome |
| `marks_report.pbix` | Power BI report: Average Python by section, Students card, Section slicer |
| `marks_report.pdf` | PDF export of the Power BI report |

**What I did**
- Loaded the data with pandas and summarised the average of each subject by section, plus each student's average
- Passed the results from Python to JavaScript as JSON (`orient="records"`)
- Used JavaScript (`filter`, `map`, `sort`, `forEach`) in Node.js to answer questions from the JSON
- Drew **Average Python by section** as an SVG bar chart with JavaScript and saved it as a web page
- Built the same chart in Power BI, with the aggregation set to Average instead of Sum

**Tools:** Google Colab, pandas, Node.js, Power BI Desktop  
**AI tools used:** Claude (Anthropic)