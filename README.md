# Fcm web push with vanilla js
This is a dummy repository describing how to use vanilla js to implement firebase cloud messaging web push notification.

# How to run?
To run the project:
- Replace the empty firebase credentials in the source code
- Run the `index.html` file with live server from vscode

Now open `http://localhost:5500` in the browser with browser's developer tool on.
Browser will ask for your notificatoin permission. Allow it to generate your `fcm token` in the console.
Now you can use that `fcm token` to push test notification in that device.

> **NOTE:** If your browser tab is not focused on the project you will get os level notification. If you are in focus of the opened browser tab then the notificatoin payload will be printed in the console.
