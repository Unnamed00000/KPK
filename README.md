# KPK

Dore og vinduer - lokal arbejdsseddel.

Open `index.html` in a browser.

Features:

- calendar with ISO week numbers;
- separate local saved entries for each date;
- Danish as the default language, with English, Arabic, and Russian available;
- employee name, employee number, week, and workday;
- work rows for place, series, start time, end time, and calculated time;
- meeting row for place `114`;
- hidden automatic pause subtraction for `09:00-09:20` and `12:00-12:20`;
- Monday to Thursday work time `06:00-15:05`, Friday `06:00-15:00`;
- time shown in hundredths of an hour, for example `45` minutes is `0,75`;
- copy and print buttons for the final text.
- PWA support with installable app metadata, offline cache, and app icons.

All data is saved locally in the current browser with `localStorage`.

PWA installation requires opening the app from `https://` or `localhost`; service workers do not run from a direct `file://` URL.
