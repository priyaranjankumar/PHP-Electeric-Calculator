# PHP-Electeric-Calculator

Simple PHP program for demonstration the basics of PHP.

## Problem Statement
```
You are required to print electricity bill for the no of unit. Units must be given as an
input by the user, it will print the electricity bill using: i. For first 50 units, it will
charge Rs 9 per unit ii. For next 50 units, it will charge Rs 12 and iii. Above it, it will
charge Rs 15.

```
### Solution:
PHP is scripting langauage which does run directly on browser. for running them you need to setup a server or use online server. For local server we will be using **apache** and **php**.

## Prerequisites
* Apache
* PHP

## Installing Prerequisites

For Apache
```
sudo apt-get install apache2
```
For PHP
```
sudo apt-get install php

```
## Steps to Run the Code
* After installing apache2. 

**Step:1**  
Saving the old page of apache welcome.(Incase you may need that in future.)
Open the terminal and execute this.
```
sudo mv /var/www/html/index.html /var/www/html/index.back

``` 
**Step:2**  
Make a PHP file to writre code in it.

```
sudo gedit /var/www/html/index.php

```

**Step:3**


Now open the the index.php shared file and copy the codes from it and paste it.

or

You can skip **Step: 2** and copy the file directly into the html folder.

```
sudo cp index.php /var/www/html/

```
**Step:4** 
Restart Apache 

```
sudo systemctl restart apache2

```

