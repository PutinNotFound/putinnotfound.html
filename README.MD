1. Create .htaccess on root directory of the site.

2. Edit .htaccess. Add rows

RewriteEngine on
ErrorDocument 404 https://MYSITE.COM/putinnotfound.html , 

here MYSITE.COM replace by real URI your website.

3. Copy putinnotfound.html to root of the site.

4. Testing: get any URI in browser, like https://MYSITE.COM/bla-bla-bla.html. If redirect work - all are OK. Otherwise edit again.
