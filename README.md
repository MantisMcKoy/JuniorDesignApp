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

pip install Flask praw pandas numpy PyPDF2 nltk text2emotion datetime
