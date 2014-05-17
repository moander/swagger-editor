# Project Phonics

Coming soon!


## [View App](http://apigee.github.io/phonics/)

[Click Here](http://apigee.github.io/phonics/)

## Running Locally

* Make sure you have These dependencies installed
 * NodeJS
 * Ruby
 * Compass
* Clone the repository
* `npm install`
* `bower install`
* `npm run fix-coffee`
* `grunt serve`



## Building

Just run 

```
$ grunt build
```


## Pushing to `gh-page`

Just run 

```
$ grunt ship
```
Please do not touch `gh-pages` branch manually

### Problem with CoffeeScript Grunt Module

Run this npm command to fix it: 


```
$ npm run fix-coffee
```

We need to update grunt-contrib-coffee's coffee-script version to `1.6.0` and run `npm install` it if you see coffee-script errors.