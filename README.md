# Exno.7-Develop a prompt-based application tailored to their personal needs, fostering creativity and practical problem-solving skills while leveraging the capabilities of large language models.

# Name: KAILASH KUMAR S
# Register no: 212223220041
# Aim: To develop a prompt-based application using ChatGPT - To demonstrate how to create a prompt-based application to organize daily tasks, showing the progression from simple to more advanced prompt designs and their corresponding outputs.

# AI Tools Required: 

Excellent — that’s a clear and practical project idea!
Below is a **complete, well-structured explanation and demonstration** for your topic:

# **Experiment Title:**

**Developing a Prompt-Based Application using ChatGPT for a Study Time Scheduler**

## **Aim:**

To demonstrate how to create a prompt-based application using ChatGPT to organize and schedule study tasks, showing the progression from **simple prompts** to **advanced prompt designs** and their corresponding outputs.

## **Concept Overview:**

A **prompt-based application** uses carefully designed instructions (prompts) to guide ChatGPT in performing specific tasks — here, it acts as a **Study Time Scheduler**.
By improving prompt design step by step, we can make the system more intelligent, structured, and user-friendly.

## **Stages of Development**

### **Stage 1 — Simple Prompt**

**Objective:** Create a basic list of study activities.

**Prompt Example:**

> “Help me organize my study tasks for today. I need to study Math, Physics, and English.”

**Sample Output:**

```
Here’s your study plan:
1. Study Math
2. Study Physics
3. Study English
```

**Learning Outcome:**
ChatGPT can generate a simple, direct response without additional structure.

### **Stage 2 — Structured Prompt**

**Objective:** Provide more detail — include time slots and durations.

**Prompt Example:**

> “You are my study assistant. Create a time schedule for the following subjects:

> * Math
> * Physics
> * English
>   I have 6 hours to study today. Divide my time efficiently.”

**Sample Output:**

```
 Study Time Schedule
-------------------------
9:00–11:00 AM — Math (2 hours)
11:15 AM–1:15 PM — Physics (2 hours)
2:00–4:00 PM — English (2 hours)
```

**Learning Outcome:**
Structured prompts provide more organized and practical schedules.

### **Stage 3 — Parameterized Prompt**

**Objective:** Introduce variables to make the prompt reusable and adaptable.

**Prompt Template:**

> “You are an intelligent study planner. Based on the following details, create a daily study schedule.
> Subjects: {{subjects}}
> Available hours: {{hours}}
> Preferences: {{preferences}} (e.g., more time for difficult subjects, include short breaks)
> Output: A clear table with time, subject, and notes.”

**Example Input:**

```
subjects = ["Math", "Physics", "Computer Science", "English"]
hours = "8 AM to 6 PM"
preferences = "More focus on Math and short breaks after each subject"
```

**Sample Output:**

| Time           | Subject          | Notes                        |
| -------------- | ---------------- | ---------------------------- |
| 8–10 AM        | Math             | High priority subject        |
| 10–10:15 AM    | Break            | Refresh your mind            |
| 10:15–12:15 PM | Physics          | Revise important formulas    |
| 1–3 PM         | Computer Science | Practice coding problems     |
| 3–3:15 PM      | Break            | Take a short walk            |
| 3:15–5 PM      | English          | Reading and writing practice |

**Learning Outcome:**
Parameterized prompts create flexibility and make prompts suitable for app integration.

### **Stage 4 — Multi-Prompt Workflow**

**Objective:** Simulate a complete Study Planner app using multiple steps.

**Prompt Sequence:**

1. **Prompt 1 – Input Collection:**

   > “List the subjects you plan to study today.”

2. **Prompt 2 – Schedule Creation:**

   > “Now, create a detailed schedule for these subjects, considering equal time and short breaks.”

3. **Prompt 3 – Motivation:**

   > “Give me a motivational message to help me stay focused on my study plan.”

**Combined Output:**

```
 Study Plan for Today
-------------------------
8–10 AM: Math  
10:15–12:15 PM: Physics  
1–3 PM: Computer Science  
3:15–5 PM: English  

 Motivation:
“You don’t need to study harder — just smarter and consistently. Stay focused!”
```

**Learning Outcome:**
Demonstrates **multi-step prompting** that mimics real application flow.

### **Stage 5 — Advanced System Prompt (App-Like Design)**

**Objective:** Use a **system prompt** and **structured output** (like JSON) for integration with applications.

**System Prompt Example:**

> **System Role:** You are a smart study scheduler that organizes students’ study time efficiently. Always output the schedule in JSON format.

**User Prompt:**

> “Subjects: Math, Physics, Computer Science, English
> Available hours: 8 AM to 8 PM
> Preference: Focus more on difficult subjects and include 15-minute breaks.”

**Sample JSON Output:**

```json
{
  "study_schedule": [
    {"time": "8–10 AM", "subject": "Math", "priority": "High"},
    {"time": "10–10:15 AM", "subject": "Break", "priority": "Rest"},
    {"time": "10:15–12:15 PM", "subject": "Physics", "priority": "High"},
    {"time": "1–3 PM", "subject": "Computer Science", "priority": "Medium"},
    {"time": "3–3:15 PM", "subject": "Break", "priority": "Rest"},
    {"time": "3:15–5 PM", "subject": "English", "priority": "Low"}
  ],
  "summary": "Morning hours are dedicated to challenging subjects. Maintain focus and take proper breaks."
}
```

**Learning Outcome:**
This demonstrates **advanced prompt engineering** suitable for backend integration in chatbots or web applications.

## **Conclusion**

Through this experiment, we successfully demonstrated how prompt engineering can be used to develop a **ChatGPT-based Study Time Scheduler**.
By progressively refining prompts:

* Simple prompts → produce direct responses.
* Structured and parameterized prompts → generate organized outputs.
* Advanced system prompts → enable automation and app integration.

Hence, prompt-based applications can act as **intelligent virtual study assistants**, improving productivity and time management for students.

## **Optional Extension (Implementation Idea)**

You can extend this as a mini web or Python app:

* **Frontend (HTML/JS):** Collects subjects, available time, and preferences.
* **Backend (Python/OpenAI API):** Sends prompts to ChatGPT.
* **Output:** Displays a generated study schedule table.

# Explanation: 
Prompt:
"Design a personal productivity assistant that can help manage daily tasks, schedule reminders, suggest wellness tips, and answer general queries. The assistant should interact using natural language and be adaptable to the user’s changing preferences over time."
Procedure:
1. Define the core requirements of a personal productivity assistant.
2. Identify and construct appropriate prompts for each task using an LLM (e.g., ChatGPT).
3. Simulate natural user interaction through a simple interface or command-line system.
4. Collect feedback or inputs from users and adapt responses accordingly.
5. (Optional) Integrate basic memory to simulate preference adaptation.
EXPECTED OUTPUT: - (attached the drive link)
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



# Result: 
The lab exercise resulted in the creation of a prototype concept for a personal assistant powered by large language models. Students were able to:
 Understand how to tailor LLM prompts to real-life applications.
 Foster creativity by designing features suited to their personal or academic lives.
 Learn prompt engineering techniques for optimal interaction with AI tools.
 Experience the versatility and utility of generative AI in solving everyday problems.
