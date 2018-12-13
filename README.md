# A Simple Progressive Web

This example contains a very simple progressive web app (pwa) that demonstrates two key features for a pwa. 
* Using a service worker to do resource caching so the app will work offline. 
* Using a web app manifest file to 'install' the app on the user's device. 

## Running the Example
* Place the files on a web server (the nodejs http-server is fine).
* View the site using chrome. 
* Use the developer tools and the application tab to check the caching
* Switch off the network connection in chrome and refresh the page. 
    * Check the network tab to make sure resources are being served from cache.
* Click the 'Add to homescreen' button. Accept the prompt and check this works i.e. an icon has been added to the desktop and clicking this opens the app. 
    * To uninstall the app, open a new tab in chrome and click on the 'show apps' button. 

## Finding out more

### Progressive Web Apps
* https://developers.google.com/web/progressive-web-apps/

### Service Workers
* https://developer.mozilla.org/en-US/docs/Web/Apps/Progressive/Offline_Service_workers
* https://developers.google.com/web/ilt/pwa/introduction-to-service-worker

### Add to Home Screen
* https://developers.google.com/web/fundamentals/app-install-banners/
* https://developer.mozilla.org/en-US/docs/Web/Apps/Progressive/Add_to_home_screen
