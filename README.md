# academy-2017
Agenda and materials for the 2017 versions of CoDe Academy
## General stuff

### WIFI Access


### Slack
You can access the CoDe Academy slack here: [CoDe Academy Slack](https://code-academy.slack.com)

### Installation
Git: [git-scm.com](https://git-scm.com/)


## Day 1
### Agenda
* Welcome and project intro
* Introduction to Continuous Delivery
* Lego game
* Lunch
* Lego game
* Git Basics
* Xtra: Problem solving
* Snacks and social



## Day 2
### Agenda
* Recap
* Jenkins
* Testing
* Lunch
* Advanced git + PIP



## Day 3
### Agenda
* Recap
* Docker
* Lunch
* Advanced Docker
* Advanced Jenkins

## Day 4
### Agenda

* 9.00 Bringing it all together
* 12.00 Lunch
* 13.00 Bringing it all together
* 15.00 Show off and evaluation
* 16.00 Socializing, thanks for this time!


# AWS Setup

* Download the user file.
* Unpack the users.zip
* Go into the user number you have chosen with Git bash for windows, and the terminal for UNIX
* There will be three files: `docker-1.txt`,`user<number>-lab.pem`, and `user<number>-lab.ppk`
* `docker-1.txt`: will have the IP address of the AWS instance. You need it to log into the server. 
* both `user<number>-lab` files are private key files to use to log into your instance
* To log in, execute: `ssh -i user<number>-lab.pem ubuntu@<ip>` to log into your server
