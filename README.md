# S.M.E — Streams Made Easy

Installers and automatic updates for **S.M.E**, a Windows desktop viewer for Twitch with a built-in voice assistant, Jarvis.

This repository only hosts releases. It contains no source code.

## Install

1. Open [Releases](../../releases/latest) and download `S.M.E-<version>-setup.exe`.
2. Run it. The installer isn't code-signed, so Windows SmartScreen may warn you: choose **More info → Run anyway**.
3. Once installed, S.M.E keeps itself up to date: new versions download in the background and install when you close the app (Settings → Jarvis → Automatic updates).

A portable `.exe` is also attached to each release. It doesn't update itself; download a new copy instead.

## Your data stays on your PC

Your Twitch sign-in, settings, voice training and Jarvis's memory are stored only in your Windows profile (`%APPDATA%\S.M.E`). They are never part of a release.

## Requirements

- Windows 10 or 11 (64-bit)
- A Twitch account (sign in once inside the app)
