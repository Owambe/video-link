# Link to LOOM recording:

1st link:https://www.loom.com/share/4b7789561e93494aaf818e1f1f6d254e

2nd link:https://www.loom.com/share/87cf92ba428444dab097f2ccbccbe415?sharedAppSource=personal_library




Initially we wanted to host the backend on firebase but later decided to host it on Google cloud platform instead.




The backend is actually on Google Cloud — GCP.
Owambe is a fundraising website.


The pictures used on this website are stored in a bucket on Google Cloud console.

We created a VM and named it 'apache2-server'


An apache webserver was installed in the VM along with PHP and MySQL server.

They were set up to receive messages from the "Contact Us" webpage.


So the MySQL database is inside the VM.


— the name of the database is 'dev_to'

— a table named 'test' was created inside the database.

— the columns in the table were named 'name', 'email' and 'message' respectively


The 'contact us' page is located at /var/www/html/index.html and it is submitted to a PHP file named 'submit.php'

'submit.php' is located at /var/www/html/submit.php


I've included pictures to show you.


The idea is that when people do contact us, their messages will be stored in the MySQL database for us to read.
