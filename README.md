# JavaScript SDK for AT&T Enhanced WebRTC API

# SDK Contents

* `/js/ewebrtc-sdk.min.js`: JavaScript client library for the AT&T Enhanced WebRTC API
* `/node-sample/`: Node.js Sample application
* `/node-sample/public/tutorial/index.html`: AT&T Enhanced WebRTC JavaScript SDK tutorial
* `/node-sample/public/api-docs/index.html`: JS SDK API reference documentation

# Using the Sample Application

The following section is an overview for setting up the AT&T Enhanced WebRTC sample application. The sample app can be used as a reference and starting point for your own applications.

For full instructions on deploying this SDK and sample app, see the [Enhanced WebRTC JavaScript SDK page](http://developer.att.com/sdks-plugins/enhanced-webrtc) on the AT&T Developer Program Web site.

## Summary

* Enroll in the [AT&T Developer Program](http://developer.att.com/).
* Set up your app on the AT&T Developer Program website, configure it for WebRTC and obtain an App Key and App Secret.
* Configure the Node.js sample app package.json with your App Key, App Secret, ewebrtc_domain (org domain),
  virtual_numbers_pool, and oauth_callback address.
* Install the Node.js sample app dependencies by running `$ npm install` in the `node-sample` directory.
* Start the sample app Web server by running `$ npm start` from the `node-sample` directory.
* Open Firefox or Chrome to run the sample application at the address, `https://127.0.0.1:9001/`
* When initially loading the sample app you will receive the error, `NET::ERR_CERT_AUTHORITY_INVALID`. You must add a security exception by clicking `Advanced` and then click on `Proceed to 127.0.0.1 (unsafe)`

## System Requirements

* [Node.js](http://nodejs.org/download/)
* Google Chrome version 42.x or later (tested).
* Node.js (quick-start deployment), available from [Nodejs.org](http://nodejs.org/download/)
* Ruby, Java or PHP (production environment). For more information on a production deployment see [Enhanced WebRTC JavaScript SDK page](http://developer.att.com/sdks-plugins/enhanced-webrtc).


# Further reading

* AT&T Enhanced WebRTC JavaScript SDK configuration, deployment and samples: http://developer.att.com/sdks-plugins/enhanced-webrtc
* DHS Library Release Notes: [`/node-sample/RELEASE.md`](/node-sample/lib/RELEASE.md)
* Sample App ReadMe: [`/node-sample/README.md`](/node-sample/README.md)
* Sample App Release Notes: [`/node-sample/RELEASE.md`](/node-sample/RELEASE.md)

## DHS Samples

* AT&T Node DHS: [`ewebrtc-dhs-restify`](https://github.com/attdevsupport/ewebrtc-dhs-restify)
* AT&T PHP DHS:[`ewebrtc-dhs-php`](https://github.com/attdevsupport/ewebrtc-dhs-php)
