<div align="center">

# PrettyRoutine

**Your semester, at a glance.**

A clean, downloadable class routine for BRAC University, built around the courses and sections you take.

✨<a href="https://ziswhyzis.github.io/prettyroutine/" target="_blank" rel="noopener noreferrer">**Open PrettyRoutine Website**</a>✨

</div>

---

## What it's for

No more piecing your routine together from different places or **having an ugly routine saved**. After confirming advising, select your courses and sections, and PrettyRoutine fills in the relevant class details—faculty, rooms, weekly schedule, and available midterm and final exam information.


## Made for

**Students**  
Build your semester timetable, keep exam dates close, and export it as an image to save on your phone or print. ✨


**Student Tutors (STs)**  
Add the courses you tutor and set your consultation hours. Your ST slots appear alongside your classes, so you can see your week in one place.


## Features

- Course → section selection
- Automatically filled faculty, rooms, class times, and exam details (where available)
- Weekly timetable with clash highlighting
- Optional ST courses and consultation slots
- PNG export for saving, sharing, or printing
- Themes, with preferences saved in your browser


## Run locally

No build tools or installation required.

```bash
git clone https://github.com/ziswhyzis/prettyroutine.git
cd prettyroutine
python3 -m http.server 8000
```

Open [localhost:8000](http://localhost:8000) in your browser.


## Notes

Routine data comes from the [BRACU Connect data feed](https://usis-cdn.eniamza.com/connect-migrate.json). The available information may change or be incomplete, so double-check details when needed.


### *feedbacks are much appreciated*
