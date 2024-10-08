# Student Feedback Sentiment Analysis Bot

### Overview

This repository contains the solution for automating the processing of student feedback through sentiment analysis using **UiPath StudioX**. The bot automatically reads student feedback from Excel files, analyzes the sentiment (positive, neutral, or negative), and generates a summary report to help universities easily understand feedback trends.

---

## Problem Statement

Universities often collect feedback from students regarding courses, professors, and learning experiences. Manually analyzing this feedback is time-consuming and difficult to quantify. The goal is to develop an automation bot that:
1. Automatically processes student feedback from a structured document (Excel, PDF, or Word).
2. Analyzes the sentiment of the feedback (positive, neutral, or negative) using pre-trained sentiment analysis models.
3. Generates a summary report categorizing feedback based on sentiment to provide insights.

---

## Solution

We implemented a solution using **UiPath StudioX** and its integrated tools for sentiment analysis and document processing.

### Features:
- **Automated Feedback Extraction**: Reads feedback from Excel files.
- **Sentiment Analysis**: Utilizes a sentiment analysis model to classify feedback as positive, neutral, or negative.
- **Summary Report**: Automatically generates a report based on sentiment results, giving universities clear insights into student opinions.

---

## Getting Started

### Prerequisites:
- **UiPath StudioX**: Ensure UiPath StudioX is installed. You can download it [here](https://www.uipath.com/product/studiox).
- **Excel Files with Feedback**: The bot reads feedback data from an Excel file.

### Installation:
1. Clone this repository using:
   ```bash
   git clone https://github.com/your-username/student-feedback-sentiment-analysis.git
   ```
2. Open the project in **UiPath StudioX**.

### Workflow Overview:
- **Read Feedback**: The bot reads student feedback from an Excel file.
- **Analyze Sentiment**: Feedback is passed to a pre-trained sentiment analysis model (available via UiPath AI Fabric or external APIs).
- **Generate Report**: The bot generates a report that categorizes feedback based on sentiment.

---

## How to Use

1. **Prepare Input Files**:
   - Place the student feedback in an Excel file with feedback text in a column (e.g., Column A: Feedback).

2. **Run the Bot**:
   - Open the project in **UiPath StudioX**.
   - Modify the path to your Excel file if necessary.
   - Run the bot to process the feedback.

3. **Output**:
   - The bot will generate a summary report (in Excel or PDF) with sentiment analysis for each piece of feedback.
     
## Contributing

We welcome contributions! Feel free to fork this repository and submit a pull request.

---

## Contact

For any issues or queries, feel free to reach out to(queenssnapping@gmail.com).

---
