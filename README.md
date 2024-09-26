# Pomodoro_timer28
This project is a Pomodoro Timer built using Python's tkinter library, designed to help users manage their work and break intervals efficiently by following the Pomodoro Technique. The application cycles through work sessions and breaks, allowing for increased productivity and time management.

function breakdown:
- WORK_MIN: 25 minutes (work duration)
- SHORT_BREAK_MIN: 5 minutes (short break duration)
- LONG_BREAK_MIN: 20 minutes (long break duration)

The reset_timer() function allows the user to stop the current timer and reset the session to its default state. It cancels the running timer, resets the displayed timer, and clears any checkmarks indicating completed sessions.

The start_timer() function begins a new work/break session based on the current state. The application cycles between:
+ Work Session: 25 minutes (green display)
+ Short Break: 5 minutes (pink display)
+ Long Break: 20 minutes (red display, after every 4 work sessions)


