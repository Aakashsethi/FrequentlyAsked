# FrequentlyAsked
#KEY FEATURES

Access Control
Database Notifications
Email Notifications Using Mailtrap
Frequently asked questions: This demo website has few features similar to quora and other Q&A forum websites.

To run this project on your local:
Clone:
https://github.com/Aakashsethi/FrequentlyAsked

Composer:
CD into FAQ and run composer install

env file:

cp .env.example to .env

Database Setup

Setup sqlite database

Generate artisan key

php artisan key:generate

Migrate php artisan migrate



#ABOUT FAQ Epic Story explaining the key features:

There is only one type of Access types/roles (Access controls) for a user

Register and Create Profile:
To become a website user can create an account using email. Once logged in, the user should be able to create his/her profile and can also Edit it! Ask questions: A user once logged in will be able to create questions, view the questions and edit the questions admin, one should be able to view the faqs and view the users. Answer a question: A user once logged in can answer a question, edit and delete it.

Answer Notifications (via database):
Once a question is answered, the user is notified that his/her question is notified via database. The count of the notifications depends on the number of answers.

Link to Heroku App This app is only till the point where user can create and answer questions. When tried to push the notification feature, heroku is showing an database error-https://freqas.herokuapp.com/


