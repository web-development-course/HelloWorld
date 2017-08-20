# Hello World
Follow this tutorial to create your first web application!

# Installations & Registrations
- Google Chrome [Download here](https://www.google.com/chrome/browser/desktop/)
- Node.js LTS [Download here](https://nodejs.org/en/)
- Visual Studio Code [Download here](https://code.visualstudio.com/Download)
- Now.sh [Download here](https://zeit.co/download)
 
# Create your Code Directory (one time only)
- Open Node.js command prompt (windows) or the terminal (mac)
- Go to your home directory (windows: `cd \` | mac: `cd ~`) 
- Create a new folder named Code (windows: `md Code` | mac: `mkdir Code`) 
- Enter into your new folder `cd Code`
- Install Sails.js `npm install -g sails`

# Create the HelloWorld Application
- In the Code directory, Generate the helloworld app `sails new helloworld` (your can change 'helloworld' with any other app name)
- Navigate into the new generated app folder `cd helloworld`
- Run the app `sails lift`
- Open Chrome and navigate to [your localhost](http://localhost:1337) to see the app
 
# Make Some Modifications 
- Open Visual Studio Code
- Open the `helloworld` folder (File > Open)
- Click on the `views` folder and click on the `homepage.ejs` file
- Change the text `A brand new app` and change it to any text you want
- Save the file

# Upload to Now.sh
- Open the now.sh app icon (in the top tollbar)
- Drag the entire `helloworld` folder into you app icon
- Wait for the deployment to finish

# Hooray! You now have your first published website
