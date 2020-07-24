The Offensive Game (forked from Pretend You're Xyzzy)
===================

### About the project

I am not the orinigal author. All credit goes to:

https://github.com/ajanata/PretendYoureXyzzy
https://pretendyoure.xyz/zy/

I am merely expanding upon this project for use on my own servers.

### Getting started / building the project

A Cards Against Humanity clone, server and web client. See WebContent/license.html for full details.

Note: This project is built on TomCat9 and the latest Java JDK 14.
You will need to first configure the build.properties.

You will need to have Tomcat9 and PostreSQL configured.

The project requires Maven to build and can be automated via the included 
'build.bat' file.

For GeoIP functions to work, download http://geolite.maxmind.com/download/geoip/database/GeoLite2-City.mmdb.gz somewhere, unzip it, and update the geoip.db value in build.properties to point to it.

## Third-Party Usage

A Docker package for this project exists at [emcniece/DockerYourXyzzy](https://github.com/emcniece/DockerYourXyzzy):

```sh
docker run -d -p 8080:8080 emcniece/dockeryourxyzzy:dev
```