Job Application Assistant
Overview
This is a personalized, single-page web application designed to streamline your job application and interview preparation process. Instead of a manual, scattered approach, this tool helps you centralize your application data, generate tailored application drafts, and prepare for interviews with confidence.

The app uses your browser's local storage to save all your data, ensuring your information is private and accessible only to you. You can host this single HTML file on any static hosting service like GitHub Pages or Netlify.

Features
1. Application Tracker
A simple and effective table to track your applications. You can add new applications and view their status at a glance. Each entry includes the date, company name, job title, and a link to the job posting.

2. Dynamic Draft Generation
Based on your pre-defined CV summary and cover letter template, the app automatically generates a tailored cover letter draft for each new application. It replaces key placeholders like [Company Name] and [Job Title] to save you time and ensure consistency.

3. Interview Prep Assistant
This section is your personal interview playbook. It contains your pre-written, dynamic answers to three core interview questions:

Why [COMPANY NAME]?

Why this [JOB TITLE]/industry?

Why are you qualified?

The app will automatically adjust these answers with the details of your new application, so you can quickly review your talking points before an interview.

How to Get Started
Host the file: Upload the job_application_assistant_with_interview_prep.html file to a static hosting service (e.g., GitHub Pages).

Open the app: Navigate to the live URL in your browser.

Set up your assets: In the "My Application Assets" and "Interview Prep Answers" sections, fill in your CV summary, cover letter template, and dynamic interview responses. The app will save this data automatically.

Generate & Track: Use the "Job Details" form to input information for a new job. Click "Generate & Track Application" to create a draft and add it to your tracker.

How It Works (Technically)
This is a single-page application built with HTML, CSS (using Tailwind CSS), and JavaScript.

Data Storage: All of your data is saved in your browser's localStorage. This means the data is not sent to a server and remains on your machine.

Drafting: The JavaScript code uses a simple find-and-replace function to customize your templates with the details you enter.

User Interface: The UI is designed to be clean and responsive, so it works well on both desktop and mobile devices.

This README gives you and anyone else who might view your project a clear understanding of its purpose and functionality.
