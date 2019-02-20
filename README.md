# employeemanager

> A Vue.js project

## To test on your machine
1. Setup `npm`, `webpack-cli` and `vue-cli`.
2.  Go to [firebase console](https://console.firebase.google.com/), sign in with your gmail and create a project there named `vuefs-prod`. On your project page, go to `Database` section in your left navigation panel and enable firestore in test mode.
3. Clone the repository `git clone git@github.com:pfieffer/employeemanager.git`  or `git clone https://github.com/pfieffer/employeemanager.git`
4. Create a `firebaseConfig.js` file in your `src/components/` directory
5. Paste the following in there
   ``` javascript
   export default{
    apiKey: "XXXXXXXXXXXXXXX",
    authDomain: "XXXXXXXXXXXXXXX",
    databaseURL: "XXXXXXXXXXXXXXX",
    projectId: "XXXXXXXXXXXXXXX",
    storageBucket: "XXXXXXXXXXXXXXX",
    messagingSenderId: "XXXXXXXXXXXXXXX"
    }
   ```
5. Replace `XXXXXXXXXXXXXXX` with your credentials from [firebase console](https://console.firebase.google.com). You can get this, by going to `Add Firebase to your web app` from firebase console.
6. Then run 
     ``` bash
        # install dependencies
        npm install
        # serve with hot reload at localhost:8080
        npm run dev
    ```


## App Screenshots:

### New Employee
![New Employee](https://screenshotscdn.firefoxusercontent.com/images/5f7c317f-d232-435b-bb9c-f7bf0b88e7de.png)
---
### View, Edit and Delete Employee
![View Edit and Delete Employee](https://screenshotscdn.firefoxusercontent.com/images/4a8e65b5-ce7e-4e93-b6f5-f7b4528318ab.png)
---
### View Employee List
![View Employee list](https://screenshotscdn.firefoxusercontent.com/images/6d565500-6e96-4ff5-a1d8-90b4574d2332.png)
---
>I have tried to put appropriate commit messages for figuring out how exactly each module was built. Thanks to [Traversy Media](https://www.youtube.com/channel/UC29ju8bIPH5as8OGnQzwJyA) for this particular tutorial. 

For a detailed explanation on how things work, check out the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).
