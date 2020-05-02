|<center><h1> Getting Started </h1></center>
|:-------------------------|
|<ul>**Installations:**<li>Open the terminal and run the following commands:</li><ul><li>Install **Brew**: `sudo chown -R $(whoami):admin /usr/local/* && sudo chmod -R g+rwx /usr/local/*`</li><li>Install **Visual Studio Code**: `brew cask install visual-studio-code` (or preferred IDE)</li><li>Install **Git**: `brew install git`</li><li>Install **npm**: `brew install node`</li></ul></ul><ul>**Credentials:**<li>Obtain access / credentials from workspace owner (currently Tom Ginn for Azure DevOps)</li>

</br>

|<center><h1> Cloning the  Repository </h1></center><li>https://dev.azure.com/Comfort-Order/Comfort%20Order/_git/Consumer-Portal-Mobile</li>
|:-------------------------|
| <h3> Access Repo and Select **beefBooks** for backend then Clone in VS Code</h3>
|  
| <h3> Confirm/Agree the following dialogues:</h3>
|  
| <h3> Save to your preferred directory </h3>
|   
| <h3> Enter your username for your DevOps account</h3>
|   
| <h3> Next, it will ask for a password. To get a password you will need to generate an access token to get one, click on the account icon in the top right corner of Azure DevOps and click `Personal Access Tokens`</h3>
|   
| <h3> Create a new token with full access and desired amount of time access, click to copy the password to clipboard and then paste into VS Code</h3>
|

</br>

|<center><h1>Native App Start</h1></center>
|:-------------------------|
| <h3> Open project from the directory that you chose. Then open the directory in the terminal and run `npm install` </h3>
|  
| <h3> You will need to install CocoaPods, run `sudo gem install cocoapods`</h3>
|   
| <h3> Then `cd` into the 'ios' directory in the terminal and run `npx pod install`</h3>
|  
| <h3> After that, open Xcode and open the project in the ios directory and build it using the play button</h3>
|   
| <h3>Then go back to VS Code and run the app by using `npm run start`</h3>
|   
| <h3>Finally go back to Xcode and the app should be available</h3>
| 


