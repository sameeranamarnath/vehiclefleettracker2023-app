Work in progress:
What does this app do:
It uses a scalable real-time production grade architecture based on react-nextjs, aws api gateway based websockets and lambda functions written in typescript to receive real time location updates of users via social posts like tweets/geodevice updates and shows the same on a map with a dashboard.

The deployment of various parts of the solution are coordinated using terraform IAAC and
docker based image deployment.

This repository houses the frontend of the tracking app
, i am also working on an interface which can be used to share blog posts

Usecases:

1. Delivery fleet tracking based on mandatory checkins made enjoyable using social media checkins.
2. Hosting contests based on geo campaigns/mass messaging campaigns.

frontend of the real-time vehicle tracking application

Uses nextjs14 ( which runs only with node>18.17,not necessarily a restriction however) , styledcomponents usage is limited,

the api and websocket are hosted via api gateway

      -Amar.S
