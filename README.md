# Amblr
When you’re walking around the city, you want to enjoy the fun and interesting things and avoid the dangerous / gross stuff. Amblr lets you share points of interest with other users and lets you see what other have added. It’s kind of like Waze, but for walkers.

## Team

  - __Product Owner__: Toben
  - __Scrum Master__: Alex
  - __Development Team Members__: Trini, Bryan

## Table of Contents

1. [Usage](#Usage)
1. [Requirements](#requirements)
1. [Development](#development)
    1. [Installing Dependencies](#installing-dependencies)
    1. [Tasks](#tasks)
1. [Team](#team)
1. [Contributing](#contributing)

## Usage

When you load the app, you'll see a Google Map where you can add a point of interest (POI) at your current location by clicking a menu link or at any location by touching and holding on the map for 1 second. After adding a POI, you can add details and save it to the database. Touch existing POIs to see the details.

Sign In and Sign Out features are implemented with Passport.js, but they do not restrict user functions yet.

## Requirements

### Stack
- MongoDB 2.1.16
- Express 4.13.4
- Angular 1.4.3 with Ionic 1.2.4
- Node 4.4.2
- Google Maps API

### NPM Modules and Bower Components

For complete details, see package.json files in Server and Client folders, and bower.json in Client folder.

### What's Ionic?

In case you're curious about the mobile technologies:


Ionic - A mobile development framework for Angular.js - see the [official site] (http://ionicframework.com/) and [this blog post] (http://blog.ionic.io/where-does-the-ionic-framework-fit-in/)


Cordova - Cordova wraps your HTML/JavaScript app into a native container which can access the device functions of several platforms (phones, tablets, browsers) -  See [http://cordova.apache.org/] (http://cordova.apache.org/)


## Development

### File Structure

See the [file structure] (https://github.com/mediocreokra/amblr/blob/master/_FILE-STRUCTURE.MD) for a guide to what's included.

### Logging

Server logging will be done both in the console and to /server/logs/log.log.
Log level can be configured in /server/config/logger.js

### Installing Dependencies

From within the ```client``` directory:

```sh
npm install
bower install
```

From within the ```server``` directory:

```sh
npm install
grunt server-dev
```

### Roadmap

View the current issues list [here](https://github.com/mediocreokra/amblr/issues)


## Contributing

See [CONTRIBUTING.md](https://github.com/mediocreokra/amblr/blob/master/_CONTRIBUTING.md) for contribution guidelines.
