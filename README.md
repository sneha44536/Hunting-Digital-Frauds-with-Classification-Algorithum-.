# Hunting-Digital-Frauds-with-Classification-Algorithum-.

### 🛠️ Tech Stack & Tools Used
[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)](https://pandas.pydata.org/)
[![NumPy](https://img.shields.io/badge/Numpy-013243?style=for-the-badge&logo=numpy&logoColor=white)](https://numpy.org/)
[![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)](https://scikit-learn.org/)
[![Matplotlib](https://img.shields.io/badge/Matplotlib-ffffff?style=for-the-badge&logo=matplotlib&logoColor=black)](https://matplotlib.org/)

📍 The Problem: The "Needle in a Haystack"
In India, millions of digital transactions happen every second. While most are safe, a tiny fraction are scams. Because scams are so rare, finding them is like looking for a needle in a haystack. If a computer only looks at the "big picture," it might ignore the scams entirely because they happen so infrequently.

  
💡 The Solution: safe-Shield
This project is an intelligent system designed to protect Indian digital payments. It looks at transaction details—like the amount, the city, and the time of day—to decide if a payment is Real or Fraud.

🚀 How the System Works (Simple 3-Step Process)
1. The "Bulletproof" Cleaning Engine
Real-world data is often messy or incomplete. Before the computer can learn, my code automatically:
    a)Fixes missing information.
    b)Removes duplicate entries.
    c)Prepares the data so it is 100% ready for analysis.

Why this matters: It ensures the system never crashes when it sees "messy" real-life data.

2. Balancing the Scales (SMOTE)
Since there are very few fraud examples compared to real ones, the computer can get "lazy" and assume everything is real. I use a technique called SMOTE to create synthetic examples of scams.
The Result: The computer gets enough practice looking at fraud patterns to become an expert at catching them.

3. The Logic Map (Decision Trees)
Instead of a "Black Box" where you don't know why a decision was made, this system uses a Decision Tree. It works like a smart flowchart:
       Step A: Is the transaction amount unusually high?
       Step B: Is it happening at an odd hour (like 3 AM)?
       Step C: Is the location far from the customer's home?



🌟 Key Project Highlights
Built for India: The system understands local payment card types like RuPay and identifies risks in cities like Bangalore, Mumbai, and Surat.
Understandable AI: It provides a visual map of its logic. You can see exactly why a transaction was flagged as "Fraud" instead of "Real."
Smart Timing: It automatically looks at the time of the transaction to catch scammers who operate while people are asleep.

🛠️ The Tools I Used

Python: The main language used to build the system.
Scikit-Learn: The "brain" that provides the classification algorithm.
Pandas: Used for organizing the transaction data.
Matplotlib: Used to draw the visual logic maps.

📈 Final Output
When you run this project, it produces a Logic Tree. This turns complex math into a simple picture that proves the system is making smart, data-driven decisions to keep digital payments safe.
