git config --global user.email "your-email"
git config --global user.name "your-name"

mkdir Sources
cd Sources/

git clone git@github.com:limacat76/Hades-Desktop.git
^ it will give an error

ssh-keyscan -t rsa github.com >> ~/.ssh/known_hosts
ssh-keygen -t rsa -b 4096 -C email
ssh-add ~/.ssh/id_rsa

copy and paste your key on github

sudo apt-get install xclip
xclip -sel clip < ~/.ssh/id_rsa.pub

now clone

git clone git@github.com:limacat76/Hades-Desktop.git
cd Hades-Desktop/

optional: switch to branch
git checkout -b gh-20170802.notes origin/gh-20170802.notes

