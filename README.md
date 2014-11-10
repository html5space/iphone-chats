# iPhone Message Chat Emulator

HTML5 web application

## Live Demo

http://iphone-chats.html5space.org

## Screenshot
![iphone chats screenshot][iphone]
[iphone]: http://cl.ly/image/1D3H0G34250w/iphone-chats.png "iphone chats screenshot"

## Usage
1. Press the home button to reset
2. Type a message text to the input field and press enter or click the "Send" button
3. Create some messages
4. When ready press the camera button at the left of the input field to take the screenshot
5. Right click on the screenshot image for saving it using the "Save image as..." command

Optionally you could redefine the Carrier ("Telenor") and the Sender ("Friend") values by clicking the items

## Build instructions
1. Clone the project
2. Open the project folder
    ```
    cd iphone-chats
    ```
3. Update dependencies
    ```
    sudo npm update
    bower update
    ```
4. Build the app (compressed code will be available in the dist folder)
    ```
    grunt build
    ```