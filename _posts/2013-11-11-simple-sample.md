---
layout: post
title:  "Building Simple Sample with Meteor."
date:   2013-11-11 12:00:00
categories: projects
summary: "An overview of my experience building a geolocation based app using the Meteor Framework. My progress and possibilities in the road ahead."
image: "/img/simplesample.png"
---

###As of today:###

Simple Sample [simplesample.meteor.com][simplesample] is a demo app where users can signup, create projects, and collect points, lines, and polygons per project. I built this application as a open alternative to enterprise solutions with the flexibility of using a samrt phone or tablet in comparison to a GPS device.  The application is built on the [Meteor Framework][meteor] with layout and mapping help form [Bootstrap][getbootstrap] and [Leaflet][leaflet] respectively. When choosing a framework, I was looking for something Javascript/Node based with a quick user authentication, real-time capabilities, and an established user community. Meteor fit the description plus provides services to deploy demo applications quickly and for free.  The reactive database functionality of Meteor's Mongodb allows for real-time updating of the map as shapes are created and destroyed. The major pitfall of using Meteor is its current scalability issues replicating the Mongodb across servers, but for the Meteor 1.0 release in early 2014, this scalability issue is slated to be solved.

<br />

###For the Future:###

For the future, I would like to incorporate three additional features: drawing geometry onto the map, shareing/collaborating on projects, and downloading collected data.

###Tools/Resources:###
- Check out the source code for Simple Sample [https://github.com/apburnes/simple-sample][simplesource]
- [Meteor JS][meteor]
- [Leaflet JS][leaflet]
- [Bootstrap][getbootstrap]



[simplesample]: http://simplesample.meteor.com
[simplesource]: https://github.com/apburnes/simple-sample
[meteor]: http://meteor.com
[leaflet]: http://leafletjs.com/
[getbootstrap]: http://getbootstrap.com/