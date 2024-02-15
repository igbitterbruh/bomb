1. Install node.js if you don't have it. 
For windows download from the website: https://nodejs.org/en/download
For Linux (Ubuntu/Debian) use these commands:
`curl -fsSL https://deb.nodesource.com/setup_16.x | sudo -E bash - &&\ sudo apt-get install -y nodejs`
next:
`sudo apt-get install -y nodejs`

2. prepare a folder. 
Clone this repository (in linux just use `git clone https://github.com/igbitterbruh/bomb`)

3. Install the libraries 
For Windows: run cmd in the folder and type `npm install` or run the **npm_install.bat** file 
For Ubuntu: run console in the folder and type the command `npm install` 

4. Configuration 
In the **index.js** file in the 3rd line you can set the URL of the website, change the values responsible for sending requests to the website (if you know what and how you can modify this, the default is set optimally) 

5. Startup 
For Windows: run the **start.bat** file 
For Ubuntu: run the console in the folder and then use the command `node index.js`

# Attention!
you use this guide at your own risk! Performing attacks on large sites or government sites is illegal!
I recommend using this to test the security of your own sites!

Used package (It is not mine): https://www.npmjs.com/package/kira