Lucas Marble
http://a2-lucasmarble.onrender.com

## Simple Hurricane Database

This is a simple hurricane database that you can interact in. It has 4 fields: Name, Year, Wind speed, and Air pressure. To submit a storm, you must input a name and year. You do not have to input a wind speed or air pressure. One thing is that each hurricane's name and year is unique. So, if you submit a storm that has the same name and year, instead of putting in a new entry, it will instead update the storm with said name and year. To delete a storm, simply type the name and year and press the delete button.

There is a category attribute that you do not submit, because the server figures it out for you. Because the category of a hurricane is determined solely on wind speed, it will adjust accordingly. It will even change accordingly if you modify existing data.

The input boxes and buttons are formatted with a flex display spaced around by row.


## Technical Achievements
All of this information is on one HTML page. The table will appear after one submission or deletion. It will disappear if you reload the page, but it'll come back after a submission or deletion. It was pretty hard to figure out how to make the table appear each time it got an update of any kind, because I had to assume the format correctly for it every time.

There is the ability to modify existing data. Simply type the same name and year, and change the wind speed and/or air pressure, and the table will adjust accordingly. If you wish to change the name or year, you must delete it and add it back again. This wasn't too difficult to figure out, I just had to make sure the program knew if it was receiving information it already had (the name and year). If it didn't, it would add it. If it did, it would modify it.

### Design/Evaluation Achievements

Depending on what category the hurricane is, the color of the row will change. This is because each category on the Saffir-Simpson Scale is usually associated with a color (for example, category 5 is usually pink). This one was very challenging, because I had to determine when it was reading from the windspeed, which is what determines category. However, because the windspeed is always the third key, I ended up hard coding that when it was on the third key, it would determine the color.
