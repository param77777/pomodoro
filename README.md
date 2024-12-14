# Pomodoro Timer 🍅

A simple Pomodoro Timer built using Python's `tkinter` library. This timer helps you manage your productivity by alternating between work sessions and breaks, following the Pomodoro Technique.

## Features
- **Work Timer**: 25-minute work sessions by default.
- **Short Break**: 5-minute short breaks after each work session.
- **Long Break**: 20-minute break after completing four work sessions.
- **Customizable**: Easily modify the work, short break, and long break durations.
- **Visual Countdown**: Displays the countdown timer on a canvas.
- **Session Tracking**: Displays checkmarks for completed work sessions.

## Requirements
- Python 3.x
- `tkinter` (usually included in standard Python installations)

## Customization
You can customize the timer durations by modifying these constants in the script:
```python
WORK_MIN = 25  # Duration of work sessions in minutes
SHORT_BREAK_MIN = 5  # Duration of short breaks in minutes
LONG_BREAK_MIN = 20  # Duration of long breaks in minutes
```

## Contributing
Feel free to submit issues or pull requests for improvements or additional features.
