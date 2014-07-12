sunnyportal-api
-------
NodeJS API to integrate with [Sunny Portal](https://www.sunnyportal.com/).

This module can retrieve the current status of an array as well as the production for a given day.

Sunny Portal lacks an API for reading data from your solar panels. This is a simple hack to access the data.

Please review the test for examples.

***
This is just a fork of the original project from the github user [mkorthuis](https://github.com/mkorthuis/sunnyportal-api).
It is able to reuse the login session for currentProduction() and compatible with the homemanager product of SMA Solar. Add plantType = 'homemanger' to the options object.