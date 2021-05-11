# VaccineNotifications
This script checks the cowin portal in intervals to find the slots available for the vaccination in your city(pin code) and for your age. If there is some available slot, it will keep sending the mails every minute till the time slots are available to the specified email address.


## Steps to run the script:
```
Step 1) grant application access:
https://support.google.com/accounts/answer/185833?p=InvalidSecondFactor&visit_id=637554658548216477-2576856839&rd=1  

Step 2) Fill the details in .env file

Step 3) Run: npm i && pm2 start vaccineNotification.js

Want to close? pm2 stop vaccineNotification.js && pm2 delete vaccineNotification.js
```