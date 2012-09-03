heroku-blank
============

Simple vraptor project configured to deploy to heroku cloud.


Deploying to heroku
-------------------

* clone this repo
* add your heroku app remote branch
	* ```git remote add heroku git@heroku.com:<your-app>.git```
* push to heroku 
	* ```git push heroku master```
* that's it!

Importing to eclipse
--------------------
* run ```mvn clean install```
	* take a coffee while you wait maven to download the whole internet
* import to eclipse (File > Import > Existing Projects Into Workspace)
* that's it!