# Realtime Online Chat
Chatting web application with authentication, live searching, one to one chat, message seen/unseen, new message notification, emoji sending features.


# Built on -
Backend - NodeJs, ExpressJs \
Database - MongoDB \
Frontend - jQuery and JavaScript, Bootstrap, EJS templating engine \
Socket - Pusher

##### Steps -
1. Set Up the Project:
Clone or create a new NodeJs project.
Install necessary dependencies using npm:
npm init -y
npm install express mongoose pusher body-parser ejs

2. Set Up MongoDB:
Install MongoDB and start the server.
Create a new database for your chat app.

3. Set Up Pusher:
Create an account on Pusher (https://pusher.com/).
Create a new app and get the credentials (App ID, Key, Secret).
Install the Pusher Node library:

4. Configure Express and Pusher:
Create an Express app and configure it.
Connect to the MongoDB database.
Set up Pusher with your credentials.

5. Create Models and Routes:
Define MongoDB models for users and messages.
Create routes for user authentication, message sending, and receiving.

6. Implement Authentication:
Use Passport.js for user authentication.
Implement login and signup routes.

7. Build Real-Time Chat with Pusher:
Implement socket connections using Pusher.
Set up channels for one-to-one chat.
Emit and listen for messages in real-time.

8. Implement Live Searching:
Integrate a live search feature using jQuery.
Implement functionality to search for users in real-time.

9. Add Message Seen/Unseen Feature:
Keep track of the status of messages (seen/unseen).
Update the UI to reflect message statuses.

10. Implement New Message Notification:
- Use Pusher to notify users of new messages.
- Update the UI to display notifications.

11. Enable Emoji Sending:
- Integrate an emoji picker library.
- Implement functionality to send and display emojis in messages.

12. Styling with Bootstrap:
- Enhance the UI using Bootstrap for a responsive design.

13. Use EJS Templating Engine:
- Implement dynamic rendering of HTML templates using EJS.

14. Testing:
- Test the application thoroughly, especially the real-time features.

15. Host Locally:
- Use a tool like ngrok to expose your local server to the internet.

16. Run the Application:
- Start your NodeJs server and MongoDB.
- Open the application in a web browser and test the features.


