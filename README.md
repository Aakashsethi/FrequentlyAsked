# FrequentlyAsked
To Run the FAQ Project 
#Link to heroku
http://freqas.herokuapp.com/

#link to localhost display
https://docs.google.com/document/d/1hwhLJZtmhsfH7Q1kmPcY9gVwa1EDNr6RG9V96KfkejM/edit?usp=sharing

git clone https://github.com/Aakashsethi/FrequentlyAsked.git
CD into faqand run composer install
cp .env.example to .env
setup database / with sqlite or other https://laravel.com/docs/5.6/database
#FAQ Project by Aakash Sethi

Epic: Implementing notification system where user will get notification email when their question is answered or updated.

User Stories:

User will get email verification after registering to the application.
Registered Users will be notified when someone answers their question.
Users will be notified when answer is edited.
User are redirected to the answered question when they click on 'View Answer' button in email.
Note: sendgrid account is used to send email.
