# Firetary webservice
Firetary (Firefox OS virtual assistant) server running at firetary.appspot.com

## Running
```
/path/to/google/appengine/dev_appserver.py /path/to/firetary/folder --executable_path=/path/to/php-cgi
```

Example:

```
../google_appengine/dev_appserver.py firetary/ --executable_path=../php-5.4.25/installdir/bin/php-cgi
```
