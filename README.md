# 💻 Software Engineering  

## 📌 Overview  
As part of a **software engineering course at the University of Maryland**, I performed **requirements analysis and testing** as part of the **Software Development Life Cycle (SDLC)** for a **student management application**. The project involved **requirement gathering, system modeling, and testing through real-world API interactions**.  

---

## 🛠 Key Contributions  

- 📜 **Conducted requirement analysis** using **Entity-Relationship Diagrams (ERD)**, **Domain Questions**, and **User Stories**.  
- 🎯 **Prioritized features using bigraph-based prioritization**, ensuring a **structured SDLC workflow**.  
- 🚀 **Designed user stories and their priorities**, mapping **core functionalities** for a student management system.  
- 🔄 **Performed extensive API testing**, providing **numerous test inputs through Twitter API** to validate system interactions.  

---

## 🛠 Tools & Technologies Used  

| Category                     | Tools & Technologies |
|------------------------------|----------------------|
| 📜 Requirement Analysis      | ERD, Domain Questions, Prioritization Graphs |
| 🚀 API Testing               | Twitter API |
| 🔄 Software Development Lifecycle | Agile, SDLC |
| 📊 Project Management        | JIRA, Trello |
| 🔑 System Modeling           | UML, Use Case Diagrams |

---

## ⚙️ Sample Implementations  

### 📜 Sample User Story for Student Management System  
```plaintext
As a student, I want to be able to register for courses so that I can enroll in my classes on time.
```
🎯 Example of ERD for Student Management System
```plaintext
[STUDENT] -- (Registers) -- [COURSE]
[COURSE] -- (Taught by) -- [PROFESSOR]
[STUDENT] -- (Submits) -- [ASSIGNMENT]
```
🚀 Sample API Call to Twitter for Testing
```python
import tweepy

consumer_key = "your_consumer_key"
consumer_secret = "your_consumer_secret"
access_token = "your_access_token"
access_secret = "your_access_secret"

auth = tweepy.OAuthHandler(consumer_key, consumer_secret)
auth.set_access_token(access_token, access_secret)
api = tweepy.API(auth)

tweet = api.update_status("Testing Twitter API for Software Engineering Project!")
print("Tweet posted successfully!")
```

⸻

📋 Final Report & Evaluation

The project concluded with:

✅ Well-defined system requirements, including ERDs, domain questions, and prioritization bigraphs.
✅ Thorough user story mapping, ensuring a structured and user-centric software development process.
✅ Practical API testing, demonstrating real-world software interactions using the Twitter API.
✅ Final presentation & documentation, summarizing the SDLC workflow for a student management system.

⸻

🎤 Presentation & Impact

I compiled the findings and system design models into a technical software engineering report, demonstrating real-world application development workflows.

⸻

💬 Have Questions?

Feel free to reach out or open an issue! 🚀💻
