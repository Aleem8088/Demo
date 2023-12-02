//intro 
//installation


git config --global user.name "mohammed-kaif-sheikh"

git config --global user.name "mohammedkaif235@gmail.com"

git config --list

mkdir Dev
cd Dev

git init

//folowing commands for pulling the files from github
git remote add origin "https://github.com/mohammed-kaif-sheikh/Demo.git"

git pull origin main //default branch of the repository,main is the branch name


//following commands to add and commit files to github(single and multiple)
git status    //for checking  what files are not uploaded.

git add filename.txt //command to add a single file to the staging area 

git config core.autocrlf true // to avoid the warning of lf(linefeed) getting replaced by crlf(carriage return line feed)

git commit -m "created new text file for demo purpose" //commit with mesages to the changes committed to track the purpose of the commit

git  add -A 

git add . //both the previous commands can be used to add all the files to the staging area

git commit// this will commit and open an editor to add a mesage for the commit

 git commit -a -m "modified abhi.txt to add as well as to commit at once"

 git log// log of the changes
 

 //////to revert a file 

cat>>revert.txt
git add
git commmit -m "revert"
git checkout 'ec7a9456' revert.txt // from the previous commit first 
cat revert.txt
ec7a9456

how to pull the data from github
git pull
git fetch+merge
git clone "URL"

ssh is a protocol that provides user a secure access to the remote server over an untrusted network. It uses public key authentication . also it uses encryption using encryption algo (RSA).




branches are for making changes into an existening directory by copying 
git branch // to know the present branch
git branch fbranch /// to create a branch with an image of the master branch
git checkout fbranch //to switch or move to that particular branch
git merge// from 
