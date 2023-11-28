# support-phone-numbers

This repository contains code examples that should be copied to Twilio Functions in Console:
https://console.twilio.com/us1/develop/functions/services

Or you can use them on your own JavaScript Server. 

Each folder/directory contains sub-directories "assets" and "functions", and each file in those sub-directories should be copied to the assets and function section of the Function created on the above link. 

Detailed steps are below:

- The function should be created under a desired Main account.
- You will have the option to search the logs of the subaccount in the created apps.
 
Steps to take:
1. Open the GIT repository for the desired function. We will reference this as we create the online function in Console.
2. Create a new Function in Console by going to Functions & Assets > Services > Create a new Service.
3. Add a new function (button in top left corner) and give it the same name as the function in the GIT folder (without .js extension).
4. Repeat step 3 for every Function in the GIT folder.
5. Open the Assets directory in the GIT
6. Create an Asset in the online Function (button in top left corner) and name it index.html (with .html extension)
7. Open the file in the GIT directory and copy the code content from the index.html file.
8. Do the same thing for the .css files that are in the GIT Assets folder.
9. For these assets, when you open them in the online Function, in the bottom-right corner it should say “html” and “css” respectively.
10. Click on “Environmental Variables” and add a new key called “Password” with the desired value (this will be your password to use the app).
11. Save all functions and assets in the online Function.
12. In the online Function, next to the name of each file you will see the current access level - set it to Public for all of them. By default they are Private.
13. Click on “Deploy All”, and wait for the deployment to be completed.
14. Click on “Dependencies” and update some items as needed.
- The twilio module version with ^3.61.0.
- If the @twilio/runtime-handler version is not at least 1.2.1, change it to 1.2.1.
- Change the Node version to 18 at the top.
15. Click “Deploy All”, and wait for deployment.
16. Click on index.html and in the bottom right corner click on “Copy URL” and paste it in a new browser tab. This will open the app.
