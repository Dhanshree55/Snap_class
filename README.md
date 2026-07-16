# Class-Snap 📸

A high-performance, lightweight attendance tracking and live classroom management dashboard built natively in Python using Streamlit. This application is engineered with professional software architecture patterns, prioritizing data integrity, decoupled presentation layers, and strict data security protocols.

---

## 🏗️ Architectural Core & Engineering Patterns

* **Centralized State Management:** Implements rigorous multi-layered session-state mapping to enforce transactional safety during runtime client-side updates and eliminate widget collision errors.
* **Decoupled Architecture (Separation of Concerns):** The project is structured with a distinct separation between presentation layouts (`src/ui`, `src/screens`) and operational core workflows (`src/pipelines`).
* **Relational Data Modeling:** Engineered with an explicit schema framework mapping subjects, enrollments, and real-time validation parameters safely to eliminate concurrent state mutation issues.
* **Defensive System Design:** Outfitted with robust backend validation checks to protect computational paths and secure user inputs prior to data persistence stages.

---

## 🛠️ Tech Stack & Dependencies

* **Language:** Python
* **Frontend Dashboard Framework:** Streamlit
* **State Management:** Streamlit Session State & Runtime Trackers
* **Environment Management:** Isolated virtual environment configurations (`venv`)
* **Security & Credentialing:** Enforced local runtime secret parsing (`.streamlit/secrets.toml`)

---
