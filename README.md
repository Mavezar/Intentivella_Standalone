# Intentivella_Standalone
!!!VIBECODED APP!!!

VT: https://www.virustotal.com/gui/file/65a276f76023d55db1b863226a61aaaa9ed5ea8bc9a9a0ac186dfb74a887a444

SHA-256: 65a276f76023d55db1b863226a61aaaa9ed5ea8bc9a9a0ac186dfb74a887a444

HOW TO:
1. Unpack Intentivella_Standalone.zip
2. Go to /intentivella.dist/
3. Run Intentivella.exe

INTENTIVELLA 0.6.6 — Windows 10/11 x64

No Python installation is required on the receiving computer.

Features:
- Active-window work statistics, daily goal progress bar and full-screen reminders
- Daily goal achievements at 25%, 50%, 75% and 100%; five-day streak badge
- Optional five-minute focus sprint counting only actual active work time
- Productivity Room BETA is temporarily hidden in 0.6.6 for future development.
  Existing purchases, artwork, point balance, and source modules are preserved.
- Settings -> Advanced settings can be scrolled with the mouse wheel or the
  visible vertical scrollbar, even while hovering over nested fields/buttons.
- Your own daily goal reward message when the goal is completed
- Delays configurable in hours, minutes and seconds
- Password protection for pause and stop
- Calendar date picker for statistics, with day-by-day browsing
- Custom full-screen reminder background (PNG/JPG/WEBP/GIF/BMP), title and message
- On-hover tips for pause and stop controls
- English interface by default; Russian available in Settings
- Developer contacts: mavezarart@gmail.com / @mavezarart
- Donate: https://boosty.to/mavezar

The app is not a system-wide activity tracker. It counts the foreground application
and pauses counting after two minutes without keyboard or mouse activity.

Settings, milestone/streak history, custom reminder images and statistics are stored in
%LOCALAPPDATA%\Intentivella. The milestone file is motivation.json. The beta room state, earned points and purchased items are stored in productivity_room.json. Existing work history does not generate retroactive room points on the first run.
Your selected image is imported as a local PNG. Streaks are recorded from
version 0.6.1 onward: older usage is not retroactively marked as completed.
The 5-day streak is based on consecutive calendar days, including weekends.

ANTIVIRUS WARNINGS
Some antivirus programs may flag Intentivella as potentially malicious. This may be
a false positive related to heuristic analysis or Nuitka Onefile self-extraction.
Nuitka compiles application logic to native code, but Onefile extracts runtime
components when launched.
Intentivella also monitors active application windows. These legitimate features
may contribute to heuristic antivirus detections.

A warning should not automatically be considered a false positive. Verify the file,
keep Windows Defender enabled, and contact the security vendor if necessary.

EXPERIENCE BETA (updated in 0.6.4)
Only applications currently selected for work can appear in Experience BETA.
Experience is derived exclusively from recorded work activity in work_usage.json,
not from all app activity in usage.json. Selected browser tabs also count as
work where the window title matches a work keyword. Levels 0..100 are per EXE.
Level N requires N squared work hours (Level 100 = 10,000 work hours).
The existing color tiers, level bar, and 100-segment track are unchanged.
Idle time, distractions, background activity, and disabled monitoring never
award experience. Unselecting a work app hides it from the Experience tab;
adding it back restores its previous *work-only* progress. The program keeps
this history in local storage without a separate XP counter.
For working windows selected by title keyword, title-rule matches are saved
locally as keyword-only metadata in work_title_sources.json. Full window titles
are not saved. Older browser work history remains visible when work-tab
keywords are selected; old title-based work from non-browser programs may
require one new work session to appear in this view.

POMODORO EXPRESS (introduced in 0.6.5)
The dedicated Pomodoro Express tab runs configurable focus/break cycles.
Defaults: 20 minutes of work, 5 minutes of rest, 4 cycles. The final cycle
includes its break. Work (1-240 min), rest (1-120 min) and cycles (1-24)
are configurable and persist in the local config.json. Each interval ending
shows a small non-blocking desktop status pop-up; the final break completion
ends the session. Pause/resume and reset are available. Active sessions are
not restored after closing the program. Pomodoro uses ordinary clock time,
independent of work-time measurement. Work XP and statistics continue to count
ONLY monitored, foreground, allowed applications without idle time. Normal
distraction warnings are suppressed while the Pomodoro timer is on a break.
