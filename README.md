# ScreenFeel — downloads

**Screenshot anything. Understand it.**

This repository exists to host the installer for **ScreenFeel**, the
privacy-first AI screenshot app for Windows. There is no source code here —
ScreenFeel is proprietary and its source is private.

### Download

**[Download for Windows](https://screenfeel.app/download)** — or grab the
latest installer directly from [Releases](../../releases/latest).

For Windows 10 and 11. Capturing, annotating and the local library are free
without an account; signing in switches on the AI lenses.

### Installing

The installer is not yet signed through the Microsoft Store, so Windows
SmartScreen shows a warning naming an **Unknown Publisher** — either
"Windows protected your PC" (choose **More info**, then **Run anyway**) or,
when SmartScreen cannot be reached, a dialog offering **Run** directly. This
is expected for a new unsigned installer and disappears once ScreenFeel
ships through the Microsoft Store. It installs for the current user only —
no admin prompt — and adds a Start menu and desktop shortcut.

### Verifying your download

Every release includes a `SHA256SUMS.txt` next to the installer. To check
that the file you downloaded is the file we published:

```powershell
Get-FileHash ScreenFeel-Setup.exe -Algorithm SHA256
```

The hash must match the one in `SHA256SUMS.txt` on the same release. If it
does not, delete the file and download again from
[screenfeel.app/download](https://screenfeel.app/download).

For security teams: the installer elevates nothing (per-user install, no UAC
prompt), the app reaches exactly one host (`screenfeel.app`), and it contains
no third-party scripts, analytics or trackers. The privacy policy at
[screenfeel.app/privacy](https://screenfeel.app/privacy) states what leaves
the device and when.

### What it does

- Capture a region of any display, any open window, or the whole screen — in
  any application. It can take over the **Print Screen** key and act as your
  machine's screenshot app.
- Annotate, crop, redact and beautify in a keyboard-first editor.
- Ask AI about a capture: explain it, read its text, translate it, turn a
  chart into CSV, diagnose an error on screen, or flag secrets before you
  share it.
- Everything you capture stays in a local library on your own device. When
  you run an AI lens, exactly one image is sent, read for the answer, and
  kept by nobody — zero data retention, never training data.
- Presenter tools for screen sharing: cursor glow, boxes, arrows and fading
  ink, drawn locally over any app.
- Interface in English, Spanish, German, French, Japanese, Korean and
  Simplified Chinese.

### Links

- Website — [screenfeel.app](https://screenfeel.app)
- Pricing — [screenfeel.app/pricing](https://screenfeel.app/pricing)
- Privacy policy — [screenfeel.app/privacy](https://screenfeel.app/privacy)
- Questions — [screenfeel.app/faq](https://screenfeel.app/faq)

### Issues

This repository does not track issues for the app. Support goes through the
contact link on [screenfeel.app](https://screenfeel.app).

---

© ScreenFeel. All rights reserved. The installer published here is licensed
for personal and business use of the application itself; it may not be
redistributed, repackaged, decompiled or reverse-engineered.
