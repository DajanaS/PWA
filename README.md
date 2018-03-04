# Hello World - Progressive Web Application

## 10 steps to create a simple Hello World PWA

1. Create a directory named as the name of the application, in my case *PWA*.
2. Inside that directory, create a new one named *src*.
3. Inside *src* create an [index.html](src/index.html) file (without `script` tags) and a [.css](src/hello-world.css) file
4. According to [Firebase docs](https://firebase.google.com/docs/web/setup), create a Firebase project in the [Firebase console](https://console.firebase.google.com/). Mine looks like this:
![prtsc1](prtscs/prtsc1.png)
5. Copy the snippet into [index.html](src/index.html) file.
6. Check if [node.js](https://nodejs.org/en/download/) is installed and if it is not install it. It is prerequisite for the next step.
7. Install firebase (if it is not already installed) by opening console and writing the command `npm install -g firebase-tools`.
8. Position into the directory of the application, which is *PWA* in my case, and write the command `firebase init`.
![prtsc2](prtscs/prtsc2.png)
9. Follow the answers as in the screenshot and then write the command `firebase deploy`.
10. The project is ready and available in the URL given in the console, in my case [here](https://hello-world-c0364.firebaseapp.com/).