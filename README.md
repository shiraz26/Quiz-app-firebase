# Quiz-app-firebase
# Jawan Pakistan
#Saylani
#Jawan-Pakistan
firebase connectivity with quiz app
<br> https://database-quizapp-final.web.app/
<br>After downloading zip file , you can change your web app  firebase configuration as per your project. 
changes will start from web app  firebase configuration in index.html file inside script tag . var firebaseConfig this line remain same changes from .
<br> var firebaseConfig { } in this  curly braces  you write your own configuration data and replace my data.<br>
  <br> Initialize Firebase firebase. <br>initializeApp(firebaseConfig); this will remain same don't change this .
 <br> In firebase application , real time database you can change in rules part <br>
 <br>   {
 <br>  "rules": {
  <br>   ".read": true,
   <br>  ".write": true
  <br> }
 <br>}
  <br>copy and paste this code in rules of real time database in firebase.
