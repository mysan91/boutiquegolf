
<img src="" style="width:550px">



# 

## About 
The site is a Golf store, were you can buy golf products, courses and also golf travels. 


## Creating 



## UX 




### User Goals
*

 ### Site Owner Goals 



 ### User Requirements 



## Design Choices 

#### Home page



### Styling 

### Features that is implemented:

The website uses Materialize CSS on following:

* Navbar 
* Mobile Sidenav 
* Form (to register and log in)
* Users can login and register to add or edit tasks
* Users can delete a task
* Users can edit a task
* Users can pick both start and due date to a task 
* Site linked to Heroku
* Site linked to Mongodb database
* Login/register
* CRUD

### Features left to implement



### Technologies used 
Languages:

* HTML5
HTML was used for the main structure of the website.
* CSS3
CSS was used to style and change sizes. 

* Javascript
Was used on the dynamic functions on the site 

* Python3 
Used as Back-End programming language

* Pymongo 
Used as Python's API for MongoDB intergration.

* Flask rendering template, URIs Requests and the flash messages.

* BSON for accessing the data in MongoDB and to access IDs. 

* Werkzeug was user to hash password when registering to the site and encrypting on MongoDB.

Database:
* MongoDB was used to store all data for the website.

* Heroku
Used for hosting my full stack app.

Requests and flash messages.
* Jquery
JQuery was used for materialize features that needed javascript.
* Materialize CSS


Tools & Libraries:
*	Gitpod
* Github
*	Font-Awsome
*	Google Fonts
* Google Chrome



## Testing
#### User story Testing 
 

#### General testing 

* All links on the site works well and are being opened with success. 
* The page/linkes such as add task, manage categories and profile will will only be shown when the user is logged in. 
* Register with the user mysans with success. 
* Register with the user test1 and it worked with success, the new user was added to the database and was logged in. 
* Test to start a new task with the new user and it worked well. 
* Tested to delete a task and that also worked well. 
* Tested to manage categories and add a category and that worked well. 
* Tested to edit a category and that worked well. 
* Tested to delete a category and that worked well. 

##### Responsiv test
In this test i used the Google inspect tool 
The following devices were used: 

* Ipad 
  * When testing the responsivness for the Ipad, The navbar adjust and poped up at the right and the tasks also adjusted fine. 
  All the different sizes worked fine. 
* Iphone X
  * When testing the responsivness for the Iphone X, The navbar adjust and poped up at the right and the tasks also adjusted fine. 
  All the different sizes worked fine. 
* Iphone 6/7/8 
  * When testing the responsivness for the Iphone 6/7/8, The navbar adjust and poped up at the right and the tasks also adjusted fine. 
  All the different sizes worked fine. 
* Benq 24 inch screen 
  * When testing the responsivness for the BenQ, All of the sites and content adjust fine and worked well. 
 
## Deployment 
The following steps i made to deploy the project on to the github page.
1. Log in to the github account. 
2. Pick the repositorie with the name 
3. After you click on the repositorie push the settings button. 
4. Scroll down to the Github pages under the source section. 
5. Click on the none bar and change it to Master.
6. Save the changes! 
7. The page then did refresh and the page is published at 

### Deploymen Mongo DB 
Mongo DB is used for tha database in this project 
Start by going to https://www.mongodb.com/ and creata a account. 
1. Start by creating a new Cluster. 
2. Then create database Task_manager. ANd add the collection name categories.
3. Then click on create collections. 
4. Users, Tasks, categories has already been created on step 3.
5. To insert documents to a collection click on the collection categories and then insert document.
6. The following string collections was used: 
* category_name 
* task_name
* task_description
* start_date
* due_date
* created_by 
* username
* password

7. Go back to github and the repository.
8. Above the list of files click on the code button. 
9. To clone the repository using HTTPS, click HTTPS under "Clone".
10. Press Enter to create your local clone.
11. Create your own env.py file to store variables
  * Import os
  * os.environ.setdefault("IP", "enter value")
  * os.environ.setdefault("PORT", "enter value")
  * os.environ.setdefault("SECRET_KEY", "enter value")
  * os.environ.setdefault("MONGO_URI", "enter value")
  * os.environ.setdefault("MONGO_DBNAME", "enter value")

12. In mongoDB click on the overview button and connect.
13. Pick connect your application.
14. And pick python and version.
15. Copy the link and paste it in the ("MONGO_URI", "enter value")
16. Update the undername and password in the link.
17. 
### Run the code locally
1. On the github page navigate to the main page of the repository you want to run. Check repository 
2. Above the list of files press on the code button with the downloadinglink.  
3. To clone the repository using HTTPS, under "Clone with HTTPS", click on the https link and the link will be copyed. If you want to clone the repository using SSH or Github Cli click on the link tap ob the respective tabs. 
4. After you have copy the link go to Git Bash and open. 
5. Change the current working directory to the location where you want to put the cloned directory. 
6. Type git clone and paste the repository URL.
7. Press enter to create the local clone. 

### Deployment Heroku 
1. Created a new application using the Heroku dashboard.
2. Go to settings tab, click on 'reveal config vars' and add config vars such as IP (0.0.0.0), PORT (5000), MongoDB Name, MongoDB URI URL with DB name and password.
3. Install Heroku via the console using npm install -g Heroku.
4. Push two new files (requirements.txt and Profile) to repository.
5. Now in In Heroku, you can Enable Automatic Deployment
6. Then deploy branch.
7. That can take a minute to build, once it's done, The message ‘Your app was successfully deployed.’ will be shown then Click ‘View’ to launch your new app: 




## Credits 
 Pexels.com


