# UVA Geo-guessing App
We developed a competitive forum for users to guess locations posted by other users around UVA grounds with limited information, with an active points leaderboard. The game uses a daily challenge structure, where users are presented with one location to guess per day. However, former day's challenges also appear to ensure all users can complete all of the challenges!

Hosted on Heroku (for now): https://project-b24-12f95dd04436.herokuapp.com/

__Contributers:__ Kyle Tran, Ravi Jayaraman, Niket Anand, Thomas Reiter, Hennok Tilahun

# What I Contributed
For this project, I participated in developing the Google login on the homepage through Google OAuth. The framework we used for this project was Django, so my teammates and I had a learning curve because we were unfamiliar with how Django works. In addition to implementing the Google login, I helped integrate the Google Maps API for the main guessing portion of our app. Through online tutorials, I was able to find a lot of resources to guide my work. I also aided in making the daily challenge feature of the app by creating a custom Django command that allows a daily challenge to be added daily. While implementing these features, I also aided my group mates as needed as well as writing Python test cases in our test suite.

# Development Process
In developing this project, we followed a general software development cycle with the steps of requirements, design, implementation, testing, and maintenance. In the first step, we gathered requirements through elicitation. We had a Google form that we used in communicating to our stakeholders what requirements our project should have. From there, we created storyboards so that our group members could work on different features during each sprint. Throughout the development of the project, we had 6 check-in sprints, following an agile-like development. In our sprints, we would meet with a teaching assistant to assess our project progress and have the opportunity to ask any questions.

# How it Works
For now, this project is hosted on heroku. However, to run this web application locally, clone this repo. Then, activate the virtual environment by typing "./env/Scripts/activate" in the console. Then, run the command "python manage.py runserver" on your console. The web application should then be able to run locally. When running locally, if you want to add daily challenges, simply type the command "python manage.py add_daily_challenge". On the hosted heroku website, this command is automatically run every 24 hours as long as there is a challenge in the challenge bank.


