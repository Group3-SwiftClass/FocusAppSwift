# FocusAppSwift
# **Original App Design Project**

**App Name Ideas:**
- FocusFlow
- FocusBuddy
--------------------------------------------
**Table of Contents:**
1. Introduction
- Project Overview
- Purpose and Goals of the App
- Description of the Pomodoro Technique

2. App Features
- Overview of Core Features
- Timer with Work and Break Intervals
- Customizable Timer Settings
- Task Management

3. Overview of Additional Features (Not Required)
- Focus Mode (Noises in background)
- Custom Themes
- Statistics/Progress Tracking
- Social Sharing

4. User Interface (UI) Design
- Screen Mockups
- Home Screen
- Settings Screen
- Task List Screen
- Statistics/Progress Screen
- Profile Screen (optional)
- Color Scheme and Theming
- Navigation Flow

5. Main Navigation Overview
- Main Flow (Timer/Task List)
- Task Management Flow
- Settings Adjustment Flow
- Statistics Access Flow

6. Software Development Tools and Technologies
- Programming Language (SwiftUI)
- APIs used
- Database Requirements
- App Architecture

7. Overview of App Structure
- Explanation of Key Components and Modules
- Timer Logic
- Task Management System

8. Potential Technical Challenges
- UI/UX Design Challenges
- Solutions and Workarounds
- Future Enhancements

9. Summary of Project Experience
- Lessons Learned
- Next Steps for the Team
--------------------------------------------
**Description:**
(FocusFlow/FocusBuddy) is a productivity app designed to help you stay focused and achieve your goals using the Pomodoro technique. Break down your work into focused intervals with customizable timers, followed by short breaks to recharge. Track your progress with insightful statistics, manage tasks with a built-in to-do list, and create a distraction-free environment with focus mode. Whether you're studying, working, or just need a boost in productivity, (FocusFlow/FocusBuddy) helps you stay on track and make the most of your time.

**App Evaluation:**
Category: Productivity, Education
Mobile:  Yes
Story: Helps users overcome procrastination and stay focused by guiding them through structured work intervals and breaks. It transforms time management into a habit, allowing users to achieve their goals with a balanced approach to work and rest.
Market: The app is aimed towards anyone looking to boost their productivity through structured time management. It’s ideal for those who want to improve their focus, manage their workload, or find balance in their study and work routines.
Habit: This is a daily use app. It helps users establish a consistent routine for working and taking breaks, making it a key part of their daily workflow and study sessions
Scope: The app is narrow in terms of features but highly focused, offering a specialized toolset centered around the Pomodoro technique

**Product Spec**
1. User Stories (Required and Optional)
Required Must-have Stories

- User can start, pause, and reset the Pomodoro timer
- User can customize work and break intervals in the settings.
- User can view the current session's countdown on the home screen
- User can see a notification when a work or break interval ends
- User can add, edit, and delete tasks in the task list
- User can view their task list while using the timer
- User can view their progress, including total completed sessions, work time, and break time

Optional Nice-to-have Stories
- User can enable Focus Mode to disable distractions during work intervals
- User can select background sounds (e.g., rain, white noise) during sessions
- User can track daily and weekly productivity through visual charts
- User can sync data across devices using a cloud service
- User can share completed sessions and productivity stats on social media
- User can set custom themes for the app’s appearance
- User can see achievements or motivational messages after completing certain milestones

2. Screen Archetypes

Home Screen
- Required User Feature: User can start, pause, and reset the Pomodoro timer
- Required User Feature: User can view the current session's countdown

Settings Screen
- Required User Feature: User can customize work and break intervals
- Required User Feature: User can enable or disable Focus Mode
- Optional Feature: User can select background sounds

Task List Screen
- Required User Feature: User can add, edit, and delete tasks
- Required User Feature: User can view their task list

Statistics Screen
- Required User Feature: User can view total completed sessions, work time, and break time
- Optional Feature: User can view daily and weekly productivity charts

Profile Screen (Optional)
Optional Feature: User can see achievements and set focus goals

3. Navigation
Tab Navigation (Tab to Screen)
- Home - Displays the timer and task list
- Tasks - Shows the user’s task list and allows task management
- Statistics - Displays the user's progress and productivity charts
- Settings - Allows customization of timer intervals and app preferences

Flow Navigation (Screen to Screen)
Home Screen
- Leads to Tasks Screen when the user selects "Manage Tasks"

Settings Screen
- Leads to Home Screen after customizing intervals.

Tasks Screen
- Leads to Home Screen when the user finishes managing tasks

Statistics Screen
- Leads to Home Screen when the user taps back

Wireframes
[Add picture of your hand sketched wireframes in this section]

[BONUS] Digital Wireframes & Mockups
[BONUS] Interactive Prototype
Schema
Models
[Model Name, e.g., User]

Property Type Description
username	String	unique id for the user post (default field)
password	String	user's password for login authentication
...	...	...
Networking
[List of network requests by screen]
[Example: [GET] /users - to retrieve user data]
...
[Add list of network requests by screen ]
[Create basic snippets for each Parse network request]
[OPTIONAL: List endpoints if using existing API such as Yelp]
