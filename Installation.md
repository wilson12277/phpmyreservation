# Installation #

Before you start, read the [requirements](http://code.google.com/p/phpmyreservation/#Requirements).

## Create MySQL tables ##

It is a good idea to backup your database first.

**1)** Download [this SQL file](http://www.olejon.net/code/phpmyreservation/db/phpmyreservation.sql)

**2)** Import it into your MySQL database using the mysql command (google it) or a tool like phpMyAdmin

## Install phpMyReservation ##

**1)** Download and extract phpmyreservation-x-x.tar.bz2

**2)** Edit config.php. Secret code is 1234 by default. Set to 0 to disable.

**3)** Move the phpmyreservation folder to where it can be reached through your web server

**4)** If you chose to enable reservation reminders in config.php, [read this](ReservationReminders.md) to make it work

**5)** Open phpMyReservation in a web browser. If you have done everything correctly, you should see the login page

**6)** Create a new user. The first created user will get admin rights

**7)** Set the price per reservation in the control panel (just set to 0 if usage is free)