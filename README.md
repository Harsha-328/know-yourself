# Know Yourself 🧠🩺

A single-page wellness & cognitive self-assessment web app — test your IQ, check your health index, gauge stress/burnout risk, and score your sleep quality, all in one place.

## Features

- **🧠 IQ Test** — 10 randomized questions each attempt (4 easy, 4 medium, 2 hard, drawn from a pool of 30), with a live timer, difficulty progression, estimated IQ score, percentile, and a Verbal/Pattern/Logic/Numerical strength breakdown.
- **🩺 Health Index & Diet Engine** — calculates BMI, daily calorie target (Mifflin-St Jeor), hydration target, and an overall 0–100 wellness score, plus a personalized diet plan and daily routine schedule.
- **⚡ Stress & Burnout Index** — a quick pulse-check on work hours, pressure, fatigue, and digital breaks, producing a burnout risk score and tailored tips.
- **🌙 Sleep & Recovery Score** — evaluates bedtime consistency, caffeine intake, pre-bed screen use, and morning energy to produce a recovery score.
- **📈 My Reports** — every attempt across all four assessments is saved automatically (via browser local storage), so you can compare your scores before vs. after over time.
- **🔗 Share** — built-in share button (native share sheet or copy-link fallback) to send the app to friends.
- **🖨️ Print Summary** — printable IQ and Health reports.

## Tech Stack

- Plain HTML, CSS, and vanilla JavaScript — no build step, no dependencies to install
- [Tailwind CSS](https://tailwindcss.com/) via CDN for styling
- Google Fonts (Plus Jakarta Sans)
- Browser `localStorage` for saving assessment history per device

## Usage

Just open `index.html` in any modern browser — no server or installation required. All data stays on your device.

## Disclaimer

This is an informational self-discovery tool, not a substitute for professional medical, psychological, or clinical assessment.
