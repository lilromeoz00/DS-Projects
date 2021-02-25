## I didn't want to have to keep opening anaconda then typing "jupyter notebook" over and over again every time I wanted to run jupyter lab so I made it a double click shortcut on my taskbar with a nice icon :) Tutorial Below!

### 1. Change whatever browser you'd like Jupyter to run in as your Default Browser 
### 2. Go into anaconda and type the command "jupyter notebook --generate-config"
### 3. Find your .jupyter files (In \users usually) and right-click edit the notebook_config.py file
### 4. Cntrl F and find "NotebookApp.notebook_dir"
### 5. Inside that line, Uncomment and Unindent the line.
### 6. Where you the the = '' you need to put your directory of choice which hosts your files
### 6b Ex. c.NotebookApp.notebook_dir = r'C:\Users\jordan'
### 7. Go to "C:\ProgramData\Anaconda3\Scripts\activate.bat" and right-click copy it. Rename it "activate_jupyter.bat"
### 8. Open your new bat file and at the very bottom right before ":End", insert "@CALL jupyter notebook"
### 9. Save and close your new bat file
### 10. Make a desktop shortcut linked to your "activate_jupyter.bat" file (Change the icon if you'd like)
### 11. Drag your new .exe file to the task bar and Viola! Works like a charm! 
