Google Universal Analytics adapter for AngularJS
================================================

`angular-ga` is a very straightforward AngularJS adapter of the **new** (google analytics script)[https://developers.google.com/analytics/devguides/collection/analyticsjs/]. 

It gives you full control of your analytics, exposing the google's `ga()` function for you.
What it means is, that it will set the page field on every route change for You, but you will have to send the pageviews, events etc. manually. But on the other hand, you have the full control of that process.

Usage
=====

## Embed tracking code

Include the **new** universal analytics script in your html as usual, but remove `ga('send', 'pageview');`

## Enable the ga module
```js
angular.module('yourModule', ['ga'])
```

