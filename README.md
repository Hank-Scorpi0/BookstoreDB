# Modifying and Creating a DB using a TKinter UI
Libraries
  sqlite3
  tkinter

Modules
  Backend
  Frontend
  
  
# Frontend

The code for the user interface starts at line 41. This uses basic grid/pack methods to create a window to workout of. 

For each of teh buttons you will see a "Command" element that references the functions defined in the lines preceeding line 41. 

These funcitons reference the back end. 


# Backend

Each function defined on the backend can be associated to a button on the front. connect() looks to see if a database already exists and creates one if a DB is not found. 

All backend functions can be executed within the command line with examples starting at line 49. 

# Making an executable

In command line:
  pip install pyinstaller
    #Navigate to the folder our script is located in
  pyinstaller --onefile --windowed Frontend.py
  
  When you run the exe for the first time, the backend script will create a new blank DB file for you to start adding data. If you have data that you would like the EXE to use simply copy and paste it into the folder with the EXE prior to running. 
