# iSplit
Mobile web app that can read a photo of a bill and split the bill among people

## Installation steps
* Make sure you have Node.JS and NPM installed on your local machine.
* Make sure you have an Editor that is compatible with ESLINT (like atom with the ESLINT plugin installed)
* run npm install to install all dependencies, make sure to keep all dependencies up to date using npm update.
to start the client run npm start
* Navigate your browser to http://localhost:9000
* To run the API server run npm run api -> The API server is now running on http://localhost:3000
* To build a distributable version of the App run npm run build.

## User Guide with Screenshots
* Opening the software
  * The first step is extremely simple. Open the application in your mobile web browser. You will be greeted by a welcome screen that looks like this
  
  ![image](https://user-images.githubusercontent.com/10985717/36130554-3c52d958-1022-11e8-96bd-01ba6aab4c2d.png)

* Authentication
  * Because the user has never logged in before. Authentication is required. Simply tap the "Login in with Facebook" button and let your device handle the rest. This will send a request to the server.

  ![image](https://user-images.githubusercontent.com/10985717/36130657-b8649c16-1022-11e8-8add-88d5460469a4.png)
  
* Taking a picture
  * Click the "Upload Bill" button to take a picture. Once you have clicked this button it will open the camera or the camera roll on your device. Simply select a picture from your camera roll or take a picture to continue to the next step. The next step is Cropping the picture.
  
  ![image](https://user-images.githubusercontent.com/10985717/36130737-3b34b202-1023-11e8-9ab4-c4a232470d03.png)

* Cropping the picture.
  * Once the picture has been selected, you can crop it. This allows you to select the most important part of the image.
  
   ![image](https://user-images.githubusercontent.com/10985717/36130773-6eadc4b6-1023-11e8-8fa5-f3591bf85b1e.png)
   
* Wait for a response from the server.
  * Sit back and relax. The server is now handling your request, translating the bill and converting it to a proper format so that you can split it.
  
  ![image](https://user-images.githubusercontent.com/10985717/36130824-a1b75f98-1023-11e8-97d6-7f3fbfc148c8.png)

* Explore the list of items on the bill.
  * Once the information has been retrieved from the server. Scroll through the list of items to start assigning it to people.
  * Simply click on an item to expand it.
  
  ![image](https://user-images.githubusercontent.com/10985717/36130837-b855f6ce-1023-11e8-9d68-f88dd30ca01d.png)

* Add a person to the group.
  * Right now, items can only be assigned to myself. To add more people to the group, simply click the add person button.
  
  ![image](https://user-images.githubusercontent.com/10985717/36130863-cf280cc0-1023-11e8-8566-b6c7d2871177.png)

* Filling out persons' information
  * Make sure to fill out all the fields, Isplit will validate your inputs.
  
  ![image](https://user-images.githubusercontent.com/10985717/36130895-fc3cfd56-1023-11e8-8cde-100598ca5574.png)

* Assign an item to a person.
  * Once an item has been opened. Simply tapping it will add that person to the list of people who will be paying
  
  ![image](https://user-images.githubusercontent.com/10985717/36130926-17b2cf34-1024-11e8-8cd1-c83e8b002b1d.png)

* Checking the overview
  * Clicking the overview button in the bottom allows you to see a proper overview of how exactly the items have been divided between the group. You can always navigate back by hitting the big red "back" button.
  * Once you are happy with the way the items are split. Hit the big checkmark to confirm and notify all your friends that they owe you money.
  
  ![image](https://user-images.githubusercontent.com/10985717/36130942-30d30e2a-1024-11e8-96ad-483ef1900eb3.png)

* Wait for a response from the server.
  * Sit back and relax. The server is now handling your request, Once you are navigated back to the homescreen, it means all your friends have been properly notified. From here on onwards you can split another bill. Or just wait for your friends to pay their dues!
  
  ![image](https://user-images.githubusercontent.com/10985717/36130990-6f9fc490-1024-11e8-932b-b1cd09502164.png)

* Receiving a text message notification.
  * This screenshot shows Abilash's point of view. Now that we have split the bill with him. He received a notification, telling him that he owes Jens some money.

  * Abilash also receives a unique URL. This will give him some more information about what exactly he owes Jens.
  
  ![image](https://user-images.githubusercontent.com/10985717/36131015-8f1daf62-1024-11e8-803f-ac9bb6d9b167.png)

  * Navigate to the Payment Request page.

  * Simply tapping the unique URL opens the following page in your mobile browser. This page shows a picture of jens - which iSplit automatically pulled from Facebook.

  * This view also gives Abilash a detailed breakdown of what exactly he owes Jens money for.
  
  ![image](https://user-images.githubusercontent.com/10985717/36131040-b5f52f70-1024-11e8-9877-3ac37f46f7b4.png)




  
  






