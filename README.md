# Green Up! Seattle

#### *10 teams of Seattle neighborhoods compete for the title of "Greenest Hood" by playing a waste sorting game to earn points for their team!* 

### Motivation

With a partner, I created Green Up! Seattle because I noticed people were always stalling in front of the waste bins trying to figure out whether their trash goes in the garbage, recycling, or compost. Half of the time, they would end up putting it in the wrong bin. I wanted to create an app that would educate people who live and work in Seattle to properly dispose of their trash, but in a fun way.

By offering an incentive (such as 20% off their recycling bill), users would be encouraged to participate and earn points for their team, as well as recruit others to play. Through repeat exposure to common waste items, people would learn to put their waste in the right place! 

### Overview

The app features a game called **Bin It to Win It!** which displays pictures of common household waste items which the user must place in the right bin. One game consists of 5 rounds and each correct answer is worth 10 points. Users can play as many times as they wish.

A user will earn points for the neighborhood they selected when they signed up. A user may change hoods, but all points earned prior will remain with that hood.

Each hood has its own profile page, which displays all of its sub-hoods, members, and ranking. All hoods are listed on a leaderboard, providing motivation for users to earn more points for their team.

User profiles are editable, and display username, name, hood, level, and total points. A user's level is based on the total number of points they have earned.

There is a resource page with links to more information on recycling, compost, and garbage for users who want more information.

All of the waste items used in the game were taken directly from the city of Seattle's waste guidelines. 

## Technology

* Full Ruby on Rails app with MVC framework
* PostgreSQL database using ActiveRecord
* Secure password using Bcrypt
* Automated image seeding using Regex to parse filenames
* Bootstrap CSS for styling
* User validation using session IDs

## Installation

To run the app on your machine:
```
$ git clone [REPO]
$ rails db:setup
$ rails s
```

Live site is hosted at https://greenupseattle.herokuapp.com/

## Screenshot


## License
 MIT © jyang81
