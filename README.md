# expoForWeb
one code rendered for all the platform (EXPO, Web, React Native, iOS, Android)

**How is the example build**

 - Step 1- To setput a new project you have to install either expo XDE or expo cli
 - Step 2- To install expo cli run npm install expo-cli -g
 - Step 3- Init a new project using expo init command.
 - Step 4- To run expo server execute command expo start or npm run start
 - Step 5- The above step will install expo app in emulator or simulator whatever you are using.
 - Step 6- Now this was all about mobile platforms. For web install yarn add react-scripts react-dom react-native-web react-art react-router-native react-router-dom
 - Step 7- react-scripts will help to run all the scripts which creat-react-app gives, react-dom is for rendering react code to render in html, react-native-web is the one which play a big role in rendering same code for different platforms by substituting similar components of mobile with web, react-art is a peer dependency of react-native-web, react-router-native for routing in mobile platform and react-router-dom for routing in web.
 - step 8- Create a public folder and add a html file where react code will be rendered.
 - Step 9- Create src folder in the root dir of the project. Inside src folder create a index.js file which will handle rendering of mobile app code in web dom. Inside src folder create App.js which has a logic of mobile app code, import this file to index.js which is responsible for web platform rendering, So that same code could be used for mobile app as well as web.
- Step 10- The only difference is the routing part, which we will define in diffrent files for each platform i.e mobile and web. For web routing we will react-router-dom and for mobile routing we will use react-router-native. To differentiate between routing of web and mobile we will use .web.js extension for web and .native.js for mobile. The compiler will automatically take the one which is compatible to the platform.

 
----------

Note:- Now whatever you write inside the src/App.js file for mobile app development will be compiled automatically for web platform also, though there are few styling issues.

----------

**Author**

    Anoop Singh (codesingh)
    Email: anoop100singh@gmail.com
    Stack Overflow: codesingh(username)
    
----------    

**License**
    
Apache-2.0
