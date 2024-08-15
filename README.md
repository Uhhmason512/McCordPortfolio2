AutomationMacro

During my time with Boeing I noticed a lot of data needed to be added manually. This gave me the idea to create an automation macro, inspired from the "sneaker bots"  I used to purchase in highschool to buy and sell Jordans and Yeezys easily.

Essentially, the listeners will listen track your keyboard events and mouse clicks to then replay them on your screen. This can be done as many times as you desire. 

If an excel sheet is uploaded with one column of data the program can copy the data from each row to your screen one at a time depending on the index of your playback. So if you have [spotify; apple; pandora] in a column then on the 2nd playback it can copy apple to the screen.

The program can also copy text from the screen to a separate excel through pyTesseract. pyTesseract is a pip that'll take a screenshot of your screen and then match this screenshot against different saveds texts in the google Tesseract OCR (must download for script to work) to output the text seen on the screen. This is very useful for sites/programs without an open API where data can't be called easily.

Working around Boeing restrictions was hard. I wanted to toggle mouse output during recording but I wasn't able to get full access to pynput functionalities.
