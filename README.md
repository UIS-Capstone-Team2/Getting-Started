# How To Set Up Your Dev Enviroment
For this guide I am assuming your using windows 10, most of this should work for 7 too
## Step 1: Install Git
[Git](https://git-scm.com/download/win) is the version control tool we will be using. It always us to all work on the same code base and not steop on eachothers toes. Download the 64 bit version (unless you need 32 for some reason). Just run it and except all the defaults. The one that says checkout windows style and commit Unix style is important. Make sure that option is selected.

## Step 2: Install Node.js on Windows 10
[Node.js](https://nodejs.org/en/download/) This is the language we are going to be using. It is very similar to Javascript. Download and install the 64bit LTS version. It doesn't really matter if you pick the LTS or MSI but for concistancy sake pick the msi and accept all the defaults. 

## Setp 3: Install a Text Editorr
Don't use notepadd. I will give you 3 options and pick your posion. This is really a personal decison.
[atom](https://atom.io/)
[notepad++](https://notepad-plus-plus.org/)
[sublimeText3](https://www.sublimetext.com/3)

##  Set 4: Install Ember.js
[Ember.js](https://guides.emberjs.com/v2.0.0/getting-started/) This is the framework we will be using. It basically gives you a bunch of prebuilt functions and templates. We already have all the dependancies for it so now just install it by opening a powershell prompt and typing

```npm install -g ember-cli```

```npm install -g phantomjs2```

and we are done, well with installing stuff

## Baby's First App
So I am not sure how familar you all are with comand line but it will become your best friend. In that same powershell prompt type
```cd```
That stands for change directory and without any parms will go to your home directory. Now type 
```ls```
This will list all the files and folders in the current directory. Now we are going to create a new one called projects
```mkdir projects```
That is make a new directory called projects. Now cd into that folder
```cd projects```
Now we will create our first Ember app
```ember new my-new-app```
That will create a new directory called my-app and start making all the files ember needs. It should look something like ![this](https://www.dropbox.com/s/s1azvi2wkqimqc1/Screenshot%202017-01-23%2021.10.10.png?dl=0)

