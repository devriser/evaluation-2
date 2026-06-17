# 💬 Technical Assessment: Real-Time Chat Application (React Native)

Welcome to the **devriser** technical assessment! This coding challenge is designed to evaluate your engineering skills in React Native, focusing on state management, UI/UX implementation, real-time data handling, and backend synchronization.

---

## 🕹️ Application Concept & Core Features

The goal is to build a fully functional, highly responsive, and visually polished real-time chat application. The application should handle seamless messaging between two users with modern UI feedback loops.

1. **User Interaction & Flow:**
   * Implement a mechanism to simulate or switch between **two distinct users** in a shared conversation thread.
   * Include a live **Online Status Indicator** that visually changes based on whether the counterpart user is active.
2. **Real-Time Capabilities:**
   * **Instant Messaging:** Messages sent by User A must update instantly on User B's screen without manual refreshes or pulling to reload.
   * **Typing Indicators (Bonus):** Show a visual cue (e.g., "User is typing...") when a message is actively being drafted.
3. **UI/UX Excellence:**
   * A clean, modern chat interface with clear distinct alignments and colors for sent vs. received messages.
   * Clear timestamps appended to individual text bubbles.
   * Flawless native layouts using `KeyboardAvoidingView` (or similar) to ensure the message input container is never blocked or obscured by the device's native keyboard.

---

## 🛠️ Technical Guidelines & Specs

* **Frontend:** Built using React Native (Expo or bare React Native CLI are both welcome). You are free to choose your preferred styling library (Tailwind/NativeWind, StyleSheet, etc.) and state management engine.
* **Backend Integration (Highly Valued):** * Deploying a lightweight backend engine (e.g., Node.js + Socket.io) to orchestrate live socket channels is highly preferred.
  * Alternatively, utilizing integrated Backend-as-a-Service (BaaS) platforms like Firebase Firestore or Supabase Realtime is also fully acceptable.
  * *Note: If a backend layer is omitted, you must robustly mimic asynchronous live stream events locally.*

---

## 📦 Submission Requirements

To proceed to the interview stage, your final repository **must** include the following deliverables:

1. **Standalone APK File:** You must compile and attach a working, installable **`.apk`** build of the application. Submissions that only work via local development environments or require us to boot up a local metro bundler will be disqualified.
2. **Source Code:** Provide a link to your public GitHub repository. Code architecture should be clean, modular, properly typed (if using TypeScript), and backed by a logical commit history.
3. **Setup Documentation:** A clear markdown section detailing how to spin up your frontend (and backend, if applicable) locally, including any environmental variables required.
4. **Video Demonstration:** Include a short screen recording (`.mp4` or GIF) directly inside the repository showing the messaging flow working simultaneously between both users (ideally running two emulators side-by-side or dual windows).

---

## 📊 Evaluation Criteria

Your submission will be reviewed against:
* **Real-Time Synchronization:** Reliable, duplicate-free message delivery across sockets.
* **UI/UX Polish:** Accurate padding, layout transitions, and seamless keyboard management.
* **Code Craftsmanship:** Clean separation of concerns, optimized re-renders, and proper cleanup of persistent socket listeners.

Good luck! We look forward to evaluating your build. 🚀

---

## ⏳ Deadline & Timeline

* **Submission Window:** You have **7 days** from the receipt of this challenge to submit your complete repository and deliverables.
* **Hard Deadline:** **Thursday, June 25, 2026** at **11:59 PM UTC**.
* **Extensions:** We respect your time and existing commitments. If you need a reasonable extension due to work or personal circumstances, please request it at least **24 hours before** the deadline. Unannounced late submissions will not be reviewed.
