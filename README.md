# ⚡ Study Mood Assistant — Your Burnout-Free Learning Friend

An interactive, responsive study workspace designed with a sleek **Obsidian Black & Cyber Amber** dashboard layout. Instead of forcing students through rigid structures, this application actively checks in on their emotional state and energy levels to reshape their workload in real-time.

---

## 💡 What Problem Does This Solve?
Traditional digital learning hubs are cluttered, text-heavy, and completely ignore how a student feels. This leads to information overload and fast burnout. 

Our app bridges this gap with a human-first approach: it translates the user's focus levels and frustrations into a tailored, easy-to-digest checklist that builds confidence through small, manageable wins.

---

## ✨ Working Features & Architecture

The ecosystem consists of three highly connected pages stored in a single folder:

### 1. The Main Dashboard (`index.html`)
* **AI Mood Detector:** A smart feedback area that reads direct user inputs (e.g., typing *"I'm stressed"* or *"I'm stuck"*) to instantly understand the student's emotional state.
* **Friendly Interface:** Built using simple, human English rather than stiff, robotic jargon to reduce academic pressure.
* **Live Workspace Adjuster:** Updates the interface's advice messages and stress metric indicators dynamically based on configuration settings.

### 2. Adaptive Study Plan (Right Sidebar)
* **Fluid Step Generator:** Swaps dense task objectives out for simple targets (like *"Watch a 2-minute video"* or *"Take a water break"*) the moment low energy or high stress is detected.
* **Custom Task Injector:** Allows students to manually type and add their own sub-questions or custom targets to the active timeline with a single click.

### 3. Deep-Dive Focus & Logs
* **Lesson Room (`lesson.html`):** A clean space focused entirely on learning content, equipped with a personal scratchpad for tracking quick summary notes.
* **Past Activity Tracker (`history.html`):** A history log displaying analytical session records, past mood trends, and specific adjustments made by the application.

---

## 🛠️ Built With
* **HTML5 & Vanilla JavaScript** — Powers the dynamic state-switching and mood deduction logic.
* **Tailwind CSS Engine v4** — Delivers a fluid, true-black dark environment.
* **Lucide Icons** — Provides a clean, minimalist visual layout.

---

## 🚀 How to Run the App Locally
1. Download or clone this repository.
2. Keep `index.html`, `lesson.html`, and `history.html` together inside the same folder.
3. Simply double-click **`index.html`** to run the complete platform instantly inside any web browser (Chrome, Safari, Edge)—no setup or server installations needed!
