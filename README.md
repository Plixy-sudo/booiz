
<h1 align="center">wingflex demo</h1>

The demo implementation of <a href="https://github.com/MercuryWorkshop/scramjet">Scramjet</a>, the most advanced.

<a href="https://github.com/MercuryWorkshop/scramjet">Scramjet</a> is an experimental interception based web proxy designed with security, developer friendliness, and performance in mind. This project is made to evade internet censorship and bypass arbitrary web browser restrictions.

#### Refer to <a href="https://github.com/HeyPuter/browser.js">browser.js</a> where this project will now receive updates outside of just bypassing internet censorship.

## Setup / Usage
```

Install dependencies


```pnpm install

Run the server

```
pnpm start
```

Resources for self-hosting:

- https://github.com/nvm-sh/nvm
- https://docs.titaniumnetwork.org/guides/nginx/
- https://docs.titaniumnetwork.org/guides/vps-hosting/
- https://docs.titaniumnetwork.org/guides/dns-setup/

### HTTP Transport

The example uses [libcurl-transport](https://github.com/MercuryWorkshop/libcurl-transport) to fetch proxied data encrypted.

You may also want to use [epoxy-transport](https://github.com/MercuryWorkshop/epoxy-transport), a different way of fetching encrypted data.

This example also now uses [wisp-js/server](https://www.npmjs.com/package/@mercuryworkshop/wisp-js) instead of the now outdated wisp-server-node. Please note that this can also be replaced with other wisp implementations like [wisp-server-python](https://github.com/MercuryWorkshop/wisp-server-python) which is highly recommended for production.

See the [bare-mux](https://github.com/MercuryWorkshop/bare-mux) documentation for more information.
