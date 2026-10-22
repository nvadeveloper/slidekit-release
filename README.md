# Slidekit — beta

Slidekit is a desktop editor for interactive, slide-based e-learning courses, with an AI assistant built in. Build slides with layers, states, triggers and variables, add quizzes and media, and export a SCORM 1.2, SCORM 2004, cmi5, xAPI or web package for your LMS.

This repository holds only the installers and their notes. The source code is not published.

**Status: free beta.** Expect rough edges and keep copies of your important course files. Feedback is very welcome — see below.

## Download

Open [**Releases**](https://github.com/nvadeveloper/slidekit-release/releases) and download the newest version for your system:

| System | File |
| --- | --- |
| macOS, Apple silicon (M1 and later) | `Slidekit-<version>-mac-arm64.dmg` |
| macOS, Intel | `Slidekit-<version>-mac-x64.dmg` |
| Windows 10 / 11, 64-bit | `Slidekit-<version>-win-x64.exe` |

`SHA256SUMS.txt` beside them lists the files’ checksums, if you want to check a download.

**System requirements:** macOS 13 or later, or Windows 10/11 (64-bit); a window at least 1280 pixels wide.

## Installing the beta

The beta installers are not yet signed with a developer certificate, so your system warns you the first time.

**macOS**

1. Open the `.dmg` and drag Slidekit into Applications.
2. Open Slidekit. macOS says it cannot check the app for malicious software.
3. Open **System Settings → Privacy & Security**, scroll down and click **Open Anyway** next to the message about Slidekit, then confirm.

You only need to do this once.

**Windows**

1. Run the `.exe`.
2. If Windows SmartScreen says it protected your PC, click **More info → Run anyway**.
3. Accept the license agreement and finish the installer.

On a PC with Smart App Control turned on, Windows blocks unsigned installers with no way around it; the beta can’t be installed there yet.

There are no automatic updates in the beta: download and install a new version the same way.

## What is in the beta

- **An AI assistant beside the slide:** courses from your documents, layouts in the course’s style, interactive exercises, triggers in plain words, quiz questions, narration scripts and translation. It runs through your own Claude Code or Codex, or your company’s OpenAI-compatible model.
- Slides with layers, object states, triggers with conditions, and variables.
- Masters and layouts, scenes, and a course view of how slides lead to each other.
- Questions: single choice, multiple response, true/false, drag and drop, matching, sequence, text and numeric entry, press-the-key and hotspots; question banks and draws, partial credit, points per choice.
- Quizzes with a passing score, attempts and timers; results slides and certificates.
- Video and audio with captions; narration recorded in the app.
- Ready-made blocks (tabs, accordion, process, flashcards), a scroll panel, HTML objects, formulas, icons and tables.
- **Course transfer:** a `.story` course or the SCORM package (1.2 or 2004) published from one opens as a new Slidekit course — slides, layers, states, triggers, variables, questions, banks and the test, fonts and pictures. It runs on your computer, without AI.
- PowerPoint import and XLIFF translation.
- Export to SCORM 1.2, SCORM 2004, cmi5, xAPI and a web page; a preview with a debug panel.
- English and Russian interface (Settings → Interface language).

Exported courses are yours: the player inside them is MIT-licensed, so you can host and share them freely.

## Feedback

Found a bug or have an idea? Write to **nvadeveloper@gmail.com**, or use **Help → Report a problem or suggest an idea…** in the app — it fills in your version and system. Screenshots and the course file (if you can share it) help a lot.

If the app crashed, **Help → Save report for the developer…** saves a diagnostic file you can attach.

## License

The beta is free to use under the [beta license agreement](BETA-LICENSE.txt), which the installer also shows. Third-party components are listed in `THIRD_PARTY_NOTICES.md` inside the app.
