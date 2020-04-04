# LambStatus

This project is cloned from https://github.com/ks888/LambStatus because that project has gone into maintenance mode, but I want to run some tools (lgtm in particular) that don't work on forks and make some changes.

Documentation below is largely original with the original links.

[![API Document](https://img.shields.io/badge/api-v0-blue.svg)](https://lambstatus.github.io/apidocs/)

LambStatus is the serverless status page system. [See our website](https://lambstatus.github.io/) for features.

## Demo

* [Status page](https://demo-status.lambstatus.org): the page to tell your service's status to your users
* [Admin page](https://demo-admin.lambstatus.org): the page to change your service's status

## Get Started

See [the getting started page](https://lambstatus.github.io/get-started) to build your first status page with just a few clicks!

## Goals of this project

* Offers an open source and serverless status page system.
* Offers a pay-as-you-go pricing approach like AWS. We estimate the system takes just *$1 to handle 30,000 visitors* ([see details](https://lambstatus.github.io/cost-estimate)).
* Enables you to build and maintain the status page system with minimum effort.

## Why Serverless?

Status page system is great with the Serverless architecture, because:

* It eases your pain caused by the scaling / availability issues. It is terrible if your service is down AND heavy traffic from stuck users stops your status page.
* It enables you to pay only for what you use. A status page only occasionally gets huge traffic. The system takes only $1 per 30,000 visitors and almost $0 if no visitors.
