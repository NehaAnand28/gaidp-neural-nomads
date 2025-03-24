# 🚀 Project Name

## 📌 Table of Contents
- [Introduction](#introduction)
- [Demo](#demo)
- [Inspiration](#inspiration)
- [What It Does](#what-it-does)
- [How We Built It](#how-we-built-it)
- [Challenges We Faced](#challenges-we-faced)
- [How to Run](#how-to-run)
- [Tech Stack](#tech-stack)
- [Team](#team)

---

## 🎯 Introduction
In the banking sector, regulatory reporting involves compiling and analyzing vast amounts of data to ensure compliance with complex regulatory requirements. This process is traditionally manual and time-consuming, often leading to inefficiencies and potential errors.

Our project addresses this challenge by leveraging Generative AI (LLMs) and unsupervised machine learning techniques to automate data profiling. Our goal was to develop a solution that extracts regulatory instructions, generates profiling rules, and flags anomalous transactions along with the reason. By automating these processes, we aim to enhance operational efficiency, reduce compliance risks, and improve reporting accuracy.

## 🎥 Demo
🔗 [Live Demo](#) (if applicable)  
📹 [Video Demo](#) (if applicable)  
🖼️ Screenshots:

![Screenshot 1](link-to-image)

## 💡 Inspiration
The inspiration behind this project stems from the need to streamline regulatory reporting in banking by automating data profiling. Traditional methods involve manual rule definition, which is time-consuming and prone to errors. By leveraging AI and machine learning, we aim to enhance compliance efficiency and accuracy.

## ⚙️ What It Does
1. **Regulatory Instruction Interpretation:** Extracts and interprets regulatory reporting instructions to identify data validation requirements.

2. **Automated Profiling Rule Generation:** Uses Large Language Models (LLMs) to generate profiling rules based on allowable values and cross-relations between data elements.

3. **Executable Validation Code:** Generates code to assess data conformity against extracted rules.

4. **Anomaly Detection with Reasoning:** Identifies flagged transactions along with their reasons, combining outputs from SQL validation and an Isolation Forest unsupervised learning model.     The results are further enhanced with natural language reasoning using the Gemini API, providing comprehensive insights into anomalous transactions.

5. **Interactive Custom Conversational Interface (Chainlit UI):** Offers a user-friendly interface for two primary personas:

     - **Auditor:** Can upload CSV files to receive flagged transactions with detailed explanations, facilitating efficient review and validation.

     - **Admin:** Has the ability to view, update, and refine profiling rules, ensuring that the system remains aligned with evolving regulatory requirements and organizational needs.




## 🛠️ How We Built It
Our solution was developed using a diverse set of modern technologies and tools to ensure robustness, scalability, and user-friendly interaction:

*   **Chainlit:** Utilized for creating a interactive conversational interface that facilitates smooth interactions between users and the system.

*   **Gemini API:** Integrated to generate profiling rules and SQL queries for validation and natural language explanations for flagged transactions, enhancing transparency and understanding.

*   **Scikit-learn:** Employed for implementing machine learning models, specifically the Isolation Forest algorithm for detecting anomalies.

*   **FastAPI:** Used to build a high-performance backend API that efficiently handles data processing and requests.

*   **React:** Implemented for developing a responsive and interactive frontend interface.

*   **SQLite:** Served as the database solution for storing and managing profiling rules and transaction data.

## 🚧 Challenges We Faced

1.   **Custom Chainlit Component Development:** Developing a custom Chainlit component that integrates with React allowed us to push the boundaries of conversational interface design. Overcoming compatibility issues and ensuring responsiveness enabled us to create a highly intuitive user experience, enhancing the overall usability of our solution.

2.   **Optimizing Free-Tier Models:** Leveraging free-tier models required us to be creative and resourceful. Despite limitations in accuracy and RPM allowances, we successfully optimized our solution to maximize performance within these constraints. This experience honed our ability to efficiently utilize resources and develop scalable, cost-effective solutions.

## 🏃 How to Run
1. **Clone the repository**  
   ```sh
   git clone https://github.com/ewfx/gaidp-neural-nomads.git
   ```
2. **Create Virtual Environments:** <br> 
   Create two separate virtual environments for the backend and frontend:
   
    1. **Backend Virtual Environment:**   Create virtual environment for backend: 
        ```sh
            python -m venv backend_venv
        ```
       Activate the backend virtual environment:
        ```
            # On Windows
            .\backend_venv\Scripts\activate
            # On Linux/Mac
            source backend_venv/bin/activate
         ```
        
    2. **Frontend Virtual Environment:**   Similarly create virtual environment for frontend: 
        ```sh
            python -m venv frontend_venv
         ```
       Activate the frontend virtual environment:
       ```
            # On Windows
            .\frontend_venv\Scripts\activate
            # On Linux/Mac
            source frontend_venv/bin/activate
        ```
3. **Install Dependencies and Run Application**

   1.   **Backend Dependencies:**
        Navigate to the backend directory.
        ```sh
        cd Backend server
        ```
        Install the required dependencies using pip:
        ```sh
        pip install -r requirements.txt
        ```
        Run the backend server:
        ```sh
        python main.py
        ```
   2.   **Frontend Dependencies:**
        Navigate to the frontend directory.
        ```sh
        cd Chatbot
        ```
        Install the required dependencies using pip:
        ```sh
        pip install -r requirements.txt
        ```
        Run the frontend application:
        ```sh
        chainlit run chatbot.py
        ```


## 🏗️ Tech Stack
- 🔹 Frontend: React , Chainlit
- 🔹 Backend: FastAPI , Python
- 🔹 Database: SQLite3
- 🔹 Other: Gemini AI API

## 👥 Team
- **Neha Anand** - [GitHub](https://github.com/NehaAnand28) | [LinkedIn](https://www.linkedin.com/in/neha-anand-927157200/)
- **Sukriti Bohra** - [GitHub](https://github.com/sukriti136) | [LinkedIn](https://www.linkedin.com/in/sukriti-bohra-b93795218?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app
)
- **Nikhil Giri** - [GitHub](#) | [LinkedIn](#)
- **Aishwarya Attanti** - [GitHub](#) | [LinkedIn](#)
- **Lalitha Ramakrishnan** - [GitHub](#) | [LinkedIn](#)
