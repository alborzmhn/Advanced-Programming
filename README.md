Class Schedule & Place Visit Planner
Overview
This repository contains two distinct C++ projects:

Class Schedule - A program that generates an optimized weekly schedule for courses and teachers.
Place Visit Planner - A planner that recommends the best sequence of places to visit based on time, ranking, and availability.
📁 Project 1: Class Schedule
Description
The Class Schedule program creates an optimized weekly timetable for courses by considering teacher availability, course timings, and specific constraints. It ensures that no teacher is double-booked and all courses are scheduled appropriately.

Key Features
Teacher & Course Management: Handles multiple teachers and courses.
Conflict Resolution: Avoids overlapping schedules.
Sorting & Assignment: Prioritizes courses alphabetically.
How to Run
Compile the project using a C++ compiler.
Input:
Number of teachers and their availability.
Course details (name, day, start/end time).
Output: A complete weekly course schedule.
📁 Project 2: Place Visit Planner
Description
The Place Visit Planner suggests an optimal visiting sequence for a list of places based on opening/closing times and priority ranks. It ensures maximum coverage within the available time.

Key Features
Time Optimization: Prioritizes places with higher ranks and longer availability.
Automatic Sorting: Adjusts visiting order dynamically.
Detailed Itinerary: Prints a complete visiting schedule.
How to Run
Prepare an input CSV file with the following structure:
makefile
Copy code
name,openingTime,closingTime,rank
PlaceA,08:00,17:00,1
PlaceB,09:00,18:00,2
Compile the project using a C++ compiler.
Execute the program:
php
Copy code
./PlaceVisitPlanner <input_file.csv>
Output: A suggested visit schedule.
⚙️ Requirements
Compiler: C++11 or later.
Standard Libraries: <iostream>, <vector>, <fstream>, <algorithm>, <string>.
🚀 Getting Started
Clone the repository:
bash
Copy code
git clone https://github.com/YourUsername/YourRepo.git
Navigate to the project directory:
bash
Copy code
cd YourRepo
Compile and run each project as described.
