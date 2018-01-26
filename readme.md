#How to run test?
## Composer

Install dependencies:

```bash
composer install
```

## Linux
Google chrome or chromium running with remote debugging:
```bash
google-chrome-unstable --disable-gpu --headless --remote-debugging-address=0.0.0.0 --remote-debugging-port=9222
```
Run test with profile:
```bash
vendor/bin/behat --config behat.yml --profile linux
```

##Mac os

You must run selenium server:
```bash
java -jar selenium-server-standalone-3.7.1.jar
```
Run test with profile:
```bash
vendor/bin/behat --config behat.yml --profile win
```






vendor/bin/behat --config behat.yml --profile linux

