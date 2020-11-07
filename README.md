# video-link

The backend is actually on GCP.
Owambe is a fundraising website.


The images used on this website are stored in a bucket on Google Cloud console.
An nginx webserver was installed in a VM and a MySQL database was set up to receive messages from people.
The VM was connected to the MySQL database.
I've included pictures of the two instances — VM and database.

The idea is that when people do contact us, their messages will be stored in the MySQL database at GCP for us to read.
