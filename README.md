# css-regression-testing
Boiler plate for css regression testing


If you don't already have a global Gulp instance... http://gulpjs.com
$ sudo npm install -g gulp

If you don't already have a global PhantomJS install... http://phantomjs.org/download.html
$ sudo npm install -g phantomjs

If you don't already have a global CasperJS install... http://docs.casperjs.org/en/latest/installation.html
$ sudo npm install -g casperjs

Node modules are included, I'll take them out as soon as i figure out were some the reference data lives

Run
$ npm install 


Tests have to be run from

./node_modules/backstopjs

Command to run test

$gulp test

Command to update reference

$gulp reference

