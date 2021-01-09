# Whatsapp API Tutorial

Hi, this is the implementation example of <a href="https://github.com/pedroslopez/whatsapp-web.js">whatsapp-web.js</a>

### How to use?
- Clone or download this repo
- Enter to the project directory
- Run `npm install`
- Run `npm run start`
- Open browser and go to address `http://localhost:8000`
- Scan the QR Code
- Enjoy!

### Notes
As mentioned in the video above, you have to install `nodemon` to run the start script. You can install nodemon globally with `npm i -g nodemon` command.

### Send message to group
I was added an example to send a message to groups, but before that we must know the group ID (chat ID). Don't worry, I also add the functionality to help you to get that groups ID.

Here the way to get the groups info (including ID & name):
- Send a message to the API number `!groups`
- The API will replying with the groups info
- Use the ID to send a message
- Here the endpoint: `/send-group-message`