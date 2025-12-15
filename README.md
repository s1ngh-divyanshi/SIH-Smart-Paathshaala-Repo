# 🏫 Smart Paathshaala Prototype

## 💡 Bridging the Rural-Urban Education Gap on 2G/3G

[cite_start]This repository contains the prototype for **Smart Paathshaala**, a virtual classroom designed to deliver high-quality, structured academic content to students in rural colleges struggling with **poor internet connectivity (2G/3G)** and a **lack of expert faculty**[cite: 24, 26].

[cite_start]Developed for the **Smart India Hackathon (SIH) 2025** under the **Smart Education** theme[cite: 3, 4].

| Detail | Description |
| :--- | :--- |
| **SIH Problem ID** | [cite_start]25101 [cite: 2] |
| **Problem Title** | [cite_start]Remote classroom for Rural colleges [cite: 3] |
| **Team** | [cite_start]Code Illuminators [cite: 7] |
| **Status** | Prototype / Proof of Concept |

---

## ✨ Key Features

Smart Paathshaala is engineered to be highly accessible and content-focused:

* [cite_start]**Low-Bandwidth Access:** Creates a virtual classroom environment that works efficiently even on 2G/3G networks[cite: 26].
* [cite_start]**Structured Learning:** Syllabus is neatly divided into **Mid-Sems** and **End-Sem** categories[cite: 36, 68, 69, 70].
* [cite_start]**Content Library:** Students can access PDFs, PPTs, audio lectures (Opus codec for low-data use [cite: 33, 62][cite_start]), and previous papers, all aligned with the NEP structure[cite: 33, 34].
* [cite_start]**Interactive Practice:** Includes a **chat box** for doubt clearing and **timed quizzes** for confident preparation[cite: 21, 78, 79].
* [cite_start]**Secure Uploads:** Only verified faculty accounts, authenticated by the institution, can upload content, ensuring authenticity[cite: 29, 97].
* [cite_start]**Adaptive Connectivity:** The system can automatically switch to **audio-only mode** to maintain class continuity during network instability[cite: 86].

---

## 🛠️ Technical Approach (Planned Full Stack)

This prototype utilizes the following technologies, with a plan for a full-scale deployment leveraging low-data and secure infrastructure:

| Component | Technology | Role |
| :--- | :--- | :--- |
| **Front End** | [cite_start]HTML, CSS, JavaScript **(with React.js)** [cite: 45] | User interface, responsive design, and interactivity. |
| **Back End** | [cite_start]Node.js / Java [cite: 46] | Application logic, user authentication, and API handling. |
| **Database** | [cite_start]PostgreSQL [cite: 50] | Structured data storage for user accounts, content metadata, and quiz results. |
| **Datastreams** | [cite_start]Opus codec [cite: 61, 62] | Highly efficient compression for audio lectures to ensure low-bandwidth streaming. |
| **Cloud** | [cite_start]AWS / Google Cloud [cite: 63, 64] | Scalable hosting and storage for all course materials. |

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

[cite_start]The application is structured around dedicated workflows for teachers and students[cite: 48, 65]:

* [cite_start]**Teachers:** Log in $\rightarrow$ View List of Courses $\rightarrow$ Select Midsem/Endsem Category $\rightarrow$ Upload Content[cite: 47, 51, 52, 55].
* [cite_start]**Students:** Log in $\rightarrow$ View List of Subjects $\rightarrow$ Select Midsem/Endsem Category $\rightarrow$ Access Syllabus, PDFs, PPTs, Audios, Quizzes, and Chat System[cite: 66, 67, 71, 72, 68, 69, 70, 74, 75, 76, 77, 78, 79].

---

## 🤝 Contribution

[cite_start]This project was developed by **Code Illuminators** for SIH 2025[cite: 7].
