### BookStore APP
**Build a Book Inventory Desktop GUI and Database App by Python**

A program that stores this book information: Title, Author, Year, ISBN
User can:
- view all records
- search an entry
- add entry
- update entry
- delete
- close
#### create the frontend of GUI
1. divide the interface into 2 area
2. 4 text and 4 entries in upper area
3. 1 ListBox + 6 bottons in lower area

#### create the backend of functions
- connect
- insert
- view 
- search
- delete
- update

#### combind the frontend with backend code
1. create command for each button by create command function
2. show the information in 4 entry areas
3. get the selected row from event : click

#### Create exe app
1. install pyinstaller:
    - pip install pyinstaller
2. create exe app from the main .py file, here is bookstore.py
    - pyinstaller --onefile --windowed bookstore.py