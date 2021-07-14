# qt_qss_style
Qt styles in .qss 

https://github.com/SEB103/qt_qss_style.git


## Git global setup

* git config --global user.name "Sergey Burkin"
* git config --global user.email "sergeyburkin@gmail.com"

## Create a new repository

* git clone https://github.com/SEB103/qt_qss_style.git
* cd provis
* touch README.md
* git add README.md
* git commit -m "add README"
* git push -u origin master

## Push an existing folder

* cd existing_folder
* git init
* git remote add origin https://github.com/SEB103/qt_qss_style.git
* git add .
* git commit -m "Initial commit"
* git push -u origin master

## Push an existing Git repository

* cd existing_repo
* git remote rename origin old-origin
* git remote add origin https://github.com/SEB103/qt_qss_style.git
* git push -u origin --all
* git push -u origin --tags
