Various Commands I have used so far to configure or setup things

//Setup google chrome

wget https://dl.google.com/linux/direct/google-chrome-stable_current_x86_64.rpm

sudo yum localinstall google-chrome-stable_current_x86_64.rpm


// Run Google chrome
google-chrome &

//Set system date and time

timedatectl set-time "2023-04-10 20:58:01"
timedatectl set-ntp true


//Git clone from Github repo

git clone https://github.com/kelkarbc/letmelearn.git


//GitHub CLI Tool gh install

sudo yum-config-manager --add-repo https://cli.github.com/packages/rpm/gh-cli.repo
sudo yum install gh

// Configure gh login to Git-Github
gh auth login

git checkout delme.md
git add delme.md
git commit
git push https://github.com/kelkarbc/letmelearn.git

//Git config user name and email

git config --global user.name "BCK"
git config --global user.email "bckel@noreply.com"

//Git pull from github repo
git pull https://github.com/kelkarbc/letmelearn.git


