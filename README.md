# react-rxdb-example

A simple anoymous chat app that shows how you can create offline apps with React and [RxDB](https://github.com/pubkey/rxdb), using a local IndexedDB database.

This project was bootstrapped with [Create React App](https://github.com/facebookincubator/create-react-app).

## Requerimients
- Node version 6 or superior. You can use [nvm](https://github.com/creationix/nvm#installation) to switch between Node versions.
- A modern browser that [supports IndexedDB](http://caniuse.com/#feat=indexeddb).

## Installation
1. Clone this repo and `cd` into it.
2. Execute `npm install` to download depencencies.
3. Execute `npm start` to start the dev version of the app and test the local database functionality RxDB provides.
4. To test the offiline functionality provided by `create-react-app`, you should take into account some [considerations](https://github.com/facebookincubator/create-react-app/blob/master/packages/react-scripts/template/README.md#making-a-progressive-web-app), but basically, execute `npm run build` to build a production build of the app and then execute `npm run offline`, go to `http://localhost:3000` (in incognito mode if possible, since this will install a service worker and its manifest) and go offline to test it.
5. Also, you can go to `http://localhost:5984/_utils/` to open the database web interface.

## License

MIT