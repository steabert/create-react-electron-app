This project provides a boilerplate for using electron together with create-react-app.

Part of this project was bootstrapped with [Create React App](https://github.com/facebookincubator/create-react-app).
You can find the most recent version of the create-react-app guide [here](https://github.com/facebookincubator/create-react-app/blob/master/packages/react-scripts/template/README.md).
All of it applies to this project as well.

You can use `yarn start` and `yarn build` as with a regular create-react-app project.

In addition, for the electron part of this project, use
```
yarn electron-dev
```
to start electron with `http://localhost:3000` as URL, or
```
yarn electron-prod
```
to start electron with `/build/index.html` as URL.

You can combine both building the react app and launching electron
with:
```
yarn dev
```
for development, or
```
yarn prod
```
for production.

Scripts with node dependencies can be added to the `lib/` directory, and exposed via `lib/index.js`.