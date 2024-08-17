# notion-enhancer-app.asar
Since Notion-enhanced is not updated anymore, and so i dont have to do the process each time i am on a new linux machine, here is the app.asar that makes notion-enhanced to work.

# How-to

### Install notion-enhancend 

```terminal
$ sudo pacman -S notion-app-enhanced
```  

### Clone this repo on your machine
Pick any folder on your machine and clone the repo:
```terminal
$ git clone https://github.com/pedropmelojs/notion-enhancer-app.asar.git
```  
Open the folder:
```terminal
$ cd notion-enhancer-app.asar/
```  
And then extract the file:
```terminal
$ tar -xvzf app.asar.tar.gz
```  
Replace the notion-enhanced app.asar with the one from this repo
```terminal
$ cp app.asar /opt/Notion\ Enhanced/resources/app.asar
```  
### And Voila!
![alt text](https://raw.githubusercontent.com/pedropmelojs/notion-enhancer-app.asar/main/Notion.png) 

##### PS: The extracted files may be large. But its mostly the extracted files from the original app.asar that where modified, so you can check or modify it yourself.