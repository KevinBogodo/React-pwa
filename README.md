![Logo](https://cdn.cosmicjs.com/6352a0f0-28d7-11e9-804a-1fcd66628430-cosmic-pwa.jpg)
# Add pwa in existing react application

Hello, here we are going to add pwa fonctionnality in simple react app

1- Create app create-react-app

2- Add workbox packages using this commande : `npm i workbox-background-sync workbox-broadcast-update workbox-cacheable-response workbox-core workbox-expiration workbox-google-analytics workbox-navigation-preload workbox-precaching workbox-range-requests workbox-routing workbox-strategies workbox-streams workbox-webpack-plugin`

3- Copy and paste necessary files `service-worker.js` & `serviceWorkerRegistration.js` from  /src folder 

4- Edit index.js buy adding:

  `import * as serviceWorkerRegistration from './serviceWorkerRegistration';`
  
  `serviceWorkerRegistration.register();`


5- Build and deploy (local deployment) using `serve package`

- `npm run build`
- `serve -s build`

If you want to test this projet,
- First install package `npm install`
- Start with `npm run start`

Note: Pwa fonctions are fully available only on production mode. fell free to share any update or sugestion to upgrate or correction

Thank's

