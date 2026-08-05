# Project_in_Collaboration
This repo cotain the very first of our collaborative project.


### Current Implementations ideas:
1. free rooms under free slots recommended
2. notes/description space for daily task, test_dates, imp ques talks



### Track Project

1. version1 contains:
- 12 hr format clock
- total free time
- select today by default
- room no
- days navigation



#  Future Features ideas:
by claude----
Next steps, whenever you're ready:

Backend + JSON file — instead of hardcoding SCHEDULE in the HTML, move it to a schedule.json served by a small Flask/Express backend. This makes step 2 (auto-updating) possible without touching the webpage code.
Daily Puppeteer script — logs in, waits for you to click the captcha, downloads the PDF, and overwrites schedule.json if anything changed.
PDF diffing — so it only flags/updates when the timetable actually reschedules, rather than blindly trusting a stale cache.

