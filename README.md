# React Native Redux App Project Structure V1
React Native Redux app is all about managing the react and redux project structure, Development and issue tracking. This is repo include front-end framework and api connectivity, React, Redux, React-router5, Webpack, file-loader and Uglify / Concat.

**Note: As of Jan 1th 2018, the code has been updated to work w/ latest versions of its dependencies!**


## Built With

* [ReactNative](https://reactjs.org/) - The web framework used
* [Redux](https://redux.js.org/) - The state container for apps
* [Router5](https://router5.github.io/) - Used for front-end routing instructions and outputs state updates
* [React-Router5](https://rometools.github.io/rome/) - Used for front-end Routing
* [npm](https://www.npmjs.com/) - Dependency Management


## Installation Packages
After cloning the project to your computer run the following command in your terminal to install all required node packages.

```
sudo npm install && yarn install || npm install && yarn install
```

#Running Locally
*You need terminal windows open*, one for client and the other for server.

2. In terminal 1, run: `npm run dev`. This runs the development server(config-development-server).
3. Open browser and go to: `localhost:8080`


####Production
In production, we need to compile the **latest** client js and place it to `dist` folder. This allows the main app Webpack module to also show the final app with bundle analyzer.

Generate latest React app: `npm run build`.


## Authors

* **Omer Ali**
