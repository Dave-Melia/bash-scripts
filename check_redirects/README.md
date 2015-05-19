## check_redirects

This is a useful Bash script for checking redirects in bulk.

### Usage

You will need to edit foo.list and place in your source/destination URIs on each line; it should look like this:

/dvd/1/123456.html /home.html

/dvd/2/123456.html /home.html

Above is the source URI and the destination URI on the same line.

```bash
[dave@enterprise ~]$ bash check_redirects 
Enter the host (e.g. www.host.com): www.host.com
Enter the server (e.g. testweb999.local.domain): testweb999.local.domain
[OK]: /dvd/1/123456.html redirects to /home.html
[OK]: /dvd/2/123456.html redirects to /home.html
[OK]: /dvd/3/123456.html redirects to /home.html
[OK]: /dvd/4/123456.html redirects to /home.html
```

The script will compare the source to the destination before moving on to the next line.



> "The best way to find yourself is to lose yourself in the service of others." - Mahatma Gandhi
