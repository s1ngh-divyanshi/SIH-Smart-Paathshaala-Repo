# 🏫 Smart Paathshaala Prototype

## 💡 Bridging the Rural-Urban Education Gap on 2G/3G

This repository contains the prototype for **Smart Paathshaala**, a virtual classroom designed to deliver high-quality, structured academic content to students in rural colleges struggling with **poor internet connectivity (2G/3G)** and a **lack of expert faculty**.

Developed for the **Smart India Hackathon (SIH) 2025** under the **Smart Education** theme.

| Detail | Description |
| :--- | :--- |
| **SIH Problem ID** | 25101 |
| **Problem Title** | Remote classroom for Rural colleges |
| **Team** | Code Illuminators |
| **Status** | Prototype / Proof of Concept |

---

## ✨ Key Features

Smart Paathshaala is engineered to be highly accessible and content-focused:

* **Low-Bandwidth Access:** Creates a virtual classroom environment that works efficiently even on 2G/3G networks.
* **Structured Learning:** Syllabus is neatly divided into **Mid-Sems** and **End-Sem** categories.
* **Content Library:** Students can access PDFs, PPTs, audio lectures (Opus codec for low-data use), and previous papers, all aligned with the NEP structure.
* **Interactive Practice:** Includes a **chat box** for doubt clearing and **timed quizzes** for confident preparation.
* **Secure Uploads:** Only verified faculty accounts, authenticated by the institution, can upload content, ensuring authenticity.
* **Adaptive Connectivity:** The system can automatically switch to **audio-only mode** to maintain class continuity during network instability.

---

## 🛠️ Technical Approach (Planned Full Stack)

This prototype utilizes the following technologies, with a plan for a full-scale deployment leveraging low-data and secure infrastructure:

| Component | Technology | Role |
| :--- | :--- | :--- |
| **Front End** | HTML, CSS, JavaScript **(with React.js)** | User interface, responsive design, and interactivity. |
| **Back End** | Node.js / Java | Application logic, user authentication, and API handling. |
| **Database** | PostgreSQL | Structured data storage for user accounts, content metadata, and quiz results. |
| **Datastreams** | Opus codec | Highly efficient compression for audio lectures to ensure low-bandwidth streaming. |
| **Cloud** | AWS / Google Cloud | Scalable hosting and storage for all course materials. |

---

## 🚀 Getting Started

To run the current prototype:

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/s1ngh-divyanshi/SIH-Smart-Paathshaala-Repo.git](https://github.com/s1ngh-divyanshi/SIH-Smart-Paathshaala-Repo.git)
    ```
2.  **Navigate to the project directory:**
    ```bash
    cd SIH-Smart-Paathshaala-Repo
    ```
3.  **Open the file:**
    Open the `prototype_sih.html` file directly in your web browser.

---

## 📂 Project Workflow Overview

The application is structured around dedicated workflows for teachers and students:

* **Teachers:** Log in $\rightarrow$ View List of Courses $\rightarrow$ Select Midsem/Endsem Category $\rightarrow$ Upload Content.
* **Students:** Log in $\rightarrow$ View List of Subjects $\rightarrow$ Select Midsem/Endsem Category $\rightarrow$ Access Syllabus, PDFs, PPTs, Audios, Quizzes, and Chat System.

---

## 🤝 Contribution

This project was developed by **Code Illuminators** for SIH 2025.
