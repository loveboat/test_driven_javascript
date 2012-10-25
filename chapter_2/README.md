# Test Driven Javascript #

Examples and tutorials from the Test-Driven JavaScript book by Christian Johansen 

## Commands
Server start
    java -jar $JSTESTDRIVER_HOME/JsTestDriver-1.2.1.jar --port 4224

Then visit `http://localhost:4224` for every browser you wish to attach to this server. Multiple servers can be run so a lean, single browser, server can be used as a default with periodic testing on a much 'fatter' more heavily connected server can be performed.

Client test
    java -jar $JSTESTDRIVER_HOME/JsTestDriver-1.2.1.jar --tests all
		
Client reset
    java -jar $JSTESTDRIVER_HOME/JsTestDriver-1.2.1.jar --reset


Add Ruby gems for test runner control
    gem install jstdutil
		
Test all
    jstestdriver --tests all
		
Auto-runner for tests :)
    jsautotest

## JsTestDriver Installation
Create a path variable to point to the .jar directory in ~/.bash_profile
    export JSTESTDRIVER_HOME=~/Developer/jstestdriver

