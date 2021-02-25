## It took me 2 whole hours to figure out but in the end I got it done!
## I didn't want to have to keep opening anaconda then typing "jupyter notebook" over and over again every time I wanted to run jupyter lab so I made it a double click shortcut on my taskbar with a nice icon :)

### 1. Change whatever browser you'd like Jupyter to run in as your Default Browser 
### 2. Go to "C:\ProgramData\Anaconda3\Scripts\activate.bat" and right-click copy it. Rename it "activate_jupyter.bat"
### 3. Open your new bat file and at the very bottom right before ":End", insert "@CALL jupyter notebook"
### 4. Save and close your new bat file
### 5. Make a desktop shortcut linked to your "activate_jupyter.bat" file (Change the icon if you'd like)
### 6. Drag your new .exe file to the task bar and Viola! Works like a charm! 
