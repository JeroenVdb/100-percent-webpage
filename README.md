100-percent-webpage
===================

This website must obtain a score of 100% on all performance and best practice tests on the internet.

## Steps taken

- Added favicon so we don't get any 404 errors
- Enabled gzip via the .htaccess
- Added (long) expire dates for favicon + default expire date
- Added character encoding type to the Response Header instead of inlining it into the <head>

## Tested with

- WebPagtest: http://www.webpagetest.org/?url=jeroenvdb.be/100-percent-webpage/index.html
- Google Pagespeed: https://developers.google.com/speed/pagespeed/insights/?url=http%3A%2F%2Fjeroenvdb.be%2F100-percent-webpage%2Findex.html&tab=desktop
- GTmetrix: http://gtmetrix.com/reports/jeroenvdb.be/6LDoeAZS
