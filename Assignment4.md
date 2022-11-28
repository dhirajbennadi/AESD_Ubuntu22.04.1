#Mandatory Installations


sudo apt-get install make
sudo apt-get install binutils
sudo apt-get install build-essential
sudo apt-get install diffutils
sudo apt-get install gcc
sudo apt-get install g++
sudo apt-get install bash
sudo apt-get install patch
sudo apt-get install gzip
sudo apt-get install bzip2
sudo apt-get install perl
sudo apt-get install tar
sudo apt-get install cpio
sudo apt-get install unzip
sudo apt-get install rsync
sudo apt-get install file
sudo apt-get install bc
sudo apt-get install findutils


# Cloning Buildroot
Clone the link: https://github.com/buildroot/buildroot/tree/2022.02.x

cd buildroot

git checkout --track origin/2022.02.x

cd ..

git submodule add ./buildroot/
git add .
git commit -m "Message"
git push

Go to your repo and check if buildroot is added in the repository


