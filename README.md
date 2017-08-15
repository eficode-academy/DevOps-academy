# academy-2017
Agenda and materials for the 2017 versions of CoDe Academy
## General stuff

### WIFI Access
SSID: AU-guest

### Slack
You can access the CoDe Academy slack here: [CoDe Academy Slack](https://code-academy.slack.com)

### Installation
Git: [git-scm.com](https://git-scm.com/)


## Day 1
### Agenda
* Welcome and project intro
* Introduction to Continuous Delivery [Slides](https://files.slack.com/files-pri/T6J8MD8BW-F6KQ9KV8D/continuous_delivery_academy_-_intro.pdf)
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
* Testing [Slides](https://files.slack.com/files-pri/T6J8MD8BW-F6K1GS7S5/writing_good_tests.pdf) | [Survey](https://goo.gl/forms/bSlfDxjxrdgBKGq22)
* Jenkins [Slides](http://code.praqma.com/reveals/code-academy/basic-jenkins) | [Survey](https://docs.google.com/forms/d/e/1FAIpQLSeoHUWH9Sofip5PW6Ut9wfZTHsYbP9xd9NnqrcN5ukWe2JLiA/viewform?usp=sf_link)
* Lunch
* Advanced git + PIP [Slides](https://files.slack.com/files-pri/T6J8MD8BW-F6LEWS0KY/git-3.pdf) | [Survey](https://docs.google.com/forms/d/e/1FAIpQLSdceqBcfeVolJi08Sni4432S_dOExq6WL7MyuFrod3R0rI-Lw/viewform?usp=sf_link)



## Day 3
### Agenda
* Recap
* Docker [Slides](https://docs.google.com/presentation/d/1lya4AI7w7QYoVNZuXE7ysY-pwDuhPvpkeYlfnumdvFw/pub?start=false&loop=false&delayms=3000) | [Survey](https://docs.google.com/forms/d/e/1FAIpQLSe2HND_TjxpZemuAnSyF5MHAaRXeG63thv-_rHGgbayObS9dw/viewform?usp=sf_link)
* Lunch
* Advanced Docker (same slides and survey as Docker)
* Advanced Jenkins [Slides](http://code.praqma.com/reveals/code-academy/advanced-jenkins/#/) | [Survey](https://docs.google.com/forms/d/e/1FAIpQLScccvOs2b00Fw4Rcgt5NIOhDv-bOzqRjvMXJWQnBVEWr4WRxg/viewform?usp=sf_link)

## Day 4
### Agenda

* 9.00 Bringing it all together [Assignment](https://github.com/praqma-training/ca-project)
* 12.00 Sponsor + Lunch
* 13.00 Bringing it all together
* 15.00 Show off and evaluation [Survey](https://docs.google.com/forms/d/e/1FAIpQLScx1T4OZXVVv0X-qZkLQQWSNVHrss7CelRqB8JbIYbwXJlWxQ/viewform?usp=sf_link)
* 16.00 Socializing, thanks for this time!


# AWS Setup

* Download the file above (password is on slack)
* Unpack the users.zip
* Go into the user number you have chosen with Git bash for windows, and the terminal for UNIX
* There will be three files: `docker-1.txt`,`user<number>-lab.pem`, and `user<number>-lab.ppk`
* `docker-1.txt`: will have the IP address of the AWS instance. You need it to log into the server. 
* both `user<number>-lab` files are private key files to use to log into your instance
* To log in, execute: `ssh -i user<number>-lab.pem ubuntu@<ip>` to log into your server
