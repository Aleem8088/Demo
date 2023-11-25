git config --global user.name "mohammed-kaif-sheikh"

git config --global user.name "mohammedkaif235@gmail.com"

git config --list

mkdir Dev
cd Dev

git init

git remote add origin "https://github.com/mohammed-kaif-sheikh/Demo.git"

git pull origin main //default branch of the repository

git status    //for checking  what files are not uploaded.

git add filename.txt //command to add a single file to the staging area 

git config core.autocrlf true // to avoid the warning of lf(linefeed) getting replaced by crlf(carriage return line feed)

git commit -m "created new text file for demo purpose" //commit with mesages to the changes committed to track the purpose of the commit

git  add -A 

git add . //both the previous commands can be used to add all the files to the staging area

git commit// this will commit and open an editor to add a mesage for the commit







