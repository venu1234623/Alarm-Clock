# Python Alarm Clock

A desktop alarm clock application built using Python and Tkinter. The application provides a graphical user interface for setting an alarm and plays an alarm sound when the scheduled time is reached.

## Features

- Graphical user interface using Tkinter
- Set an alarm for a specific time
- Display the current time
- Alarm notification with sound
- Time-based alarm scheduling
- Multithreaded execution to keep the application responsive

## Technologies Used

- Python
- Tkinter
- Datetime
- Threading

## How It Works

The application provides a graphical interface where the user can set an alarm time.

The program continuously checks the current time against the configured alarm time. When the scheduled time is reached, the application triggers the alarm sound.

```text
User sets alarm time
       ↓
Application monitors current time
       ↓
Current time matches alarm time
       ↓
Alarm is triggered
       ↓
Sound notification
