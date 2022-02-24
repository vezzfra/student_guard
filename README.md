# StudentGuard
An iOS and Android project to protect University students from thieves. 

In 2018 the main problem everyone was talking about in the Milan's Universities were THIEVES. 
In collaboration with a student association I developed an app that permitted all the users to notify everyone else about recent thefts and about suspicious people. 
There are three report types: 

   - Suspicious person (to warn all the users about suspicious people around the campus);
   - Theft;
   - Loss (to ask for help finding lost items);

![1242x2208bb](https://user-images.githubusercontent.com/1354168/155500376-aba56ec0-e93d-4ddd-8ac5-2e9d2a642bd1.png)
![1242x2208bb (2)](https://user-images.githubusercontent.com/1354168/155500369-bde15135-1bd6-43af-bb2b-9dcff0af6a93.png)
![1242x2208bb (1)](https://user-images.githubusercontent.com/1354168/155500379-b3ceeb6b-c912-4cd1-8bfb-faf176b356f1.png)

The concept of the app is quite simple: 

   - The user after registering (with a university mail that is requested to be verified) to the service can decide from which campus he wants to receive push notifications;
   - On the app opening the system gets the live location and then show the nearest reports;
   - While adding a new report the app tries to retrieve the location information and automatically set the building the student is in. The classroom has to be added manually;
   - When a new report is uploaded on the server a push notifications is sent to all the users registered to the interested campus and a pin is placed on the university map;
   - User are able to react with 'likes' to reports in order to validate them. 


The backend is based on the Parse Platform by Facebook (now dismissed) and uses AES cryptography for all the data uploaded and downloaded. 
This app was on the App Store and on the Play Store from 2018 to 2019 when it was dismissed because universities started to add their own services to prevent thefts. 
In the meantime the app on iOS was downloaded a total of 2K times and had a 4 stars reputation.  
