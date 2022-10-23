# TXT

TXT
 1. Create an external repository called TXT.
- `Create a new repository`
 2. Clone the TXT repository to the local computer.
- `git clone https://github.com/NeonilaH/TXT`
 3. Inside the local TXT, create the “new.txt” file.
- `touch new.txt`
 4. Add file under git.
- `git add new.txt`
 5. Commit the file.
- `git commit -m new.txt`
 6. Submit the file to an external GitHub repository.
- `git push`
 7. Edit the contents of the “new.txt” file - write information about yourself (name, age, number of pets, future desired salary). Everything should be written in TXT format.
- `nano new.txt`
```
first name: Neonila
last name: Hlovatska
age: 34
number of pets: 1
desired salary: 1000
```
 8. Push changes to an external repository.
- `git commit -m "add changes to txt file"`
---> `Git push`
 9. Create preferences.txt file.
- `touch preferences.txt`
 10. Add information about your preferences (Favorite movie, favorite series, favorite food, favorite season, side you would like to visit) in the file preferences.txt in TXT format.
 
- `cat > preferences.txt`
```
Favorite movie - None
Favorite TV series - None
Favorite season - Fall
Favorite food - Burger
The country I would like to visit - Norway
```
 11. Create a file sklls.txt add information about the skills that will be studied on the course in TXT format.
- `cat > skills.txt`
```
1.git bash commands
2. GitHub repository
3. Client Server Model
4. API testing in Postman
```
 12. Make a commit in one line.
- `git add skill.txt preferences.txt | git commit -am "add and commit 2 files at once"`
 13. Send 2 files at once to an external repository.
- `git push`
 14. Create a bug_report.txt file on the web interface.
- `Add file`
---> `Create new file`
---> `Commit new file`
 15. Make Commit changes (save) changes on the web interface.
- `commit changes`
 16. Modify the bug_report.txt file on the web interface, add a bug report in TXT format.
- `Open file`
---> Go to the pencil button `Edit this file`
```
bug report
Bug_id: 11111
Title: Missing white lines on the widget
Severity: Moderate
Priority: Medium
Environment: Xiaomi Redmi 8A, MIUI Global 12.5.2, 10 QKQ1.191014.001
Precondition: Desktop grid 5x5, font size Medium, zoom Medium
STR:
Add 6 widgets
Arrange widgets as in the attachment
AR: The widget in the center has a missing white bottom line.
ER: All widgets should have four white lines.
attachment:
https://bit.ly/3NOFgrJ
```
 17. Make Commit changes (save) changes on the web interface.
- `commit changes`
 18. Synchronize external and local TXT repository.
- `git fetch`
---> `git pull`
