# Project-Alpha2
A Chatbot trained on IIT Bombay’s data
This is an experimental chat bot (in it's early stage) that is set on the data of the institute, IIT Bombay.
This bot uses Rasa Open Source framework.
A lot of work still has to be done. More functionality and a larger database is to be used in future. Currently, the bot is able to tell the department of professors, the professors of a certain department, information about some events, etc. (so give it a try, maybe?)

# How to use?
1.) Clone this repository into yout system by using:
git clone https://github.com/FakeFame388/Project-Alpha2
2.) Make sure you install RASA into your system. Follow the offical guide at https://rasa.com/docs/rasa/installation/installing-rasa-open-source/
for doing so.
3.) Move to the clone project directory.
4.) Run the following command:
rasa train
5.) In another terminal window in the same directory, run the following command:
rasa run actions
6.) In the other window, run the following command:
rasa shell
7.) Enjoy using the bot :)

# Features:
Can be used to chit chat a little along with getting to know about professors and the insti.
example: What is the department of the prof Tara Shaw? 
example: Who are the profs of the Chemical dept?
example: List the professors at IITB.
