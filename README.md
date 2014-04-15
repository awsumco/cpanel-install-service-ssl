cpanel-install-service-ssl
==========================

Python App to Install Service SSL on a cPanel Server via Command Line 

No Extra python modules needed, has been tested with python 2.7.

### Usage

	Usage: cpanel-install-service-ssl -h
	Install Service SSL on a cPanel Server via Command Line.
	Options:
	  --version            show program's version number and exit
	  -h, --help           show this help message and exit
	  --hostname=HOSTNAME  [REQUIRED] The hostname of the host you intend on
	                       installing the SSL cert on.
	  --username=USERNAME  WHM username, normally root. If not supplied will use
	                       root
	  --password=PASSWORD  [REQUIRED] Password of the user.
	  --service=SERVICE    [REQUIRED] These services are ftp, exim, dovecot,
	                       courier, and cpanel.
	  --crt=CRT            [REQUIRED] Path to the KEY .crt file.
	  --key=KEY            [REQUIRED] Path to the KEY .key file.
	  --ca=CA              [REQUIRED] Path to the KEY .cabundle file.	