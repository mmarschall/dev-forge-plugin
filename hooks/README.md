# Hooks

This directory contains hook configuration files for event handling.

## Configured Hooks

### Notification Hook
Triggers when Claude sends a notification. Uses macOS text-to-speech to announce "Claude needs you".

### Stop Hook
Triggers when Claude stops processing. Uses macOS text-to-speech to announce "Claude is done".

Both hooks use the Ava voice on macOS for audio notifications.

## Configuration

Hooks are defined in `hooks.json`. Each hook can execute commands or scripts in response to Claude Code events.
