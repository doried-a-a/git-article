# A simple webpage
This project is used as part of [this article](https://oufok.com/article/view/bbf4ed3535714d8a8bc3d8f5e359a512) to demonstrate how to use Git.  

## How to work with this project

### First, make a copy of this project
You won't have permissions to push to this project. Hence, you can "fork" it (or make a copy of it).  
A fork is a copy of this project that you own, so you will be able to do whatever you want with it.  
You will find the fork button in the upper right conrner of the repo's main page.  


### Second, clone the repo locally
Now that you forked the repo, from your fork, Click the "Code" or "Clone" green button, select HTTPS, and copy the repo's link.  

Go to your terminal, go (cd) to the place you want to clone (or download) the project into, and write:  


    git clone $THE_URL_YOU_COPIED # replace this
    cd git-article

### Try to run it
Go to the place where you cloned the project, and double click the file "index.html" to view the webpage you just cloned!

### Play with it!
Try to change the content of this page, and once you're done you can try (from the directory git-article):

git commit -am 'Doing some changes.. here you can write whatever you want to describe your changes'
git push # to send this commit to the remote repo