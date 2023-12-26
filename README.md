Simple HTTP server that  supports file upload  for moving data around
between boxen on HTB. Based on a gist by bones7456, but mangled by me 
as I've tried  (badly) to port it to Python 3, code golf it, and make
It a  little more  robust. I was also able to  strip out a lot of the 
code trivially  because Python3 SimpleHTTPServer is  a thing, and the
cgi module handles multipart data nicely.