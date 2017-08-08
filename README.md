# academy-2017
Agenda and materials for the 2017 versions of CoDe Academy
## General stuff

### WIFI Access
SSID: ITU-guest

### Slack
You can access the CoDe Academy slack here: [codeac-cph-2017](https://join.slack.com/t/codeac-cph-2017/shared_invite/MjIyMTYyMTQxNDc1LTE1MDE4NDczMDQtMWIwOGVmYTE1MA)

### Installation
Git: [git-scm.com](https://git-scm.com/)


## Day 1
### Agenda
* Welcome and project intro
* Introduction to Continuous Delivery
* Lego game [Slides](http://code.praqma.com/reveals/code-academy/lego-scrum/#/) | [Survey](https://goo.gl/forms/ZhLXm4eHPcsGheTB3)
* Lunch
* Git Basics [Slides](https://docs.google.com/presentation/d/1pJsEyFxLLRNYdwCWaZ4UCKiHC4_tQ1hudf-PiYev8j4/pub?start=false&loop=false&delayms=3000) | [Survey](https://docs.google.com/forms/d/e/1FAIpQLSd3OO2dgdO2LZdmYMudDZmAh9oGHkjUQxX6UD0_sgYV8VvwdQ/viewform?usp=sf_link) | [More Slides](https://docs.google.com/presentation/d/1ljv4ZZTFpdO-yDgDZvCIt4k9yP1hrNrZ8T3OSpWgg34/pub?start=false&loop=false&delayms=3000)
* Xtra: Problem solving
* Snacks and social

[download the user packages for AWS](https://box.coffeedrop.dk/index.php/s/i10mIlLFd7XDc7V) **remember to write your number in slack**
Setup instructions are below the agenda.

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

* Download the file above (password is on slack)
* Unpack the users.zip
* Go into the user number you have chosen with Git bash for windows, and the terminal for UNIX
* There will be three files: `docker-1.txt`,`user<number>-lab.pem`, and `user<number>-lab.ppk`
* `docker-1.txt`: will have the IP address of the AWS instance. You need it to log into the server. 
* both `user<number>-lab` files are private key files to use to log into your instance
* To log in, execute: `ssh -i user<number>-lab.pem ubuntu@<ip>` to log into your server
