# 🌙 Ramadan London 2026

A single-page companion website for Muslims observing Ramadan in London: prayer times by mosque, countdowns to Suhoor and Iftar, and daily duas.

**Live site:** https://radiant-frangollo-4194fd.netlify.app

## Why I built this

During Ramadan I kept switching between different apps and websites to check prayer times, the Hijri date and daily duas. As a Muslim myself, I wanted one simple, clean page with everything in it, made for people in London.

If it helps even one person stay consistent or feel more connected during Ramadan, that's more than enough.

## Features

- Prayer times for 17 London mosques, chosen from a dropdown
- The next prayer is highlighted automatically
- Live countdowns to Suhoor and Iftar
- Today's Gregorian and Hijri dates
- A fasting calendar for the month
- A collection of duas and hadith for daily reflection
- Dhikr reminders (SubhanAllah, Alhamdulillah, Allahu Akbar)
- Responsive layout that works on phones

## Tech

- HTML and CSS for the structure and styling
- JavaScript for the countdowns, mosque selection and calendar
- `Intl.DateTimeFormat` with the Islamic calendar for the Hijri date
- No backend. Everything runs in the browser, hosted on Netlify

## Run it

Clone the repo and open `index.html` in a browser:

```bash
git clone https://github.com/mubarak-jimoh/ramadan-london-2026.git
```

## What I'd improve

Prayer times are currently stored in the page. The next step is to load them from a prayer times API so they update every day without me editing the code.

---

May Allah accept our fasts, prayers and good deeds. Ramadan Mubarak 🌙
