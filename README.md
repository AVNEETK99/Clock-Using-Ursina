# Clock-Using-Ursina

A clock is a device used to measure, keep, and indicate time. Clocks can be found in a wide range of styles and designs, from simple sundials and hourglasses to complex digital and analog devices. They can be used for a variety of purposes, including keeping track of the time of day, timing events, and serving as decorative items. Clocks can be powered by a variety of means, such as batteries, electricity, and mechanical mechanisms.

## Instructions to run the game

* Open the Github repository where the game code is hosted.

* Click on the green "Code" button and then select "Download ZIP" to download the code as a ZIP file.

* Extract the ZIP file to a folder on your computer.

* Open a command prompt or terminal window and navigate to the folder where you extracted the code.

* Type ```python clock.py``` and press Enter to start the game.

* Follow the prompts to play the game.

## Functionality of the code

* The first line imports everything from the Ursina library.
* The second and third lines import the datetime module and the math module, respectively.
* The ```update()``` function is defined to update the clock every frame.
* Inside the ```update()``` function, the current time is obtained using the ```datetime.now()``` function, and the hour, minute, and second are extracted from it.
* The text object that displays the time is created with the ```Text()``` function and is positioned at (0, 0.4) with a scale of 2.
* The hour, minute, and second hands are drawn using the ```hr, mn, and sd``` entities, respectively. The rotation of each entity is calculated based on the current hour, minute, and second.
* The ```draw_dots()``` function is defined to draw the small dots on the clock face that represent the minutes.
* The ```wall``` entity is created with the quad model, a scale of (15, 10), and a background texture.
* The ```clock``` entity is created with the ```circle``` model, a scale of 5, and a black color.
* The ```hr, mn, and sd``` entities are created with the ```quad``` model and different scales, colors, and positions.
* A loop is used to draw the small dots on the clock face using the ```Entity()``` function and the ```draw_dots()``` function.
* The ```Text()``` function is used to display the author's name below the clock face.
* The ```app.run()``` function is called to run the program.
