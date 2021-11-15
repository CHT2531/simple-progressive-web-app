# A Simple Progressive Web App

This example contains a very simple Progressive Web App (PWA) that demonstrates two key features for a PWA. 
* Using a service worker to do resource caching so the app will work offline. 
* Using a web app manifest file to 'install' the app on the user's device. 

## Running the Example
* Place the files on a web server.
* View the site using chrome. 
* Use the developer tools and the Application tab to check the resources have been cached
* Switch off the network connection in Chrome and refresh the page. 
    * Check the Network tab to make sure resources are being served from cache.
* Click the 'Add to homescreen' button. Accept the prompt and check this works i.e. an icon has been added to the desktop and clicking this opens the app. 

## On your own
* Try adding another HTML page to the site. Add a link to this new page. Make sure users can navigate between the two pages of the site. 
* Modify *sw.js* so that this new page will be cached.
* Modify the manifest file e.g. change the name of the app, change the background colour. 
* Uninstall the app and use the Application tab in Chrome to delete any caching for the site
* Open the app again and check that your changes have taken effect. 
* If you have an account on the selene web server, upload the app to selene and view the app using a mobile device. See how the app works on a mobile device.

## Finding out more

### Progressive Web Apps
* https://developers.google.com/web/progressive-web-apps/

### Service Workers
* https://developer.mozilla.org/en-US/docs/Web/Apps/Progressive/Offline_Service_workers
* https://developers.google.com/web/ilt/pwa/introduction-to-service-worker

### Add to Home Screen
* https://developers.google.com/web/fundamentals/app-install-banners/
* https://developer.mozilla.org/en-US/docs/Web/Apps/Progressive/Add_to_home_screen
