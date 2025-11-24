📅 Calendar Event Generator

A console-based C++ application that generates calendars, manages events, and allows users to view, add, update, and delete scheduled events.
This project demonstrates core Data Structures & Algorithms concepts using Binary Search Trees, Queues, and Date Calculations.

✅ Features
🗓 Calendar Utilities

Display current date and month

View all months of a selected year

Display a specific month between 1900–2100

Leap year detection

📌 Event Management

Add new events with:

Title

Description

Location

Date

View all scheduled events in sorted order

Edit existing events

Delete events

Detailed event view

⚙️ Under the Hood

Events stored using a Binary Search Tree (BST) sorted by date

Inorder traversal for chronological display

Queue structure for event listing

Custom calendar rendering logic

🧠 Data Structures Used
Component	Data Structure	Purpose
Event Storage	Binary Search Tree	Sort and manage events by date
Event Listing	Queue	Sequential display of events
Calendar Logic	Functions & Arithmetic	Month/day calculations
🚀 How to Run
✅ Requirements

C++ Compiler (GCC, MinGW, or MSVC)

Windows (uses <conio.h> & system("cls"))

Any C++ IDE or terminal

▶️ Steps

Clone the repository:

git clone https://github.com/your-username/calendar-event-generator.git


Open the project in your IDE or terminal.

Compile the code:

g++ calendar.cpp -o calendar


Run it:

./calendar

📋 Menu Options
1. Current Date
2. Show All Months (Year View)
3. Show Selected Month
4. Add Event
5. Show Events
6. Delete Event
7. Update Event
8. Exit

🏗️ Project Structure
Calendar Event Generator
│
├── Calendar Class
│   ├── Leap Year Check
│   ├── Monthly Display
│   └── Weekday Calculation
│
├── Event Class
│   ├── Add Event
│   ├── Edit Event
│   ├── Delete Event
│   └── BST Storage
│
└── Queue Class
    ├── Event Listing
    └── Event Selection

📚 Learning Outcomes

Applied BST for sorted data management

Implemented queue traversal

Built calendar logic using date arithmetic

Strengthened understanding of DSA in real-world applications

🔧 Future Enhancements

✅ File-based storage (save events permanently)
✅ GUI or Web UI
✅ Search events by title/date
✅ Reminder/notification system

🖥️ Tech Stack

Language: C++

Paradigm: Object-Oriented Programming

DSA Concepts: BST, Queue, Recursion

📜 License

This project is open-source under the MIT License.

🤝 Contributing

Pull requests are welcome!
For major changes, please open an issue first to discuss what you'd like to improve.

🙌 Author

Manveer Singh
B.Tech CSE (Batch 2027)
