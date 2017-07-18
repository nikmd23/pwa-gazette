---
layout: post
title: "Issue #1: Kickoff and Specs"
published: true
excerpt: "The first issue of PWA Gazette, containing links to the official specifications that are related to PWA's."
date: 2017-07-17 21:43:01 -0600
---

# Issue #1: Kickoff and Specs

Welcome to the PWA Gazette, your semi-regular-ish email newsletter devoted to Progressive Web App news and updates. Feel free to forward this to friends, who can [subscribe on the website](http://pwagazette.com/) for future updates.

## Specifications
For the first issue of PWA Gazette, we're listing out links to the official specifications that are related to PWA's. In future issues, we'll cover news, tools and techniques related to PWA's.

### [Service Workers](https://w3c.github.io/ServiceWorker/v1/)
Service Workers is first cornerstone technology behind the PWA movement. It provides for "network independence" - a fancy way of saying they enable offline functionality. [Chrome, Firefox and Opera support it today, and it's behind a flag in Edge](http://www.caniuse.com/#feat=serviceworkers).

### [Web App Manifest](https://w3c.github.io/manifest/)
Web App Manifest is the other cornerstone technology behind PWA's, and manifest file is required to be present to light up Chrome's app install banner. Essentially, the manifest provides the host operating system with metadata about how to display the app, including colors, icons and names. It's currently [supported by Chrome and Opera, and in development for Edge and Firefox](http://www.caniuse.com/#feat=web-app-manifest).

### [Fetch](https://fetch.spec.whatwg.org/) & [Promise](http://www.ecma-international.org/ecma-262/6.0/#sec-promise-objects)
Technically, the Fetch and Promise specifications have nothing to do with PWA's, however, they are prerequisites for browser vendors interested in implementing Service Workers. If you're going to work on a modern web application, you'll want to be familiar with these technologies, which [are supported](http://www.caniuse.com/#feat=fetch) in [every major browser](http://www.caniuse.com/#feat=promises).

### [Web Background Synchronization](https://wicg.github.io/BackgroundSync/spec/)
Web Background Synchronization provides a mechanism to defer actions until a user has a stable internet connection. It's great for allowing users to fill out forms and provide other input while offline.

### [Push API](https://www.w3.org/TR/push-api/) & [Notifications API](https://notifications.spec.whatwg.org/)
These two specifications are used together to re-engage users via push notifications sent to a user's device. The Notifications API has been around for quite awhile, and [is supported by basically every browser except for Safari on iOS](http://www.caniuse.com/#feat=notifications). The Push API is a bit newer, but still has [good support with implementations shipping in Chrome, Firefox and Opera and is coming soon to Edge](http://www.caniuse.com/#feat=push-api).

### *Bonus*: [VAPID](https://tools.ietf.org/html/draft-ietf-webpush-vapid-03) & [RFC8030](https://tools.ietf.org/html/rfc8030)
The **V**oluntary **Ap**plication Server **Id**entification specification and RFC8030 (which covers generic event delivery using HTTP push) are not expected to be specifications web developers know inside and out since they mostly cover details pertinent to browser vendors, but there is some useful information, particularly around how to handle push notification failures.

### [Payment Request API](https://www.w3.org/TR/payment-request/)
[Already available in Edge and Chrome Beta, and behind a flag in Firefox and Opera](http://www.caniuse.com/#feat=payment-request), the Payment Request API makes accepting payment information and handling checkout flows much easier for e-commerce PWA's.

### [Credential Management API](https://www.w3.org/TR/credential-management/)
The Credential Management API exposes and interface to the browser's password manager to that users can easily log in and store their credentials. [The Edge and Firefox teams are considering an implementation, and it has already shipped in Chrome and Opera](http://www.caniuse.com/#feat=credential-management).

---

If you'd like to submit a link for consideration in a future edition of PWA Gazette, [please submit an issue on our GitHub repo](https://github.com/nikmd23/pwa-gazette/issues/new).