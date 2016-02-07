# A dev stack I test

This repository is to quickly test the integration of GitLab, GitLab CI, Redmine, Mattermost and Sentry.

I use Mac OS X 10.11.3 with

 - boot2docker 1.8.0
 - docker 1.10.0
 - docker-compose 1.6.0

## How to use this repository

    git clone https://github.com/geelweb/devstack.git
    cd devstack

    docker-compose pull
    docker-compose up

## GitLab

https://about.gitlab.com/

docker image: sameersbn/gitlab

Brose http://192.168.59.103:8000/
default user: root / 5iveL!fe

## Redmine

http://www.redmine.org/

docker image: sameersbn/redmine

Browse http://192.168.59.103:10083/
default user: admin / admin

## Mattermost

http://www.mattermost.org/
https://github.com/mattermost/platform

doker image: geelweb/mattermost

Browse http://192.168.59.103:8065/

## Sentry

https://getsentry.com/welcome/
https://github.com/getsentry/sentry

not yet included
