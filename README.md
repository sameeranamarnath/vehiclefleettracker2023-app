What does this app do:
It uses react-nextjs, aws api gateway based websockets and lambda functions to receive real time location updates of users via social posts like tweets and updates the same on a map with a dashboard

This repository houses the frontend of the tracking app
, i am also working on an interface which can be used to share blog posts
Usecases:

1. Delivery fleet tracking based on mandatory checkins made enjoyable using social media checkins

frontend of the real-time vehicle tracking application

Uses nextjs14 ( which runs only with node>18.17,not necessarily a restriction however) , styledcomponents,

github actions workflows build various aspects of the application and sends it to aws ecr=> which is
then used for hosting the frontend
(this can also be done via cloudfront)

the api and websocket are hosted via api gateway lambdas

      -Amar.S
