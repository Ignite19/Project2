# Project2



**Journal Entry 11:38 AM 9/6/2016**

Studied what CGI is:
https://en.wikipedia.org/wiki/Common_Gateway_Interface


-CGI: Bassically offers a way for webservers to interact with executable programs running on a sever that generate dynamic
	webpages
- Web Servers use HTTP software which responds to web server requests -> HTTP have directories(folders) which hold documents
	->EXAMPLE of interaction:  if the Web server has the domain name example.com, and its document collection is stored 
	at /usr/local/apache/htdocs in the local file system, then the Web server will respond to a request for 
	http://example.com/index.html by sending to the browser the (pre-written) file /usr/local/apache/htdocs/index.html.
- CGI Directory: Holds executable scripts, not premade pages like index example ^
	EXAMPLE:For example, /usr/local/apache/htdocs/cgi-bin could be designated as a CGI directory on the Web server. 
-If a Web browser requests a URL that points to a file within the CGI directory (e.g., http://example.com/cgi-bin/printenv.pl), 
	then, instead of simply sending that file (/usr/local/apache/htdocs/cgi-bin/printenv.pl) to the Web browser, the HTTP 
	server runs the specified script and passes the output of the script to the Web browser. 

Studied more on CGI:
http://www.cgi101.com/learn/intro.html

-CGI is a program intended to be run on the web
-Used "Individual Primer" aswell as Lynda tutorial to pull up this:

BW Test version 5.1
Copyright 1995-2009 The BearHeart Group, LLC

Versions:
=================
perl: 5.008008
CGI: 3.43

CGI Values:
=================

Environment Variables:
=================
DOCUMENT_ROOT [/web/data/groups/www_site/public_html]
GATEWAY_INTERFACE [CGI/1.1]
HTTP_ACCEPT [text/html,application/xhtml+xml,application/xml;q=0.9,image/webp,*/*;q=0.8]
HTTP_ACCEPT_ENCODING [gzip, deflate, sdch]
HTTP_ACCEPT_LANGUAGE [en-US,en;q=0.8]
HTTP_CACHE_CONTROL [max-age=0]
HTTP_CONNECTION [keep-alive]
HTTP_COOKIE [_ceir=1; __utma=207094401.119368498.1447686553.1468339054.1468943916.13; __utmz=207094401.1468943916.13.13.utmcsr=mynorthridge.csun.edu|utmccn=(referral)|utmcmd=referral|utmcct=/psp/PANRPRD/; _ceg.s=ocqk8m; _ceg.u=ocqk8m; _ga=GA1.2.119368498.1447686553; BIGipServerSF_WEB_PRODUCTION_HTTP=116303490.20480.0000]
HTTP_HOST [www.csun.edu]
HTTP_REFERER [http://www.csun.edu/~jnp43115/cgi-bin/]
HTTP_UPGRADE_INSECURE_REQUESTS [1]
HTTP_USER_AGENT [Mozilla/5.0 (Windows NT 6.3) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/52.0.2743.116 Safari/537.36]
HTTP_VIA [1.1 f5-sf]
HTTP_X_FORWARDED_FOR [104.173.3.253]
PATH [/bin]
PERL5LIB [/web/lib/perl/lib64/perl5/site_perl/5.8.8/x86_64-linux-thread-multi:/web/lib/perl/lib/perl5/site_perl/5.8.8:/web/lib/perl/lib/perl5/5.8.8]
QUERY_STRING []
REMOTE_ADDR [130.166.238.1]
REMOTE_PORT [4601]
REQUEST_METHOD [GET]
REQUEST_URI [/~jnp43115/cgi-bin/test.cgi]
SCRIPT_FILENAME [/home/users6/jnp43115/public_html/cgi-bin/test.cgi]
SCRIPT_NAME [/~jnp43115/cgi-bin/test.cgi]
SERVER_ADDR [130.166.238.6]
SERVER_ADMIN [helpdesk@csun.edu]
SERVER_NAME [www.csun.edu]
SERVER_PORT [80]
SERVER_PROTOCOL [HTTP/1.1]
SERVER_SIGNATURE [<address>Apache/2.2.3 (Red Hat) Server at www.csun.edu Port 80</address>
]
SERVER_SOFTWARE [Apache/2.2.3 (Red Hat)]

**JOURNAL 11:20 AM 9/10/2016**

- Researched HTTP WIKI
- Learn Bash language
- Continued plugging away at the project

**Journal 11:21 AM 9/11/2016**

- Researched GitHub
- http://www.csun.edu/~jnp43115/cgi-bin/Project2.cgi
