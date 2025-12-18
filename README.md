# Daily-Quotes-App-Widget
A minimal, tray-based desktop widget for Windows that displays hand-picked motivational and reflective quotes. Designed to be calm, distraction-free, and always available when you need it.
# About

# ✨ What is this?
Daily Quote Widget is a lightweight Windows desktop app that:

Shows a single quote in a small desktop window

Lives quietly in the system tray

Refreshes quotes on demand

Supports dark mode

Supports Markdown formatting for beautiful quotes

Uses subtle text-only animations (no flashy effects)

Lets you maintain your own quote collection in a simple text file

It’s ideal for:

Journaling

Daily reflection

Focus sessions

Minimalist desktops


# 🧩 Key Features
🖼 Desktop widget with clean, centered layout

🧷 Tray-based control
Show / hide widget

Refresh quote

Toggle dark mode

Exit app

🌙 Dark mode & light mode (persists across restarts)

✨ Subtle text fade animation (text-only, no window flicker)


# 📝 Markdown support:
**bold**

*italic*

`code`

Author lines using —
📄 User-controlled quotes via a simple quotes.txt file

🚀 Can be configured to start with Windows


# 🖥 Supported Platform
✅ Windows 10 / 11

❌ macOS / Linux (not supported)


# 📦 What’s in this repository?
dist/
 └── DailyQuoteWidget.exe   ← the application
quotes.txt                 ← your quotes live here
README.md                  ← this file


You only need the .exe and quotes.txt to run the app.


# ▶ How to Run
Download the repository (or just the dist folder)

Double-click:

DailyQuoteWidget.exe


That’s it.

The widget will:

Appear on your desktop

Add itself to the system tray


# 🧷 Using the Tray Icon
Right-click the tray icon to access:

Show Widget → show the quote window

Refresh Quote → show a new quote

Toggle Dark Mode → switch theme

Exit → close the app completely

Closing the widget window (❌) hides it to the tray — the app keeps running.


# 📝 Customizing Quotes
All quotes are stored in a simple text file:

quotes.txt

Format rules

Quotes are separated using |

Markdown is supported

Author lines start with —


# Example
**Discipline** beats *motivation*.
— James Clear |

Progress is still progress,
even when it’s *quiet*. |

Write code like a **human** will read it.
— Unknown |


Edit the file anytime — changes apply on next refresh.


# 🌙 Dark Mode
Toggle from the tray menu

Your choice is remembered automatically

No restart required


# 🚀 Start with Windows (Optional)
To launch the widget automatically on startup:

Press Win + R

Type:

shell:startup


Create a shortcut to DailyQuoteWidget.exe

Place it in the Startup folder


# 🛠 Built With
Python

Tkinter (UI)

pystray (system tray)

Pillow (tray icon)

Packaged with PyInstaller


# 🎯 Design Philosophy
Minimal over flashy

Calm over distracting

User-owned content

Respect platform limitations

No ads, no tracking, no cloud


# 📌 License
Free to use and modify for personal or educational purposes.

# Disclaimer-
This is a personal project that i build for my use and would like share with anyone in need for such use case, it works perfectly fine in my PC even so, I will not be responsible for anything you do with it or if anything breaks, I by no means am forcing you to use it, you will do so by your own free will.

# 🙌 Contributions
Suggestions, improvements, and ideas are welcome.
This project is intentionally simple — feature requests should respect that philosophy.
