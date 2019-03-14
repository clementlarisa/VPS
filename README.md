# VPS - Vodafone Proximity Store

![directions](https://raw.githubusercontent.com/clementlarisa/VPS/master/directions%20map.jpg)

<i>(Directions map)</i>


<b>We cut the slack for users who are looking for the fastest way to a hands-on experience with their preferred products (app developed during Vodafone sponsored hackathon - won 4th place).</b>

  My team members and I met at the hackathon for the first time and we decided to form a team in order to tackle the challenge posted by Vodafone. 
  We used JavaScript and a web extension built by one of our experienced team members to inject new web content on top of the existing Vodafone online store content. 
  We used less to design the new pages where the customers were directed (using the Maps JavaScript API) to the nearest Vodafone store. (We used the store locations and products database that Vodafone gave us).
  Even though we all came from different backgrounds, through brainstorming and peer programming, we managed to merge our skills and successfully finished our app which got us 4th place among teams that had been formed long before ours.

## Inspiration
The main drive behind our app is to extend the functionality of the existing Vodafone online store.

## What it does
Our extension gets customers to the nearest offline store for product testing.

## How we built it
We use an existing Chrome extension built by one of our members (Robert Vilcu) to inject new web content on top of the existing Vodafone online website. Our app makes use of a sample database of retail stores and product availability and the Google Maps API in order to determine the fastest route to an offline testing point.

## Challenges we ran into
Integration on top of an existing website, the implementation details of which were previously unknown to us, as well as conflicts between pre-existing usage of the Google Maps API and our own implementation.

## Accomplishments that we're proud of
The fact that our team has managed to build a third-party extension that behaves like a native, first-party implementation of the challenge.

## What we learned
Through brainstorming and peer programming, we have managed to merge our skills and apply the result to a concrete implementation.

## How to build
* the app uses ABdev, therefore it requires that steps be followed as listed [here](https://github.com/vilcuRob/ABdev)
* after creating an experiment, the files from this repository should be attached to it under the js & less directory structure

## What we used
* javascript
* jquery
* chrome
* google-maps
* [abdev](https://github.com/vilcuRob/ABdev)
