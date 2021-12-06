# JuniorDesignApp

## Release Notes

## Installation Guide
### Install App
git clone https://github.com/Erickkbentz/JuniorDesignApp.git

cd JuniorDesignApp

git submodule init

git submodule update



### -- Setup Frontend and Prisma database client --
cd JuniorDesignFE
npm install

npm i -g prisma@latest

npm i @prisma/client@latest

prisma generate



### -- Setup Machine Learning --
cd ../JuniorDesignML

pip install Flask

pip install praw

pip install pandas

pip install pickle

pip install numpy

pip install PyPDF2

pip insall nltk

pip install text2emotion

pip install datetime
