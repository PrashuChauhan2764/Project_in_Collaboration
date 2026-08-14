# Project_in_Collaboration
This repo cotain the very first of our collaborative project.


### Current Implementations ideas:
1. free rooms under free slots recommended
2. notes/description space for daily task, test_dates, imp ques talks



### Track Project

# version1:
- 12 hr format clock
- total free time
- select today by default
- room no
- days navigation

# version2:
1. free rooms dropdown

# version3:
- premium design
- compare schedule feature
- file upload option

# version4:
- more accurate common free slots

# Version5:
- pink color to differenciate
- remove extra labels under scedhule upload sections keep only pdf names
- try to deploy

# Versin6:
- added pdf download option without functioning
- save button without functioning

# Version6.1:
- reduce unecessary details below of the pdf, to make the pdf of 1 page only while download


# Version6.2:
- some color updates

# Version7:
--- but the code is messy html,css,js ----------
- upload file option at centre in schedule section
- added show parsed schedule in scheduleB also
- color difference in light/dark orange in class
- time start from 8am not 9am

# Version7.1:
- schedule/compare text bold
- show "class" instead of Busy text change it
- show download pdf when both schedule uploaded and show it below the common free slots table at centre

# Version8:

* Replace fake room data with **real available rooms**.
* Store room availability in a separate **JSON file** instead of `index.html`.
* Allow adding **any number of rooms/classes** with their available time slots.
* When a user uploads their schedule, detect their **free time slots**.
* Show real available rooms according to those free slots.
* Display rooms in **block-wise order** (e.g., `4102`, `4104`).
* Prioritize rooms **close to the previous or next class** when showing results.
* Make the room data easy to update without changing the HTML code.

# version8.1:
* Add a **“Sort By”** option when viewing free rooms.
* Add dropdown options:

  * **Block**
  * **Nearby**
* Sort rooms by **block number** when “Block” is selected.
* Support **multi-digit block numbers (1–12)**.
* Correctly interpret room numbers, e.g.:

  * `4104` → Block 4, Floor 1, Room 04
  * `10201` → Block 10, Floor 2, Room 01
* When “Nearby” is selected, prioritize rooms close to the user’s **previous or next class**.


# version8.1.1
- sort by option update from white background to black and text with black







#  Future Features ideas:
by claude----
Next steps, whenever you're ready:

Backend + JSON file — instead of hardcoding SCHEDULE in the HTML, move it to a schedule.json served by a small Flask/Express backend. This makes step 2 (auto-updating) possible without touching the webpage code.
Daily Puppeteer script — logs in, waits for you to click the captcha, downloads the PDF, and overwrites schedule.json if anything changed.
PDF diffing — so it only flags/updates when the timetable actually reschedules, rather than blindly trusting a stale cache.

