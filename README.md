# Social Network Project 🌐

Welcome to our Social Network project! This is our first major milestone in software development, where we implemented a functional social networking system focusing on efficient data structures and a smooth user experience.

This project was developed as the final assignment for the **Data Structures course** at the **University of Isfahan, Faculty of Computer Engineering (Winter 2025).**

---

## 🤝 Collaborators

I am proud to have collaborated on this project with my talented friend:

* **[Amir hossein Ala](amir-h-A-0001)**
* **[Amirreza Chami](Amir-chi)**

---

## 🛠 Built With

* **C++**: For core logic and data management.
* **Qt Framework**: To provide a modern and interactive Graphical User Interface (GUI).

---

## 📋 Features

Based on the *[Social Network.pdf](https://github.com/Amir-chi/Social-Network/blob/main/Social%20Network.pdf)* requirements, the following modules were implemented:

### 1. User Management

* **Secure Authentication**: Unique username and password registration/login.
* **Personal Profiles**: Each user has a dedicated page displaying personal info and posts.
* **Privacy Control**: Profiles are only accessible to the owner and their followers.
* **CRUD Operations**: Users can edit their information, manage posts, or delete their accounts entirely.

### 2. Smart Connection System

We implemented an intelligent **“Suggested Friends”** algorithm.

The probability of two users knowing each other is calculated using the following formula:


$$P(A, B) = \frac{|\text{Common Followers}|}{|\text{Total Unique Followers of both users}|}$$


* **Smart Recommendations**: The system suggests the top 6 users based on the highest probability.
* **Fallback Mechanism**: For new users with no common followers, the system suggests the 6 most recently joined members.

---

## 🚀 How to Run

1. Ensure you have **Qt Creator** and a **C++ compiler** installed.
2. Clone the repository.
3. Open the `.pro` file in Qt Creator.
4. Build and run the project.

---

## 🎓 Acknowledgments

Special thanks to **Dr. Afsaneh Fatemi** for her guidance during the Data Structures course.
