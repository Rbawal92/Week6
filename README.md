# Fun with Video Games and the First Steps of My Journey in UX Design  
*A C++ Interactive Console Program by Raymond Bawal*
*ITCS 2530*
*Professor Koss*

---

## Overview
This program is an interactive C++ console experience designed to explore:

- User input  
- Value analysis  
- Game nostalgia  
- Enums  
- Arrays/ new this week  
- File output  
- UX-inspired data flow

The user answers questions about their favorite game, including price, hours played, gameplay ratings, difficulty, and more. The program then evaluates game value, assigns a tier, calculates averages, and generates a **summary report (report.txt)**.

---

##  Features
###  User Input & Validation**
- Game title  
- Favorite character  
- Gaming platform  
- Age  
- Hours played  
- Game price  
- Rating categories  
- Difficulty level  

###  Enum-Based Systems**
*New this weeek*
This program uses two enums:

```cpp
enum GameTier { LOW_TIER, GOOD_TIER, SUPER_TIER };
enum DifficultyLevels { EASY, NORMAL, HARD };
