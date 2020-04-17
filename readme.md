Created by Anurag Gupta
*Project still under development

1. used haarcascade classifier to detect cars
2. uses tesseract to detect text
3. uses openCV for image manipulations and enhancements
4. uses firebase cloud firestore as a database - online
5. uses sqlite database - local
6. uses twilio to send sms
7. uses multithreading to execute speed detection, license detection and storing data in parallel
8. a single webpage to view firestore collection/table

database/collection:
contains following fields/columns - {'date', 'time', 'speed', 'licNo', 'licError'}

for firestore:
1. create a firestore project and database service
2. A colletion 'overspeed' will be created automatically while running .py file
3. get your api-keys/credentials in json format for your python project and replace with .json file.

*SENS SMS PART REQUIRES A SEPARATE TABLE WITH OWNER DETAILS and CORRESPONDING LICENSE NUMBER
*OWENER DETAILS PART NOT IMPLEMENTED YET - FUNCTION IS PROVIDED

*webpage has no backend can be hosted easily on github etc.
*webpage also requires firestore credentials, can be obtained from project settings.

*license plate detection is often inaccurate
*the license image obtained is low contrast, and low res around 20*50 px, if using 1280*720 video.
*thus text recognition is so far impossible.

-for separate vehicle detection and license recognition(high res image) see other repositories.
