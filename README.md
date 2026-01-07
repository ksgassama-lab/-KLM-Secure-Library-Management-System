
# 📚 KLM: Enterprise Library Management System

**Developer:** Kaddy Gassama  
**Education:** B.S. Cybersecurity & Information Assurance  
**Credentials:** Appian Associate Developer Certificate | CompTIA Security+, PenTest+, Network+, Project+

---

## 1. Project Overview
The **KLM (Kaddy Library Management)** system is a professional application built on the **Appian** platform. It digitizes traditional library operations, replacing manual paperwork with a secure, automated workflow for managing book inventory, rentals, and returns.

![Alt text that describes the image](https://github.com/ksgassama-lab/-KLM-Secure-Library-Management-System/blob/8a5cc16a46baae7b7590ac7dc3c85f5dfc643263/Site%202.png)

---

## 2. Secure Data Management (Records)
I used **Appian Data Fabric** to build a structured database. This allows the system to store and link information efficiently, ensuring "one version of the truth" for all library data.

* **KLM Book Detail:** Tracks every book’s title, author, and real-time availability.
* **KLM Client Detail:** Maintains secure records of members and their borrowing history.


![Alt text that describes the image](https://github.com/ksgassama-lab/-KLM-Secure-Library-Management-System/blob/8a5cc16a46baae7b7590ac7dc3c85f5dfc643263/Book%20Details.png)


---

## 3. Business Logic & Automation (Process Models)
The "brain" of this app is built using **Appian process models**. I designed these workflows to handle complex decisions automatically, reducing the need for manual intervention.

* **Smart Approval Flow:** When a book is requested, the system automatically checks availability and routes a task to the supervisor for review.
* **Decision Gateways:** I implemented logic that directs requests based on user roles and book status.

![Alt text that describes the image](https://github.com/ksgassama-lab/-KLM-Secure-Library-Management-System/blob/8a5cc16a46baae7b7590ac7dc3c85f5dfc643263/Process%20modeler.png)

---


## 5. Security-First Architecture
Drawing on my **Cybersecurity degree**, I built this application with a "Secure by Design" mindset:

* **Access Control (RBAC):** I implemented **Role-Based Access Control** using Appian Groups. For example, `KLM_GROUP_SUPERVISOR` ensures that only authorized managers can approve high-level requests.
* **Least Privilege:** Users only see the data and buttons necessary for their specific role, minimizing the risk of unauthorized data changes.



---

## 🚀 Key Technical Skills Demonstrated
* **Low-Code Development:** Expert use of Appian SAIL and Process Modeling.
* **Process Optimization:** Streamlining manual business operations into digital workflows.
* **Cybersecurity Integration:** Applying Security+ and PenTest+ principles to application development.
* **Project Management:** Organizing the development lifecycle using Project+ methodologies.

---
