# React - Ecommerce Progressive Web Apps

[![CircleCI](https://circleci.com/gh/cezerin/cezerin/tree/master.svg?style=svg)](https://circleci.com/gh/cezerin/cezerin/tree/master)

this is React and Node.js based eCommerce platform. Allows creating a Progressive Web Apps.

Built with:
* Node.js v8.9
* React v16
* Redux
* Express
* Babel
* WebPack 4
* MongoDB

## Dashboard
Client-side dashboard use JSON Web Token (JWT) to access REST API.

![React-Ecommerce Dashboard](https://cezerin.com/assets/images/cezerin-dashboard-products.png?)

![Signin email](https://cezerin.com/assets/images/cezerin-signin-email.png)

## Store
Single-Page Application with React server-side rendering.

[![Cezerin Store](https://cezerin.com/assets/images/cezerin-mobile-product.png)]

[![Cezerin Store](https://cezerin.com/assets/images/cezerin-mobile-order-summary.png)]

## Installation

- [with GitHub](https://github.com/webdevstar/React-Ecommerce/blob/master/docs/getting-started.md)
- [with Docker](https://github.com/webdevstar/React-Ecommerce/blob/master/docs/getting-started-docker.md)
- [How to deploy a Cezerin on Ubuntu 16.04](https://github.com/webdevstar/React-Ecommerce/blob/master/docs/how-to-deploy-a-cezerin-on-ubuntu-16-04.md)
- [How to deploy a Cezerin on Ubuntu 18.04.1 (from GitHub)](https://github.com/webdevstar/React-Ecommerce/blob/master/docs/how-to-deploy-a-cezerin-on-ubuntu-18-04-1-github.md)

### Requirements
* Node.js >= 8
* MongoDB >= 3.2


## Documentation

[Documentation](https://github.com/webdevstar/React-Ecommerce/tree/master/docs)


## Application Structure

```
.
├── config                   # Project and build configurations
├── dist                     # Distribution folder
├── locales                  # Text files
├── logs                     # Log files
├── public                   # Static public assets and uploads
│   ├── admin                # Dashboard index.html
│   ├── admin-assets         # Dashboard assets
│   └── content              # Store root folder
|
├── scripts                  # Shell scripts for theme install/export
├── src                      # Application source code
│   ├── admin                # Dashboard application
│   │   └── client           # Client side code
│   ├── api                  # REST API
│   │   └── server           # Server side code
│   ├── store                # Store application
│   |   ├── client             # Client side code
│   |   ├── server             # Server side code
│   |   └── shared             # Universal code
│   └── index.js             # Server application start point
├── theme                    # Theme as a local package
└── process.json             # pm2 process file
```
