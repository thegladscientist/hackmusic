# hackmusic

# Chill or Go: Real-time Analytics for Ridesharing at A3C Festival and Conference 2016.

![alt tag](https://github.com/thegladscientist/hackmusic/blob/master/assets/css/images/a3c-landingpage.jpeg)

http://a3c.thegladscientist.info/

We integrated the MapQuest API to gather real-time data of traffic around the various venues of the festival in a web-based mobile app. This happened in two-fold:

-Firstly it displays the most recent (within a few ms) images for traffic surrounding the venues. We thought this would be a more efficient way to get a quick look at the traffic patterns, as opposed to opening a maps application and waiting for all of the services to load.

-Then, we evaluated the data for the instances of events, congestion/flow, and accident/incidents. We ignored construction, as we discovered it resulted in false positives. The key metric we focused on was the *impacting* variable, as it measures how much the traffic flow will impact travel in the area of focus.

To make the app quick and easy for users, we decided to use a color-coded interface, where a green background behind the venue name means the user is good to go to hail an Uber. We have integrated with the Uber API as well to allow for deep-linking directly from the GPS coordinates of the venue as the starting point of their trip upon tapping "Go". A blue background behind the venue name means the user should take advantage of the moment and chill until the traffic dies down and any surge or plus pricing ends.

Our goal is to improve the efficiency for festival/conference goers to move between venues and enjoy their interests full, by providing them with a quick-glance view of when to chill and when to go, so they have the most fulfilled experience possible.


Notes: Image on Github from Unsplash.com // HTML & CSS base template from HTML5 UP.net
