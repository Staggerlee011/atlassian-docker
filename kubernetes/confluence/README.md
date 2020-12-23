# Confluence deployment of kubernetes

There are several helm charts to deploy confluence, but i had issues getting each to work. this is a simple deloyment of confluence with the following config:

- A single pod `confluence` deployment
- Offloaded `HTTPS` to a custom URL using a loadbalancer
- `EFS` storage to allow for HA

## deployment

[Read my blog post on deployment](https://blog.serialexperiments.co.uk/posts/confluence-on-kubenetes/)