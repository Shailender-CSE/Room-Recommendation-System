# Room Recommendation System using Design and Analysis of Algorithms (DAA)

## 📌 Project Overview
This project is a **Room / Paying Guest Recommendation System** designed for **students, workers, and tourists** who want accommodation for **days, weeks, or months**.

The system applies **Design and Analysis of Algorithms (DAA)** concepts such as:
- Filtering
- Scoring (Greedy approach)
- Sorting (Bubble Sort)
- Time Complexity Analysis

The project is implemented entirely in **C++** using structured programming.

---

## 🎯 Objectives
- Recommend best rooms based on user requirements
- Apply DAA concepts to a real-world problem
- Understand scoring and sorting algorithms
- Practice modular and structured C++ programming

---

## 🧠 DAA Concepts Used

| Concept | Usage |
|------|------|
| Greedy Strategy | Selecting best room based on score |
| Scoring Function | Converts multiple parameters into one value |
| Sorting Algorithm | Bubble Sort to rank rooms |
| Time Complexity | O(n²) for sorting |

---

## 🏗️ Data Structures Used
- `struct room` → stores room details
- `struct user_requirement` → stores user preferences
- `struct matching_room` → combines room + score

---

## ⚙️ Features
- Supports **daily / weekly / monthly** stays
- Budget-based filtering
- Safety, distance, and facility-based scoring
- Sorted room recommendations

---

## 🧮 Scoring Formula
Score =
(budget - rent) +
(safety_rating × 10) +
(facility_rating × 5) +
(10 - distance)

Higher score = Better recommendation

---

## 👥 Team Roles

| Member | Responsibility |
|------|---------------|
| Member 1 | Data structures & input handling |
| Member 2 | Scoring logic & DAA justification |
| Member 3 | Sorting, output & documentation |

---

## 🚀 Future Enhancements
- Dynamic user input
- Database integration
- GUI or Web version
- Advanced sorting (Quick Sort)
- Graph-based location analysis

---

## 🛡️ License
This project is licensed under the **MIT License**.

---

## 📚 Conclusion
This project demonstrates how **DAA concepts can be applied to real-life decision-making systems**, making it both educational and practical.
