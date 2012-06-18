# Buildbot SMS

Buildbot SMS sends you an sms when your build completes.

### To use:
Prepend bbot to any command to receive a text with the exit status when it completes.

```
bbot ant long-running-build
```

### To setup:

* Download the `bbot` script, and add it to your path
* Install the [Twilio Python library](https://github.com/twilio/twilio-python) `pip install twilio`
* Fill in `TWILIO_ACCOUNT_SID`, `TWILIO_AUTH_TOKEN`, `TWILIO_FROM`, `BBOT_TO` in `bbot`
