<!-- note marker start -->
NOTE: This repo contains only the documentation for the private BoltsOps repo code.
Original file: https://github.com/boltops-learn/docker-bin-loop/blob/master/README.md
The docs are publish so they are available for interested subscribers.
For access to the source code, you can become a BoltOps subscriber.
See: https://learn.boltops.com

<!-- note marker end -->

# Docker Favorite Debugging Tip: loop.sh

[![BoltOps Badge](https://img.boltops.com/boltops/badges/boltops-badge.png)](https://www.boltops.com)

This tutorial shows you one of my favorite debugging tips when working with Docker.

TLDR: Essentially, create a loop.sh script with a simple loop just so you can keep the container running so you can exec in an debug.
## Build

    docker build -t demo/app .

## Run

    docker run demo/app

## Push

    docker push demo/app

## Notes

Replace boltops with your own DockerHub username if you are going through the tutorial.

## Video

[![Watch the video](https://uploads-learn.boltops.com/qe45gfzfgbc8vz7fg6en702p35km)](https://learn.boltops.com/courses/docker/lessons/docker-favorite-debugging-tip-loop-sh)

Note: Premium video content requires a subscription.
