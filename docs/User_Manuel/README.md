# README / User Manual  
**CS3338 Final Project Based on LACPD1**  
*Brian Andrade, Christian Garcia, Haonan Ma, Jared Martinez, Alejandro Vargas*

---

## 1. Project Overview

LACPD1 is a transcript analysis and case management system designed for the Los Angeles County Public Defender’s Office. It utilizes AWS, Box.com, and advanced NLP to assist legal professionals in detecting misconduct and organizing case insights.

---

## 2. Objective Breakdown

- Automate transcript uploading and entity extraction.  
- Enable semantic flagging of police misconduct patterns.  
- Generate searchable legal metadata and insights using NLP.  
- Provide an interactive web interface for attorneys and paralegals.  
- Deploy the solution locally via Docker with cloud integration logic.

---

## 3. Why This Software Matters

Manual legal transcript review is often inefficient, subjective, and prone to error. Our project aims to modernize and accelerate this process through automation, data enrichment, and AI-powered document analysis – making legal defense work more efficient and just.

---

## 4. How to Access or Download the System

To run the system locally:

1. Clone the repository:  
   ```
   git clone https://github.com/brinstussymethod/CS3338-Final-Project
   ```

2. Navigate to the project directory and build with Docker:  
   ```
   cd CS3338-Final-Project  
   docker compose up --build  
   ```

3. Open your browser and go to:  
   [http://localhost:3000](http://localhost:3000)

---

## 5. Jira Link

All tasks, sprint assignments, and issue tracking are managed on Jira:  
[https://bandra.atlassian.net/jira/projects?page=1&sortKey=name&sortOrder=ASC&types=software%2Cbusiness](https://bandra.atlassian.net/jira/projects?page=1&sortKey=name&sortOrder=ASC&types=software%2Cbusiness)

---

## 6. User Roles

- **Attorneys**: View flagged transcripts, generate reports.  
- **Paralegals**: Upload documents, assist in review.  
- **Admins**: Configure roles, monitor system performance.

---

## 7. FAQs

**Q: What files are supported?**  
A: PDF, DOCX. Scanned images are processed via OCR.

**Q: Is the system secure?**  
A: Yes, compliant with CJIS standards and encrypted throughout.

**Q: What happens if a transcript is flagged incorrectly?**  
A: Users can override AI results and manually update case flags.

**Q: Does the system store any sensitive user data?**  
A: Only metadata relevant to case organization is stored; no personal identifiers are retained.

**Q: Is Docker required to run the project?**  
A: It is recommended for consistent local deployment, but manual setup is also possible.

---
