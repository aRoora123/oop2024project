# oop2024project
The Gamified Learning Platform is a C++ application designed to make learning math and programming fun for kids. In Phase-1, we’ve developed a foundational game and the supporting system for managing teachers, students, and scores. The game includes a Memory Game: Flip Cards for Matching, which introduces students to problem-solving in an interactive way.

Team Members
Member A (005)
Member B (008)
Project Setup
Prerequisites

#structure
Gamified_Learning_Platform/
├── src/
│   ├── main.cpp            # Main file to run the application
│   ├── Teacher.h / .cpp    # Classes for teacher record management
│   ├── Student.h / .cpp    # Classes for student record management
│   ├── Game.h / .cpp       # Game base class and MemoryGame class
│   └── Menu.h / .cpp       # Class for the application menu and options
├── data/
│   ├── teacherRecords.csv   # Stores teacher data
│   ├── studentRecords.csv   # Stores student data
│   └── problemSets.csv      # Stores game questions and answers
└── README.md                # Project documentation

#Libraries used

1.windows.h
SetConsoleTextAttribute: Change console text color.
Sleep(milliseconds): Add a delay to the program.
system("CLS"): Clear the console screen.

2.conio.h
Provides basic console input/output functions to create a more interactive UI and handle keyboard inputs.

<chrono> and <thread>
std::this_thread::sleep_for: Cross-platform alternative to Sleep, used for time-based delays.
std::chrono: Used for tracking elapsed time, particularly to determine the scoring based on completion time.

