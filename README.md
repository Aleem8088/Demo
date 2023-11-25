git config --global user.name "mohammed-kaif-sheikh"

git config --global user.name "mohammedkaif235@gmail.com"

git config --list

mkdir Dev
cd Dev
git init

git remote add origin "https://github.com/mohammed-kaif-sheikh/Demo.git"

git pull origin main

git status    //for checking  what files are not uploaded.

git add filename.txt //command to add the file to the staging area 

git config core.autocrlf true // to avoid the warning of lf(linefeed) getting replaced by crlf(carriage return line feed)

$ git commit -m "created new text file for demo purpose" //commit with mesages to the changes committed to track the purpose of the commit






