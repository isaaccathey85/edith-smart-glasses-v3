# Codex Build Tasks for EDITH V3

## Goal
Build a modular Raspberry Pi smart glasses AI assistant named EDITH.

## Core Pipeline
Wake word → speech-to-text → command parser → AI engine → action router → HUD/voice/device output.

## Priority 1
- Build main.py pipeline
- Add config loading
- Add wake word placeholder
- Add Vosk STT placeholder
- Add command parser
- Add voice output
- Add OLED HUD output placeholder
- Add logging

## Priority 2
- Add modes: Civilian, Tactical, Stealth, Learning, Developer
- Add admin/guest permissions
- Add trusted Bluetooth device listing
- Add safe authorized device control system

## Priority 3
- Add Visual Knowledge HUD system
- Commands:
  - “Pull up the Pythagorean theorem”
  - “Show Ohm’s law”
  - “Graph y = x squared”
  - “Display a force diagram”
  - “Explain this visually”
- Render formulas, diagrams, graphs, and labels to HUD

## Priority 4
- Add camera vision module
- Add scene summary
- Add object detection placeholder
- Add contextual HUD overlays

## Priority 5
- Add suit serial controller for approved commands:
  - SUIT_ON
  - SUIT_OFF
  - FLAPS_OPEN
  - FLAPS_CLOSE
  - MISSILE_OPEN
  - MISSILE_CLOSE
  - REPULSOR_LEFT
  - REPULSOR_RIGHT

## Safety Rules
- Do not allow unknown device takeover.
- Only control paired, trusted, user-approved devices.
- Admin mode required for device control, suit control, recording, code upgrades, and security changes.
- Guest mode only allows safe questions, voice changes, and basic HUD controls.
- Code self-upgrades must create backups, run tests, and require confirmation.
