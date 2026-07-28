<p align="center">
  <img src="assets/app-icon.png" width="144" height="144" alt="Zhenzhu app icon">
</p>

<h1 align="center">Zhenzhu</h1>

<p align="center">
  <strong>Understand Chinese. Stay in the moment.</strong>
</p>

<p align="center">
  A native Chinese popup dictionary for macOS with instant definitions,
  pinyin, sentence translation, OCR, HSK levels, and flashcards.
</p>

<p align="center">
  <a href="https://zhenzhu.app">Website</a>
  ·
  <a href="https://github.com/minhnd-dev/zhenzhu-releases/releases/latest">Download</a>
  ·
  <a href="https://zhenzhu.app/#help">Help</a>
</p>

---

## Read without leaving what you are reading

Select Chinese text in almost any Mac app and Zhenzhu explains it beside the
original content. It runs quietly in the menu bar, without a permanent window
or Dock icon.

### Select text

Select Chinese text to see pinyin and definitions instantly.

https://github.com/user-attachments/assets/d54cd612-c682-48bd-8c81-20ee040405e0

### Capture from an image

Press <kbd>⌥</kbd><kbd>⇧</kbd><kbd>S</kbd>, then drag around text you cannot
select normally.

https://github.com/user-attachments/assets/8ab2ecb0-ccf9-447e-94db-6bb767a01819

### What Zhenzhu can do

- **Popup dictionary:** Select Chinese text to see definitions, pinyin, HSK
  levels, and word-by-word analysis.
- **Sentence translation:** Understand a complete sentence without losing its
  original context.
- **Snip to Translate:** Capture text from images, paused video, PDFs, and
  interfaces where normal selection is unavailable.
- **Editable segmentation:** Correct word boundaries when a sentence needs the
  judgment of a human reader.
- **Local flashcards:** Save useful words and sentences for spaced-repetition
  review directly in Zhenzhu.
- **Optional Anki integration:** Preview and send polished cards to the Anki
  desktop app through AnkiConnect.
- **Flexible display:** Choose character forms, pinyin styles, HSK standards,
  panel placement, shortcuts, and capture behavior.

## Requirements

- macOS 15 or later
- Apple silicon or Intel Mac
- Accessibility permission for reading text you intentionally select in other
  apps

## Install

1. Download the latest `Zhenzhu-<version>.dmg` from
   [Releases](https://github.com/minhnd-dev/zhenzhu-releases/releases/latest).
2. Open the disk image and drag **Zhenzhu** into **Applications**.
3. Launch Zhenzhu. Its icon appears in the macOS menu bar.
4. Grant Accessibility permission when prompted to enable selected-text lookup.

Zhenzhu is signed with a Developer ID certificate and notarized by Apple for
distribution outside the Mac App Store.

## Updates

Zhenzhu checks for signed updates using
[Sparkle](https://sparkle-project.org). You can also choose
**Check for Updates…** from the menu-bar menu at any time.

The update feed and every downloadable release are cryptographically signed.
Zhenzhu verifies the signature before installing an update.

## Privacy

Your reading data stays on your Mac:

- Dictionary data, lookup history, vocabulary status, and flashcards are stored
  locally.
- Accessibility access is used to read text you intentionally select.
- Clipboard fallback is optional and can be disabled in Settings.
- Anki integration connects only to the local Anki desktop app.
- System profiling for update checks is disabled.

Learn more at [zhenzhu.app](https://zhenzhu.app/#privacy).

## About this repository

This public repository contains only official Zhenzhu release assets and its
signed update feed. The application source code and all signing credentials
remain private.

- Release downloads are published under
  [Releases](https://github.com/minhnd-dev/zhenzhu-releases/releases).
- The signed `appcast.xml` feed is maintained automatically on the `updates`
  branch.
- Release files and the update feed should not be modified manually.

If a download or update does not behave as expected, visit the
[Zhenzhu help section](https://zhenzhu.app/#help).
