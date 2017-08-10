# [Nybles](https://nybles.github.io/NyblesNews) 

In order to create your own Ghost blog for free and host it at Github pages, check the following instructions. These instructions were tested within Linux, if you know how to make it work for Windows or Mac OS, please let me know and I'll add the instructions here. [**Check out the Live Demo**](https://nybles.github.io/NyblesNews).


## Prerequisites
Before we start, you need to install some prerequisites:
- [**pip**](https://pip.pypa.io/en/stable/quickstart/): Python 2.7.9 and later comes with *pip* by default, so it won't will bother you.
- [**buster**](https://pypi.python.org/pypi/buster/0.1.3): a Python package.
- [**NodeJS**](https://nodejs.org/en/): make sure that your [NodeJS version is officially supported by latest Ghost release](http://support.ghost.org/supported-node-versions/).
- [**npm**](https://nodejs.org/en/): NodeJS package manager.
- [**knex-migrator**](https://github.com/TryGhost/knex-migrator): you will also need to run `knex-migrator init`

## Installing for the first time
#### 1) Download repo.

#### 3) Open the Terminal and navigate to the extracted folder. Run `npm install`.
![Run "npm install". This step will take several minutes.](http://i.imgur.com/jUBPv3h.png)

#### 4) Now we've Ghost installed. Let's start it's localhost server running `npm start`:
![Run the Ghost server at localhost for the first time using "npm start"](http://i.imgur.com/m49izT3.png)

#### 5) Ghost now will be live at [http://localhost:2368](http://localhost:2368). Let's create your user and configure Ghost for the first time: go to [http://localhost:2368/ghost](http://localhost:2368/ghost) and follow the instructions.
![Follow the Ghost instructions for the first time install.](http://i.imgur.com/lss8Rbw.png)

#### 6) Now you are at the Ghost Administrative Panel, personalize your page and create the desired content.
![Ghost Administrative Panel](http://i.imgur.com/lXhbMJK.png)
