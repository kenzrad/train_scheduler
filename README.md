# train_scheduler
Firebase, Javascript, moment.js, HTML5


### Overview
*  A dynamically generated train schedule application that incorporates Firebase to host arrival and departure data
*  Retrives and manipulates data with Moment.js
*  Contemperaneously updates train information about various trains (arrival times, minutes until arrival at station)
*  Administrators can submit the following: train time, destination, first train time (military time), frequency (in minutes)
*  Calculates next train time arrival (relative to current time)
*  Multiple users can view the same train times



### Bonus (Extra Challenges)

* Consider updating your "minutes to arrival" and "next train time" text once every minute. This is significantly more challenging; only attempt this if you've completed the actual activity and committed it somewhere on GitHub for safekeeping (and maybe create a second GitHub repo).

* Try adding `update` and `remove` buttons for each train. Let the user edit the row's elements-- allow them to change a train's Name, Destination and Arrival Time (and then, by relation, minutes to arrival).

* As a final challenge, make it so that only users who log into the site with their Google or GitHub accounts can use your site. You'll need to read up on Firebase authentication for this bonus exercise.
