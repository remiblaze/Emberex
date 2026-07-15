# Emberex — DJ-style resonant performance filter

![Emberex](https://raw.githubusercontent.com/RemiBlaze/Emberex/main/emberex-ui-screenshot.png)

**A single-knob performance filter built for sweeps, builds, and drops.**

Emberex is a resonant filter effect with drive, an LFO, and an envelope follower. One bipolar knob sweeps from low-pass to high-pass, with Bandpass, Comb, and Formant modes on tap for creative sound design across tech house, house, and electronic music.

Fully **signed and notarized** for macOS as **AU, VST3, and Standalone**.

---

## 🚀 Download & Install
1. Go to the [latest release](https://github.com/RemiBlaze/Emberex/releases/latest).
2. Download **`Emberex_Installer.pkg`**.
3. Double-click it and follow the installer. Because it's **signed & notarized by Apple**, it installs cleanly — no security warnings, no right-click, no "Open Anyway."
4. Restart your DAW and rescan plug-ins.

Full guide: **[remiblaze.com/support](https://remiblaze.com/support/)**.

---

## 🎛️ Features

- **Bipolar filter knob** — one control sweeps from low-pass to high-pass (-100% to +100%).
- **Four filter modes** — LP/HP, Bandpass, Comb, and Formant.
- **Three slopes** — 12 dB, 24 dB, and 48 dB per octave.
- **Resonance** — from flat to a screaming resonant peak.
- **Drive** — pre-filter tanh saturation running at 4x oversampling.
- **LFO** — auto-filter motion with Sine, Triangle, Square, Saw, Custom, and Sample & Hold shapes, plus adjustable Rate, Depth, and Smoothing.
- **Tempo sync** — LFO Sync snaps to note divisions, and Loop Sync locks motion to the host bar/beat grid (1/64 up to 32 Bars).
- **Envelope follower** — Env Follow amount with adjustable Attack (0.1–50 ms) and Release (10–500 ms) so the filter reacts to input dynamics.
- **MIDI-aware modulation** — Key Track, Velocity Link (targeting Resonance or Drive, with Linear / Log / Exp curves), and Frequency Lock.
- **TCR (Transient-Controlled Resonance)** — spikes the filter Q on kick and snare hits, with an adjustable Intensity.
- **Ignition** — instantly snaps the filter open for a fast build/drop gesture.
- **Formant Spread** — widens or narrows the vowel character in Formant mode.
- **Drift & Seed Lock** — organic cutoff wander with a lockable seed for reproducible motion, plus a Roll button to generate a new locked pattern.
- **Dry/wet Mix** — parallel filter blending (0–100%).
- **Output gain** — level matching from -24 dB to +6 dB.
- **Phase reverse** — polarity flip on the output.
- **A/B comparison** — switch instantly between two parameter states.
- **Randomize** — one-click parameter randomization.
- **Preset save/load** — export and share `.preset` files.
- **Resizable UI** — scales from 440x560 up to 900x860.

---

## 🔬 Under the Hood

- **4x oversampled drive** — the tanh saturation stage runs through a half-band polyphase IIR oversampler and stays engaged for consistent, honest latency reporting.
- **DC blocker** — a 10 Hz high-pass on the output keeps the signal DC-free after saturation.
- **Anti-pop preset recall** — a short output fade freezes filter reads during preset and state changes to prevent clicks.
- **Reproducible modulation** — Drift wander and Sample & Hold randomness are seeded, so a saved project reloads to identical motion when Seed Lock is on.

---

## 💻 System Requirements
- macOS 15.0 or later
- Apple Silicon or Intel Mac (Universal Binary)
- Any AU or VST3 host (your DAW of choice)

---

## 🎚️ Factory Presets (22)

| Preset | Notes |
|--------|-------|
| Init | Clean starting point |
| Gentle LP Sweep | Subtle low-pass warmth |
| DJ High Cut | Classic DJ low-pass filter |
| Resonant Acid | Squelchy acid-style resonant filter |
| Bass Isolation | Deep low-pass for bass-only effect |
| Vocal Telephone | High-pass telephone/radio effect |
| Driven Filter | Saturated filter with grit |
| Subtle Warmth | Light low-pass with gentle drive |
| Build-Up HP | High-pass for tension builds |
| Drop LP | Deep low-pass for drops |
| Remi Blaze Sweep | Signature sweep with drive and resonance |
| The Deep Rise | Slow high-pass build with resonance |
| Sub-Cleaner | Tight low-cut for sub cleanup |
| Rhythmic Grit | Driven mid-band grit |
| 4-Bar Wash | Long high-pass wash |
| Sub-Surgical | Surgical low-cut |
| Comb Metallic | Metallic comb-filter tone |
| Vowel Sweep | Formant vowel sweep |
| Phase Ghost | Parallel, phase-tinged filtering |
| Sassy Formant | Vocal formant character |
| Sub-Anchor Brickwall | Steep sub anchor |
| Industrial Metallic 2 | Aggressive driven comb tone |

---

## 🐛 Bugs & Issues
Found a UI glitch, resize bug, or DAW-specific quirk? Please open an issue:
1. **[Issues](https://github.com/RemiBlaze/Emberex/issues)** tab → **New Issue**.
2. Include your macOS version, DAW + version, and steps to reproduce.

---

## 📄 License & Credits
- **Developer:** [Remi Blaze](https://remiblaze.com).
- **Framework:** [JUCE](https://juce.com).
- **License:** free under a proprietary [Freeware License](LICENSE) (see also our [terms](https://remiblaze.com/terms/)). Reverse-engineering, repackaging, binary redistribution, or reselling the compiled installer is strictly prohibited.

---

## Trademarks

All product names, company names, and logos mentioned herein are trademarks or registered trademarks of their respective owners. Any such references are used for descriptive or compatibility purposes only and do not imply affiliation with, endorsement by, or sponsorship from their owners.

VST is a trademark of Steinberg Media Technologies GmbH, registered in Europe and other countries.

Apple, macOS, Audio Units (AU), and Apple Silicon are trademarks of Apple Inc., registered in the U.S. and other countries.
