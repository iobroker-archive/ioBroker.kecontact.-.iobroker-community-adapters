![Adapter Logo](admin/charger.png)

# ioBroker adapter for KEBA KeContact wallbox

[![NPM version](http://img.shields.io/npm/v/iobroker.kecontact.svg)](https://www.npmjs.com/package/iobroker.kecontact) [![Downloads](https://img.shields.io/npm/dm/iobroker.kecontact.svg)](https://www.npmjs.com/package/iobroker.kecontact) [![Travis](https://img.shields.io/travis/UncleSamSwiss/ioBroker.kecontact.svg)](https://travis-ci.org/UncleSamSwiss/ioBroker.kecontact/) [![AppVeyor Build Status](https://img.shields.io/appveyor/ci/UncleSamSwiss/iobroker-kecontact-fxdvr.svg)](https://ci.appveyor.com/project/UncleSamSwiss/iobroker-kecontact-fxdvr) [![GitHub issues](https://img.shields.io/github/issues/UncleSamSwiss/ioBroker.kecontact.svg)](https://github.com/UncleSamSwiss/ioBroker.kecontact/issues)

Provides information about the current state of a KEBA KeContact wallbox using its UDP protocol.

## Install

Install this adapter via ioBroker Admin:
1. Open instance config dialog
2. Enter the IP address of your KEBA KeContact wallbox
3. Adjust the refresh interval if needed
4. Save the configuration
5. Start the adapter

## Configuration

### KeContact IP Address

This is the IP address of your KEBA KeContact wallbox.

### Refresh Interval

This is the interval in seconds how often the wallbox should be queried for new values.

The default value is 30 seconds which is a good balance between the load for the KeConnect and having up-to-date information in ioBroker.

## Changelog
### 0.0.1
* (UncleSamSwiss) Initial version

## Legal

This project is not affiliated directly or indirectly with the company KEBA AG.

KeConnect is a registered trademark of KEBA AG.
