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
SmartScreen may warn once about an unrecognised app. Choose **More info**,
then **Run anyway**. It installs for the current user only — no admin prompt —
and adds a Start menu and desktop shortcut.

### Privacy guarantee

**100% of ScreenFeel's AI runs on private models.** Every lens, every
follow-up question and every automatic title is answered by a model our
inference provider runs on its own hardware, under zero data retention. Your
capture is read for your answer and is then gone: never handed to a consumer
AI service, never written to a log or a dataset, never turned into training
data. There is no cheaper second path we fall back to, and no setting that
turns this off.

- **The private tier, never the anonymous one.** Inference providers also sell
  a cheaper *anonymous* tier: it hides who you are, but an outside AI lab
  still reads what you sent. ScreenFeel does not use it, for anything. It
  calls only open-weight models the provider hosts itself, so no third-party
  lab is ever in the path.
- **Read once, then nothing is left.** Your image and its answer exist for the
  length of one request and are not retained afterwards. Nothing is stored
  that could leak later, and nothing survives to be trained on. Your account
  does not travel with the request either — the model host sees our operator
  key, never you.
- **Checked, not just promised.** Which models we call is configuration, so it
  is verified rather than trusted: a check before every deploy reads the
  provider's live catalogue and fails if any model we would call is not marked
  private.

The full policy — what stays on your device, what leaves it, what the service
keeps and how to delete it — is at
[screenfeel.app/privacy](https://screenfeel.app/privacy).

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
  kept by nobody — a private model, zero data retention, never training data.
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
