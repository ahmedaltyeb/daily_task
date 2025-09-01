##############################################

Interactive Professional Dashboard
##############################################

Overview
This project is an interactive single-page application (SPA) designed to be a personal assistant for planning and managing daily and weekly tasks. The application is built to be a smart productivity tool, integrating AI features to help users break down large goals, prioritize tasks, and receive motivational summaries.

The app is developed entirely using HTML, Tailwind CSS, and JavaScript, relying on Firebase Firestore as a real-time cloud database.

Key Features
Dynamic Task Management: Add, edit, and delete tasks with instant saving to the database.

Multi-Language Support: A full UI that supports both Arabic and English with seamless text direction switching (RTL/LTR).

Light & Dark Mode: Ability to switch between a professional light mode and an eye-friendly dark mode, with user preferences saved.

Interactive Dashboard: View daily tasks with immediate visual analysis using charts (Chart.js).

AI Features (via Google Gemini API):

Smart Task Generator: Breaks down high-level goals into actionable sub-tasks.

Priority Assistant: Automatically suggests task priorities based on their content.

Motivational Summary Generator: Creates encouraging text based on completed tasks.

Integrated Notes System:

Ability to add and edit detailed notes for each task.

A daily journal to save general thoughts and texts for each day.

Professional Reports: Generate detailed weekly and monthly reports and download them as high-quality PDFs.

Instant Feedback: Toast notifications to confirm all save, update, and delete operations.

Responsive Design: A user interface that smoothly adapts to all screen sizes, from mobile to desktop.

Tech Stack
Frontend:

HTML5

Tailwind CSS

JavaScript (ES6+)

Backend:

Google Firebase - Firestore (Real-time NoSQL Database)

Cloud Services:

Firebase Functions (as a secure proxy for API calls)

APIs:

Google Gemini API

Additional Libraries:

Chart.js (for data visualization)

jsPDF & html2canvas (for PDF generation)

Setup and Running the Project
Clone the repository: git clone https://github.com/your-username/daily_task.git

Set up Firebase:

Create a new project on Firebase.

Create a new web app to get your firebaseConfig object.

Replace the placeholder firebaseConfig in the index.html file with your own.

Enable the Firestore Database service in your project.

Set up AI Features (Advanced):

Get an API key from Google AI Studio.

Follow the guide to set up a Firebase Function as a secure proxy. This is essential to protect your API key.

Run:

Open the index.html file in any modern web browser.

This project was developed as a practical tool to apply modern web development concepts, including interaction with cloud databases and the integration of AI services.
