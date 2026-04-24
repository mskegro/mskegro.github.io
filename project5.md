[Back to Portfolio](./)

# Gamified Habit Tracker

- **Class: Senior Project Implementation/Defense (CSCI 496)**
- **Grade: In Progress**
- **Language(s): Dart**
- **Defense Documentation:** [mskegro/habit_tracker](https://github.com/mskegro/habit_tracker/tree/main/documentation)
- **Source Code Repository:** [mskegro/habit_tracker](https://github.com/mskegro/habit_tracker)
(Please [email me](mailto:mskegro@student.csuniv.edu?subject=GitHub%20Access) to request access.)

## Project Description

Habit Love is a gamified habit-tracking app built with Flutter and Firebase. The app transforms the often dull process of building new habits into an engaging, rewarding experience where users earn XP for completing daily habits, level up as they grow, and unlock achievement badges for hitting milestones. Streaks keep users accountable day over day, while a built-in analytics dashboard visualizes progress through weekly and monthly charts so users can actually see themselves improving over time. All data syncs to the cloud in real time via Firebase, meaning progress is never lost and is accessible across devices. The result is an app designed to make habit formation more engaging and sustainable.

## How to Run the Program

To run this project, follow the steps below.

### 1. Clone the repository
```bash
git clone https://github.com/mskegro/habit_tracker
```
### 2. Navigate to the project folder
```bash
cd habit_tracker
```
### 3. Install dependencies
```bash
flutter pub get
```
### 4. Run the program
```bash
flutter run 
```
### 5. View output
The app will launch, and from there you can:
- Create an account or log in with your email
- Create and customize habits
- Complete habits to earn XP and build streaks
- View your achievements and analytics dashboard

## UI Design

The home dashboard displays today's habits as interactive cards, along with the user's current XP, level, and streak counts (see Fig. 1).

![screenshot](images/ss1.png)
Fig 1. The home dashboard

The habits screen displays all of the user's created habits along with their current streak and completion status (see Fig. 2).

![screenshot](images/ss2.png)  
Fig 2. The habits screen

The habit creation screen allows users to name a habit, assign a color, and set a recurrence schedule (see Fig. 3).

![screenshot](images/ss3.png)  
Fig 3. The habit creation screen

The analytics screen uses fl_chart to render weekly bar charts and monthly progress trends pulled from Firestore (see Fig. 4).

![screenshot](images/ss4.png)  
Fig 4. The analytics screen

The profile screen displays the user's current level, XP, achievement badges, and account information (see Fig. 5).

![screenshot](images/ss5.png)  
Fig 5. The profile screen

## Additional Considerations

This project highlights important software engineering concepts such as:

- Gamification mechanics including XP, streaks, levels, and achievement badges
- Real-time cloud sync using Firebase Firestore and Firebase Authentication
- State management using the Provider pattern in Flutter
- Data visualization using fl_chart for analytics and progress tracking

For more details see [mskegro/habit_tracker](https://github.com/mskegro/habit_tracker).

[Back to Portfolio](./)
