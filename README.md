# Java-TestNG-General-Demo

Clone à la Berg
[Java-TestNG-General-Demo](https://github.com/KevinMarkVI/Java-TestNG-General-Demo)

## ——————————————————————————————

#### Run a Maven Test

```
# update any package dependencies
mvn dependency:resolve

# compile the test code
mvn test-compile

# validate test environment configuration
mvn test -Dtest=Module2TestNGTest -pl on-boarding-modules/testng

# run a specific test
mvn test -Dtest=testname

# run a specific sub-module.
mvn test -pl subproject/
```



#### TODO

* Auto Tunnel
* Dynamic Capabilities Definitions




#### Demo Script

```
# using shell aliases

# open sauce connect tunnel
scq

# start dev site
web

# run tests
dxt
