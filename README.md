# meteor-ci
Testing Meteor plus Circle-CI

### Jasmine
JASMINE_BROWSER=PhantomJS meteor --test --release velocity:METEOR@1.1.0.2_3 --port 4000

### Cucumber
sudo npm install -g phantomjs
export PHANTOM_PATH=/usr/local/bin/phantomjs
