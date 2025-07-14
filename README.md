## 📢 Campus Alerts – College Event Notifier

### 🎯 Overview

**Campus Alerts** is a simple, one-page web application that helps students stay updated with important campus events like seminars, workshops, and placement drives. The app displays real-time announcements fetched from **Firebase Firestore** and uses **Gemini AI** to generate short, meaningful summaries of each event description.

> Designed as a lightweight prototype to demonstrate how **Google technologies** like Firebase and Gemini API can solve real-world communication problems in college environments.

---

### 🚀 Features

* 🔥 **Event Feed** – Displays upcoming college events in real-time from Firebase
* 🤖 **AI Summarization** – Uses Gemini API to convert long descriptions into quick summaries
* 🌐 **Fully Web-Based** – No login or complex setup needed; works on mobile and desktop
* 🧪 **Minimal & Functional** – Built with just HTML + JavaScript for simplicity and clarity

---

### 🧰 Technologies Used

| Tech                                  | Purpose                                  |
| ------------------------------------- | ---------------------------------------- |
| **Firebase Firestore**                | Stores and retrieves event announcements |
| **Firebase Hosting**                  | Hosts the app publicly online            |
| **Gemini API (via Google AI Studio)** | Generates AI summaries of events         |
| **HTML + JavaScript**                 | Simple frontend for quick prototyping    |

---

### 🛠️ How It Works

1. Events are added to a Firestore collection called `events`
2. The app reads the events on load and displays them
3. Clicking the **"Summarize"** button sends the event description to **Gemini**
4. Gemini returns a short, readable summary shown under the event

---

### 📷 Sample Use Case

> A student checks the app and sees:
> **"AI Workshop on Tuesday – Learn the basics of generative AI from industry experts."**
> Instead of reading a long paragraph, they get the key idea in a click.



