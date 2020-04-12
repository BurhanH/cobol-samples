# cobol-samples
[![GitHub](https://img.shields.io/github/license/mashape/apistatus.svg)](https://github.com/BurhanH/cobol-samples/blob/master/LICENSE)
[![Build Status](https://travis-ci.org/BurhanH/cobol-samples.svg?branch=master)](https://travis-ci.org/BurhanH/cobol-samples)
[![Codacy Badge](https://api.codacy.com/project/badge/Grade/03c8e440b8334a959403f2bc04764474)](https://www.codacy.com/manual/BurhanH/cobol-samples?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=BurhanH/cobol-samples&amp;utm_campaign=Badge_Grade)

## Main purpose

The idea is to learn COBOL programming language. (Just for fun!)

![alt text](https://github.com/BurhanH/cobol-samples/raw/master/HelloWorldCOBOL.png "COBOL Hello World program") <br>

### How to 

Before start make sure that you have COBOL compiler in your Operation System. In next section I will show an example for Ubuntu Linux.

### How to install compiler Ubuntu Linux:
```
sudo apt install open-cobol
```

### How to write your first program

Use any text editor to create a file with extention .cob (or .cbl).
Add a code ([HelloWorld.cbl](https://github.com/BurhanH/cobol-samples/blob/master/code/HelloWorld.cbl)).
Then run compiler to get executable file:
```
cobc -x YourSuperPupperProgram.cbl
```
and last one, execute a file:
```
./YourSuperPupperProgram
```

Ta-dah! Congratulations! Your first COBOL program is working!

### Extra

I'm using Visual Studio Code as IDE and [Syntax highlighting plugin for COBOL](https://marketplace.visualstudio.com/items?itemName=bitlang.cobol)
