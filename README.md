# GregSimpleReactNativeTodoList
Build your first React Native app - Todo List Tutorial Part 1
	About Expo CLI and React Native
		https://www.npmjs.com/package/expo-cli 
		https://www.npmjs.com/package/react-native

Link to source-code for Cheaters! 
https://github.com/mattfrances/simpleReactNativeTodoList/blob/master/App.js 
https://www.youtube.com/watch?v=0kL6nhutjQ8
Key Learnings
1. Set up dependencies
2. Create beautiful frontends
3. Pass props
4. Manage state

FYI… From the VS Code/IntelliJ Terminal 
Note: be aware that “npx” may be needed for the version of Mac you are using… I have a zsh and I had to add npm-global to my path
Example Issue
philipmichaels@philips-mbp todoList % expo start
zsh: command not found: expo

Prerequisites
% cd /Users/philipmichaels/Desktop/snyk_projects/
% mkdir todoList
% npm install --gloabl expo-cli
projects % echo $PATH
/Users/philipmichaels/.npm-global/bin:/usr/local/bin:/usr/bin:/bin:/usr/sbin:/sbin:/Users/philipmichaels/Library/Application Support/cloud-code/installer/google-cloud-sdk/bin:/Users/philipmichaels/.npm-global/bin
% npx expo init todoList
	Below I just hit “Enter” to
✔ Choose a template: › blank               a minimal app as clean as an empty canvas

✅ Your project is ready!

To run your project, navigate to the directory and run one of the following npm commands.

- cd todoList
- npm start # you can open iOS, Android, or web from here, or run them directly with the commands below.
- npm run android
- npm run ios
- npm run web
philipmichaels@philips-mbp snyk_projects % cd todoList

I used Explorer in VS Code to Open the folder todoList

philipmichaels@philips-mbp todoList % ls -ltr
total 1344
-rw-r--r--    1 philipmichaels  staff     107 Oct 26  1985 babel.config.js
-rw-r--r--    1 philipmichaels  staff     454 Oct 26  1985 App.js
drwxr-xr-x    6 philipmichaels  staff     192 Feb 15 13:11 assets
-rw-r--r--    1 philipmichaels  staff     648 Feb 15 13:11 app.json
-rw-r--r--    1 philipmichaels  staff     534 Feb 15 13:11 package.json
-rw-r--r--    1 philipmichaels  staff  670686 Feb 15 13:11 package-lock.json
drwxr-xr-x  497 philipmichaels  staff   15904 Feb 15 13:11 node_modules
philipmichaels@philips-mbp todoList % pwd
/Users/philipmichaels/Desktop/snyk_projects/todoList

% npx expo start

Because I use an Apple phone and do not wish to do this all on my iOS I will › Press i │ open iOS simulator
* I installed Xcode as a Developer tool fr my Mac to become an iOS simulator

Under General > Locations > Command Line Tools: Choose Xcode version (e.g. 13.2.1)

You will then see the following in the CMD line if successful:

Logs for your project will appear below. Press Ctrl+C to exit.
› Opening on iOS...
› Opening exp://192.168.87.24:19000 on iPhone 8
› Opening the iOS simulator, this might take a moment.
› Press ? │ show all commands
iOS Bundling complete 39491ms
iOS Running app on iPhone 8

Now you have an iOS Apple phone simulator instead of doing this on the phone!

Fllow Part 1 and Part 2 of the video to do this on your own

I should also note that https://www.figma.com/ has a cool interface for building phone Apps 

