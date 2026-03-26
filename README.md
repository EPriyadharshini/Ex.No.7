# Exno.7-Develop a prompt-based application tailored to their personal needs, fostering creativity and practical problem-solving skills while leveraging the capabilities of large language models.

# Date:20-3-2026
# Register no.212223230159

# Aim

To develop a prompt-based application using ChatGPT to organize daily tasks and demonstrate progression from simple prompts to advanced prompt designs.

# AI Tools Required
ChatGPT
Any browser (Chrome / Edge / Firefox)
Optional: Python / Command Line (for simulation)

# Explanation

A prompt-based application uses Large Language Models (LLMs) like ChatGPT to perform tasks through structured prompts. These prompts guide the AI to behave like a personal assistant that helps manage daily tasks, schedule reminders, suggest wellness tips, and answer queries.

# Prompt

"Design a personal productivity assistant that can help manage daily tasks, schedule reminders, suggest wellness tips, and answer general queries. The assistant should interact using natural language and be adaptable to the user's changing preferences over time."

# Procedure:
1. Define the core requirements of a personal productivity assistant.
2. Identify and construct appropriate prompts for each task using an LLM (e.g., ChatGPT).
3. Simulate natural user interaction through a simple interface or command-line system.
4. Collect feedback or inputs from users and adapt responses accordingly.
5. (Optional) Integrate basic memory to simulate preference adaptation.
   
# EXPECTED OUTPUT: 
Output (Example Response by LLM):
Personal Productivity Assistant Features:
1. Daily Task Manager:
o Accept tasks via natural language (e.g., "Remind me to call mom at 6 PM").
o Organize tasks by priority and deadline.
o Provide daily summaries and pending items.
2. Smart Scheduler:
o Schedule events and set reminders using contextual understanding.
o Notify user of overlapping appointments or free time slots.
3. Wellness Tips Generator:
o Suggest daily wellness advice (hydration, exercise, screen-time breaks).
o Adapt suggestions based on past user preferences and responses.
## App Requirements:
## Core Features:
Add daily income and expenses (with description, amount, category, and date)
View total balance (income – expenses)
Categorized spending summary (Food, Travel, Utilities, etc.)
Visualize expenses using charts (pie or bar)
Option to filter records by date or category
## Tech Stack:
Frontend: React (with Tailwind CSS or Bootstrap for styling)
Backend: Node.js with Express
Database: MongoDB (for persistent data storage)
## Frontend Requirements:
Dashboard to display total income, total expenses, and remaining balance
Form to add new transactions (income or expense)
Table or card layout to display transaction history
Chart visualization (use Recharts or Chart.js)
## Backend Requirements:
## RESTful API endpoints:
POST /transactions → Add new transaction
GET /transactions → Get all transactions
GET /summary → Get summarized data (totals per category)
DELETE /transactions/:id → Delete a transaction
## Bonus Features (optional):
Authentication (JWT-based login/signup)
Dark mode toggle
Export monthly report as PDF/CSV
## UI/UX Design Goals:
Clean and minimal layout
Use soft shadows, rounded corners, and modern typography
Mobile-friendly (responsive for all screens)
## Functional Flow:
User opens dashboard → sees balance and summary
User adds income or expense → updates dashboard instantly
Chart auto-updates to show category-wise spending
User can delete or filter transactions by category/date
# Example Applications
1. Study Time Scheduler
Prompt

"Create a study schedule for exams with 3 subjects"

Output

Morning

Data Structures (2 hours)

Afternoon

Java Programming (2 hours)

Evening

Probability (1.5 hours)

2. Project Task Breakdown
   
Prompt

"Break down my AI project into tasks"

Output

Phase 1

Research
Dataset Collection

Phase 2

Model Development
Testing

Phase 3

Documentation
Presentation
3. Personal Budget Manager
Prompt

"Create a monthly budget for student"

Output

Income

Pocket Money: ₹5000

Expenses

Food: ₹2000
Travel: ₹1000
Study Materials: ₹1000
Savings: ₹1000
4. Travel Itinerary Planner
Prompt

"Plan a 2-day trip to Ooty"

Output

Day 1

Botanical Garden
Ooty Lake
Doddabetta Peak

Day 2

Tea Museum
Rose Garden
Shopping
Personal Productivity Assistant Features
1. Daily Task Manager
Accept tasks using natural language
Organize tasks
Show pending tasks
2. Smart Scheduler
Set reminders
Detect overlapping events
Suggest free time
3. Wellness Tips Generator
Hydration reminders
Exercise suggestions
Screen break alerts

## Expected Output:
Generate full code (frontend + backend), including:
React components for Dashboard, AddTransaction, SummaryChart, and HistoryList
Express.js backend with routes and MongoDB schema
Instructions on how to run the app locally
Optional: Suggest deployment steps on Render/Netlify
OUTPUT :

# Login Page:
<img width="1322" height="893" alt="Screenshot 2025-11-10 091407" src="https://github.com/user-attachments/assets/17fcd32d-bfc7-4b08-a67d-4f5212981dc0" />

# Budget Manager:
<img width="1907" height="945" alt="Screenshot 2025-11-10 091516" src="https://github.com/user-attachments/assets/8aeebd1c-14b3-4926-bf69-6a656e1886e8" />


# Result: 
The lab exercise resulted in the creation of a prototype concept for a personal assistant powered by large language models. Students were able to:
 Understand how to tailor LLM prompts to real-life applications.
 Foster creativity by designing features suited to their personal or academic lives.
 Learn prompt engineering techniques for optimal interaction with AI tools.
 Experience the versatility and utility of generative AI in solving everyday problems.
