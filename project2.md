[Back to Portfolio](./)

Warfighter Foundation 5k
===============

-   **Class:** CSCI 334
-   **Grade:** A
-   **Language(s):** Ruby on Rails
-   **Source Code Repository:** [Warfighter Foundation 5k](https://github.com/adamrt918/UIP_FinalProj)
    (Please [email me](https://mail.google.com/mail/u/0/?source=mailto&to=thiemann.adam@gmail.com&su=Github_Access&fs=1&tf=cm) to request access.)

## Project description

This project displays the ability to create and manage a website using the Ruby on Rails framework.

## How to compile and run the program

To get started with the app, clone the repo and then install the needed gems:

```
$ gem install bundler -v 2.3.14
$ bundle _2.3.14_ config set --local without 'production'
$ bundle _2.3.14_ install
```

Next, migrate the database:

```
$ rails db:migrate
```

Finally, run the test suite to verify that everything is working correctly:

```
$ rails test
```

If the test suite passes, you'll be ready to run the app in a local server:

```
$ rails server
```
To access the admin features, please run this command  in your command line before logging in.: 
```
 $ rails db:seed 

## UI Design

This program allows users to sign up for a charity organization's mailing list and 5k race. It also displays knowledge of back end processes to hold users in the database, display teams of runners, and create a seperate admin page for management of users.

[Back to Portfolio](./)
