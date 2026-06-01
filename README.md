# AstraAI

**ASTRA AI** is a voice-controlled desktop assistant designed to help users control their computer through natural speech commands.

The name **ASTRA** comes from the Sanskrit word meaning a powerful tool or weapon. In this project, ASTRA acts as a digital tool for accessibility, productivity, and hands-free computer control.

ASTRA AI aims to make computer usage easier by allowing users to control desktop tasks using voice commands.

## Problem Statement

Most desktop automation tools require technical knowledge, typing, or manual setup. Many voice assistants also depend heavily on cloud services and are not built mainly for desktop-level productivity.

ASTRA AI solves this by providing a simple, voice-based desktop assistant that can understand commands and perform useful actions on the user's computer.

## Main Features

### Version 1 Features

- Open desktop applications using voice
- Type text using voice commands
- Take screenshots
- Control basic system actions
- Perform simple browser/search actions
- Give voice/text feedback to the user

### Future Features

- Offline speech recognition
- Local LLM-powered command understanding
- Custom user-defined commands
- Accessibility mode for elderly and disabled users
- Hindi and Gujarati command support
- Plugin system for adding new automations
- Privacy-first local processing

## Target Users

ASTRA AI is designed for:

- Students
- Developers
- Elderly users
- People with motor disabilities
- Users with hand injuries
- Anyone who wants hands-free desktop control

## Tech Stack

- Python
- SpeechRecognition / Whisper
- PyAutoGUI
- pyttsx3
- OS module
- Ollama / local LLM in future versions

## How ASTRA AI Works

1. User gives a voice command.
2. ASTRA converts speech to text.
3. ASTRA identifies the user's intent.
4. ASTRA performs the desktop action.
5. ASTRA gives feedback to the user.

Example:

```text
User: Open Chrome, open youtube, go to the video of veritasium on topic MATH DUEL, and copy the link, send it to "MUMMA" on whatsapp
ASTRA: Opening Chrome, opening youtube, navigating to MATH DUEL by veritasium, Shar options, copied link, opening whatsapp, verifying the identity, navigating to chat of MUMMA, pasted the link, SENT!

