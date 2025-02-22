# EduTech Student Performance Dashboard & Report Generator

## Project Overview

EduTech Student Performance Dashboard & Report Generator is a comprehensive solution designed to automate the analysis of student performance data and simplify the generation of official report cards. Tailored for educators in Nigeria and Africa, this tool:
- **Automates Calculations:** Computes subject totals, overall totals, averages, ranks, and letter grades from raw student data.
- **Generates AI-Powered Feedback:** Uses the Groq API to produce personalized, concise performance summaries for each student.
- **Provides Interactive Visualizations:** Features charts that display overall grade distribution, highlight top-performing students, and identify those needing extra support.
- **Creates Professional Reports:** Generates individual PDF report cards stored in teacher-specific folders.
- **Offers Customization:** Allows teachers to personalize header/footer texts, select a logo, and choose a theme color.

## Problem Statement

Manual processing of student performance data is time-consuming and error-prone. Teachers often struggle with calculating scores, ranking students, and generating official report cards, while also finding it difficult to provide actionable insights. This project aims to:
- **Automate Data Processing** to eliminate tedious manual calculations.
- **Enhance Accuracy** and consistency in report generation.
- **Deliver Actionable Insights** through AI-generated feedback and interactive visualizations.
- **Streamline Administrative Tasks** so educators can focus more on teaching.

## Market Value & Startup Opportunity

- **EdTech Growth:** With the global EdTech market on the rise and increasing digital adoption in Africa, there's strong demand for innovative educational tools.
- **Efficiency Gains:** Automating report generation reduces administrative overhead and saves valuable time.
- **Scalable Business Model:** Potential revenue streams include SaaS subscriptions, freemium models with premium features, and licensing partnerships with educational institutions.

## Features

- **File Upload & Storage:** Upload Excel files containing student data; files are stored in teacher-specific folders.
- **Automated Calculations:** Calculates subject totals, overall averages, rankings, and assigns letter grades.
- **AI-Powered Feedback:** Generates concise (50 words or less) performance summaries using the Groq API.
- **Interactive Dashboard:** Visualize data with charts for grade distribution, top/bottom performers, and subject trends.
- **PDF Report Generation:** Automatically creates and stores professional report cards.
- **Customization Options:** Personalize reports with custom header/footer, logo, and theme color.
- **Download Options:** Download processed data as CSV and charts as PNG files.

## Tech Stack

- **Programming Language:** Python 3.13.1
- **GUI Framework:** Tkinter
- **Data Processing:** Pandas
- **PDF Generation:** FPDF
- **Charting:** Matplotlib
- **AI Integration:** Groq API

## Installation & Usage

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/yourusername/edutech-report-generator.git
   cd edutech-report-generator
   Create the Virtual Environment: python -m venv venv
   Activate the Virtual Environment: venv\Scripts\activate
   ```

2. **Install Dependencies:**
   ```bash
   pip install -r requirements.txt
   ```
3. **Set Environment Variables:**
   Set the `GROQ_API_KEY` in your system:
   - **Windows:**  
     ```bash
     set GROQ_API_KEY=your_api_key_here
     ```
   - **macOS/Linux:**  
     ```bash
     export GROQ_API_KEY=your_api_key_here
     ```

4. **Run the Application:**
   ```bash
   python app.py
   ```


5. **Using the Application:**
   - **Teacher Name:** Enter your name to create a dedicated folder for your reports.
   - **Customization:** Use the **Settings** button to set a custom header, footer, logo (small size), and theme color.
   - **File Upload:** Select your Excel file containing student data, use the sample here....
   - **Filtering:** Optionally filter by student IDs.
   - **Report Generation:** The application automatically processes the data and generates PDF report cards in your teacher-specific folder.
   - **Charts:** View interactive charts for top/bottom students and subject trends, with options to download them as PNG files.
   - **Folder Access:** Use the **Open Teacher Folder** button to open the folder containing your generated reports.

## Future Enhancements

- **Advanced Analytics:** Incorporate detailed performance trends and predictive insights.
- **Cloud Integration:** Transition to a web-based platform for multi-user access.
- **Mobile Support:** Develop a mobile version for on-the-go access.
- **Automated Notifications:** Add email notifications for sending report cards.
- **Enhanced Customization:** Expand personalization options for report layouts and branding.

## Team Information

- **Team Name:** [Your Team Name]
- **Team Members:**
  - **[Name 1]:** Project Lead, Software Developer
  - **[Name 2]:** Data Processing & API Integration Specialist
  - **[Name 3]:** UI/UX Designer & Front-End Developer

## Live Demo

*(If applicable, include a link to a live demo or a video demonstration.)*

## Conclusion

EduTech Student Performance Dashboard & Report Generator is designed to empower educators by automating administrative tasks, reducing errors, and providing actionable insights through AI and data visualization. This solution supports quality education by enabling teachers to focus on improving student outcomes. 

