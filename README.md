# Oslo CoDe Academy 2019

Agenda and materials for the 2019 versions of CoDe Academy

## General stuff

### WIFI Access
SSID: Eduroam

### Slack
You can access the CoDe Academy slack here: [codeacademyoslo2019](https://join.slack.com/t/codeacademy2019oslo/shared_invite/enQtNzE1NzIyNDg5MTA5LTQwYzEwYjA2NWIyMTFlMmZjNzlmYmUyYjA0NjQzNjc0MmYyMjgxZmIzMjU2MDg3Zjg0OGVjZTFmMzYzOGEzZDg)

### Installation
Git: [git-scm.com](https://git-scm.com/)


## Day 1
### Agenda
* Welcome
* Introduction to Continuous Delivery [slides](https://docs.google.com/presentation/d/10ZfrNvXuHQv4v2WHqq5tcnlJJwKoZL5mOD8__sGPhr8/edit?usp=sharing)
* Lego game 
* Lunch
* Lego game [Instructions](https://github.com/praqma-training/lego-scrum-game)
* Git Basics [Slides day1](https://drive.google.com/file/d/12v-AcNHrdzJ708KEjM0mbBX7PsbeYPAn/view?usp=sharing)
* Xtra: Problem solving



## Day 2
### Agenda
* Recap
* Testing
* Git 2
* Lunch
* Docker


## Day 3

### Agenda

* Recap
* Docker 2
* Lunch
* CircleCI

## Day 4
### Agenda

* 9.00 Bringing it all together
* 12.00 Lunch
* 13.00 Bringing it all together
* 15.00 Show off and evaluation
* 16.00 Socializing, thanks for this time!


# Cloud Setup

* Download the user file.
* Unpack the users.zip
* Go into the user number you have chosen with Git bash for windows, and the terminal for UNIX
* There will be three files: `docker-1.txt`,`user<number>-lab.pem`, and `user<number>-lab.ppk`
* `docker-1.txt`: will have the IP address of the AWS instance. You need it to log into the server.
* both `user<number>-lab` files are private key files to use to log into your instance
* To log in, execute: `ssh -i user<number>-lab.pem ubuntu@<ip>` to log into your server
