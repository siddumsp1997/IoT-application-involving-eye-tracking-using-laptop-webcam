# IoT-application-involving-eye-tracking-using-laptop-webcam
> This web application helps us to open bookmarked tabs in the web browser by tracking our eye movement
  using the laptop’s web-camera. 
> Used WebGazer package for recording eye position on the screen.
> Created a regression model in order to store the datasets containing the eye position and the corresponding coordinates on the laptop     screen (caliberation),training them and predicting the coordinates using this. The more time spent for caliberation, the more             accurate the results will be.
> If a particular tab is viewed for more than 3 seconds, it is assumed that the tab is clicked and the corresponding link opens in a new  
  tab. ( 'viewed' in the sense, the eye pointer is within that tab's area-space )
> 3 categories are created and each category contains 4 tabs.
> First 20 seconds is meant for caliberation. After that, "Activate" button will be activated.
> Tested successfully in Google Chrome browser ( using localhost )
