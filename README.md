This is a one - one chat api using Django and jquery.

Basic Django project is setup.
Models: A chat box containing user_id, messages and date
Urls: Links to login and logout pages alongwith home page. Home is the page where we se the entire chat window. Also there are links to posting a message and checking all the messages.
Templates: Corresponding to home window, login page and all messages window.
Style sheets : bootstrap templates
Scripts : jquery scripts
Ajax form has been used for posting the messages so that the messages entered on 1 window are immediately reflected on opposite client's window.

When a message is entered in AJAX form, control goes from template to javascript to view and then back the same path with the result.

Send button next to message for is disabled by default and it is enabled only when some message is entered in the form.

In order to view all messages, database is queried and resulting chatlist is displayed.

This application is run using following steps:

1. python manage.py migrate
2. python manage.py runserver
3. Open the given ip in 2 separate browser windows to setup 2 different clients
4. start entering messages in the form



