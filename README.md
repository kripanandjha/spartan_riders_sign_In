# spartan_riders_sign_In
simple sign API for the application

android sign in with google email id

step 1: Add internet permission into your anidroidmenifest.xml file 
step 2: Now create same name project in google developer console --copy the package
		    name mentioned in anidroidmenifest.xml file 

step 3: Create new project on console.developers.google.com 

step 4: Go to https://developers.google.com/identity/sign-in/android/start-integrating
		    and sign your application

step 5: Now google will ask for sha-1 of your application -- to get that
		    signin greport in gradle to get sha-1 value and enter in google sign in page.
		
step 6:  Now download google-service.json file which google has generated for us

step 7: Paste this file to your project app folder directory.

step 8: Now install dependencies for google sign which will be mentioned on
		    'sign in page' where we left and click on 'continue sign in' which will show
		    things to set up in the project to support google sign 
		
step 9: After updating build gradle and module gradle file check if android
		    studio has installed 'google play services'
		
step 10: After installing google play services you are to go . set up onclick handler for that 

step 11: Follow this tutorial to add handler for sign in and sign out code in android
		  https://developers.google.com/identity/sign-in/android
		  

