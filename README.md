# Trondheim CoDe Academy 2019

Agenda and materials for the 2019 versions of CoDe Academy

## General stuff

### WIFI Access
SSID: Eduroam or NTNUGuest

### Slack
You can access the CoDe Academy slack here: [codeacademytronheim2019](https://join.slack.com/t/codeacademytr-b4a3814/shared_invite/enQtNjYxODE3OTgwODcxLTllNjBlN2QxMmVkY2VkNjg0NGM3MThmNGFhNmNmNjdiMzFlNTRkNTJmODkxMzhkZWVjNDJmNTUxMjFjNTJkODI)

### Installation
Git: [git-scm.com](https://git-scm.com/)


## Day 1
### Agenda
* Welcome
* Introduction to Continuous Delivery [Slides](https://docs.google.com/presentation/d/e/2PACX-1vRQRsg9TsPIJvvsT4_lPWL_Dy12OcZSL7P1PH6IkgWwRgrWCCkRxjFBVtzE0cz4qx0jgA5p0d2iELN7/pub?start=false&loop=false&delayms=3000)
* Lego game [Slides](http://code.praqma.com/reveals/code-academy/lego-scrum/#/)
* Lunch
* Lego game
* Git Basics [Slides](https://docs.google.com/presentation/d/e/2PACX-1vR4S2EGAxtOB8LQCJ1ivCupcJPD5_K02cYFzb5AwOMKnzLSBOMWyrID0-XDEWKfoSKaEQMPYOWCBNQM/pub?start=false&loop=false&delayms=3000) |[Slides2](https://docs.google.com/presentation/d/e/2PACX-1vQpT2k4Jmmc6QXJEhHnUfJsoeBlFsdybf3JtDH-kh1QnHxKdrDZYo938raim1D2usjsxMd3mT-_H2dg/pub?start=false&loop=false&delayms=3000)| [exercises](https://github.com/praqma-training/git-katas)
* Xtra: Problem solving



## Day 2
### Agenda
* Recap
* Testing
* Git 2
* Lunch
* Docker [Slides](https://docs.google.com/presentation/d/1zigkGc2R8p64VK78Cx0iyJh_fRtJ6b8Me69NSzTKZyk/present?slide=id.p10) | [Exercises](https://github.com/praqma-training/docker-katas)


## Day 3

### Agenda

* Recap
* Docker 2
* Lunch
* Jenkins

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
