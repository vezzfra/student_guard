# StudentGuard
An iOS and Android project to protect University students from thieves. 

In 2018 the main problem everyone was talking about in the Milan's Universities were thieves. 
In collaboration with a student association I developed an app that permitted all the users to notify everyone else about recent thefts and about suspicious people. 
There are three report types: 

   - Suspicious person (to warn all the users about suspicious people around the campus);
   - Theft;
   - Loss (to ask for help finding lost items);

![1242x2208bb](https://user-images.githubusercontent.com/1354168/155500376-aba56ec0-e93d-4ddd-8ac5-2e9d2a642bd1.png)
![1242x2208bb (2)](https://user-images.githubusercontent.com/1354168/155500369-bde15135-1bd6-43af-bb2b-9dcff0af6a93.png)
![1242x2208bb (1)](https://user-images.githubusercontent.com/1354168/155500379-b3ceeb6b-c912-4cd1-8bfb-faf176b356f1.png)

The concept of the app is quite simple: 

   - The user after registering (with a university mail that is requested to be verified) to the service can decide from which campus he/she wants to receive push notifications;
   - On the app opening, the system gets the live location and then shows the nearest reports;
   - While adding a new report the app tries to retrieve the location information and it automatically sets the building the student is in. The classroom has to be added manually;
   - When a new report is uploaded on the server a push notification is sent to all the users registered to the interested campus and a pin is placed on the university map;
   - Users are able to react to reports with 'likes' in order to validate them. 


The backend is based on the Parse Platform by Facebook (now dismissed) and it uses AES cryptography for all the data uploaded and downloaded. 
This app was on the App Store and on the Play Store from 2018 to 2019 when it was dismissed because universities started to add their own services to prevent thefts. 
In the meantime the app on iOS was downloaded a total of 2K times and had a 4 stars reputation.  

This code includes: 

   - <img src="https://cdn-icons.flaticon.com/png/512/1163/premium/1163417.png?token=exp=1646817425~hmac=da00e7af47ea2598b99a432bfd2a75e9" width="15px"> Cryptography;
   - <img src="https://cdn-icons-png.flaticon.com/128/2884/2884814.png" width="15px"> Usage of internet protocols;
   - <img src="https://cdn-icons-png.flaticon.com/128/1182/1182769.png" width="15px"> Push notifications (<b>Server to device</b> and <b>device to device</b>);
   - <img src="https://cdn-icons-png.flaticon.com/128/854/854929.png" width="15px"> MapKit and live location;
   - <img src="https://cdn-icons.flaticon.com/png/128/3368/premium/3368235.png?token=exp=1646817854~hmac=8e629bba2d904842e2f785fff09c3dfd" width="15px"> UIKit with Interface Builder;
   - <img src="https://cdn-icons-png.flaticon.com/128/1466/1466291.png" width="15px"> Google AdMob integration;
   - <img src="https://cdn-icons.flaticon.com/png/128/586/premium/586293.png?token=exp=1646817942~hmac=75ff0e2b7ec2802a953a386b43db96d8" width="15px"> Database access with Parse Platform (deployed on Heroku).
