# yearround
Yearround is a circular calendar, implemented in JavaScript using HTML5 canvas element.

It was created just because I wanted to see how such a calendar would look like.
Color scheme was inspired by https://drive.google.com/previewtemplate?id=1Cyg3kqR3Gd0hdTv_N7s2khX4Z9l5wQoVnRK6L-zI7pY&mode=public#

yearround in action: http://www.blasux.ru/static/yearround.html

Year 1010: http://www.blasux.ru/static/yearround.html#1010

Calendar accepts following parameters:
 * rot -- rotate to current week
 * mon -- first day of week is monday
 * nohl -- do not highlight days from Jan 1 to today, make all days white
 * <year> -- show calendar for <year> instead of current year. implies nohl, no rot

Example, monday-first calendar of 2002: http://www.blasux.ru/static/yearround.html#mon,2002


If you are a Firefox user, it will take advantage of Date().toLocaleFormat() to translate month and day names.
