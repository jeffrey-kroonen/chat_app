# Chat app
The application is used by people who want to communicate with each other over the internet. The user interface is accessible in a web browser and as a Android mobile app.

**🏗️ The application is being developed.**

In the future I will start a community for this project. It will be possible to add feature requests. The source code stays open for everyone who want's to use this for development, testing or production.

## Todo
The following list will give you an overview of the development progress. The list contains all todo's for this project.

### Web
#### User
- [ ] Add a widget to create a new user.
    - [ ] If all entered values are correct, insert a new user.
    - [ ] Log in the new user automatically.
- [ ] Add a widget to show the current logged in user his/her data.
    - [ ] Add functionality to update the data for the current logged in user.
    - [ ] Add functionality to delete all server data from the server. This functionality can only be used by the logged in user.
- [ ] Add a widget to login for anonymous users.
    - [ ] Add a functionality to generate a new login password for users who forget the password. And send the password to the given email address.

#### Chat
- [ ] Add a widget to start a new chat.
    - [ ] Add functionality to search by email address.
    - [ ] Add the newly created chat in db.
- [ ] Add widget to send messages.
    - [ ] Add functionality to fetch all messages from the current chat.
    - [ ] Add a functionality to retrieve received messages.
    - [ ] Add functionality to insert the newly created message into the db.
- [ ] Add a widget to show the status of a message.
    - [ ] Add status icons to the messages to indicate whether the message has been sent; received; read.
- [ ] Add functionality when a user delete his/her data to delete all chat data as well. Including files attached to the chats.
- [ ] Add functionality to send files attached to a message. It will still be possible to add text to the message.
    