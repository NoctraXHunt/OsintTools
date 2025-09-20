# OSINT Toolz 🔎

OSINT Toolz is a compact and polished Python terminal tool for educational OSINT tasks.  
The tool combines phone number lookup, username availability checks, NIK lookup via API, and IP tracking — all presented with a clean ASCII banner and colored terminal output.

---

## Features

- **Phone Info**
  - Supports local Indonesian format (e.g. `08xxxx` → auto normalizes to `+62...`)
  - Shows international format, location hint, carrier/provider, timezone

- **Username Checker**
  - Checks across: Instagram, Twitter (X), TikTok, GitHub, Facebook, Reddit, YouTube

- **NIK Checker**
  - Calls NIK API and displays clean, formatted output
  - Ignores internal fields like `creator` and `status`, shows only relevant result fields
  - Includes extra info: age, zodiac, pasaran (if provided by API)

- **IP Tracker**
  - Accepts IP or domain (resolves domain to IP)
  - Uses public geolocation API to return country, region, city, ISP, timezone

- **UI**
  - Fixed ASCII banner (pyfiglet `slant`)
  - Colored terminal output with `rich`
  - Menu driven, auto-clear screen on actions

---

## Quick Start

1. Clone the repository:
```bash
git clone <repo-url>
cd <repo-folder>
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Run the tool:
```bash
python main.py
```

---

## Files in this repo

- `main.py` – main script (OSINT Tool)
- `requirements.txt` – python dependencies
- `README.md` – this file
- `assets/` – preview images for README/GitHub

---

## Screenshots / Preview Images

Included in `assets/`:
1. `banner.png` — ASCII banner preview
2. `menu.png` — Main menu screenshot mockup
3. `phone_lookup.png` — Phone lookup sample output
4. `nik_lookup.png` — NIK lookup sample output
5. `ip_tracker.png` — IP tracker sample output

Use these images in your GitHub repo's README to showcase the tool.

---

## Notes & Legal

- This tool is intended for **educational** and **research** purposes only.
- Do **not** use the tool to process or expose real personal data without proper authorization.
- NIK and other personal data are sensitive — use synthetic or permitted datasets only.

---

## License

MIT
