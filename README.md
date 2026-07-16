# Akai MPK Mini MK3 - GarageBand Drum Preset Mapping

A custom, ready-to-import program preset (`.mpkmini3`) for the Akai MPK Mini MK3 that maps the 8 pads ergonomically to work seamlessly with GarageBand's default drum kits.

---

## 🛠️ The Problem

By default, the factory presets on the Akai MPK Mini MK3 split the drum kit across two pad banks (Bank A and Bank B):
- **Bank B** contained the lower drum elements (Kick, Snare, Closed Hi-Hat).
- **Bank A** (which is active by default when the controller powers on) only contained auxiliary elements (Toms, Crash, open hat, etc.).

This made playing standard beats impossible without constantly toggling between Bank A and Bank B.

---

## 🚀 The Solution

This repository provides **`GarageBandDrums.mpkmini3`**, which keeps the factory default knob CCs and arpeggiator controls intact, but restructures the pad note mappings:
- **Bank A** has been customized into an **Ergonomic Finger Drumming Layout**. You can now play a full kit (Kick, Snare, Closed Hat, Open Hat, Toms, Crash, and Clap) on a single bank.
- **Bank B** remains mapped to the factory-default **Chromatic General MIDI Layout** (consecutive MIDI notes 35–43, skipping hand clap).

---

## 🥁 Pad Layouts

Use the physical **Bank A/B** button on your MPK Mini MK3 to toggle layouts:

### Bank A (Red LED): Ergonomic Finger Drumming Layout (Customized)
*Optimized for comfort, placing the core groove components (Kick, Snare, Hi-Hats) under your primary fingers on the bottom row.*

| Pad | Row | MIDI Note | Note Name | Drum Sound |
| :--- | :--- | :--- | :--- | :--- |
| **Pad 1** | Bottom Left | 36 | C2 | Bass Drum 1 (Kick) |
| **Pad 2** | Bottom Mid-Left | 38 | D2 | Snare Drum |
| **Pad 3** | Bottom Mid-Right | 42 | F#2 | Closed Hi-Hat |
| **Pad 4** | Bottom Right | 46 | Bb2 | Open Hi-Hat |
| **Pad 5** | Top Left | 41 | F2 | Low Floor Tom |
| **Pad 6** | Top Mid-Left | 48 | C3 | Hi-Mid Tom |
| **Pad 7** | Top Mid-Right | 49 | C#3 | Crash Cymbal 1 |
| **Pad 8** | Top Right | 39 | Eb2 | Hand Clap |

### Bank B (Green LED): Chromatic General MIDI Layout (Factory Default)
*The default layout shipped with the Akai editor. It maps the first 8 consecutive MIDI drum notes (C2 to G2, skipping the clap).*

| Pad | Row | MIDI Note | Note Name | Drum Sound |
| :--- | :--- | :--- | :--- | :--- |
| **Pad 1** | Bottom Left | 35 | B1 | Bass Drum 2 |
| **Pad 2** | Bottom Mid-Left | 36 | C2 | Bass Drum 1 (Kick) |
| **Pad 3** | Bottom Mid-Right | 37 | C#2 | Side Stick (Rimshot) |
| **Pad 4** | Bottom Right | 38 | D2 | Snare Drum |
| **Pad 5** | Top Left | 40 | E2 | Electric Snare |
| **Pad 6** | Top Mid-Left | 41 | F2 | Low Floor Tom |
| **Pad 7** | Top Mid-Right | 42 | F#2 | Closed Hi-Hat |
| **Pad 8** | Top Right | 43 | G2 | Mid Floor Tom |

---

## 📥 How to Import the Program Preset

1. **Close GarageBand** (to release the USB MIDI port).
2. Open the **MPK Mini 3 Program Editor** on your computer.
3. Select **File > Open Program...** and open `GarageBandDrums.mpkmini3`.
4. Select a program slot (e.g., **Program 1**) in the editor.
5. Click **File > Send Program...** (or click the **S** icon next to the program slot number) to upload the program to your controller.
6. Open GarageBand, load a drum kit software instrument track, and test the pads!
7. **Important:** Make sure to select **Program 1** on your device (press and hold the **Favorites** button, then press **Pad 1**).

---

## 📂 Files in this Repository

*   **`GarageBandDrums.mpkmini3`**: The customized preset file ready for import.
*   **`Garageband.mpkmini3`**: The original, unaltered factory default preset (kept for backup).
*   **`Untitled.mpkmini3`**: The original raw device program export.
