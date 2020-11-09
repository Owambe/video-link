

The backend is actually on GCP.
Owambe is a fundraising website.


The pictures used on this website are stored in a bucket on Google Cloud console.


An apache webserver was installed in a VM along with PHP and MySQL server.

They were set up to receive messages from the "Contact Us" webpage.


So the MySQL database is inside the VM.


— the name of the database is dev_to

— a table named test was created inside it

— the columns created were named 'name', 'email' and 'message' respectively


The "contact us" page is located at /var/www/HTML/index.html and it is submitted to submit.php

submit.php is located at /var/www/HTML/submit.php


I've included pictures to show you.


The idea is that when people do contact us, their messages will be stored in the MySQL database for us to read.
