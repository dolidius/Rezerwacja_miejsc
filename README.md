# Reservation system

![demo](https://i.imgur.com/DCGD8XH.png)

## Installation

App requires [Node.js](https://nodejs.org/) to run app locally.

Download the repo by downloading zip or cloning the repo:

```sh
$ git clone git@github.com:dolidius/Reservation_system.git
```

Install the dependencies and start the server and api.

To start react app:
```sh
$ cd Reservation_system
$ npm install
$ npm start
```

To start API:
```sh
$ cd Reservation_system
$ cd api
$ npm install
$ npm run api
```

## Description

App is written using React, Redux, Typescript and design system called Material-UI. 

### Choosing default seats

-Next to each other:

1) Calculate maximum intervals without break in each row

2) Sort them by intervals length

3) Pick the highest interval and if its smaller than needed, then fill those seats as default and repeat until we fill user choosed tickets amount.

-Otherwise:

Just pick first x seats where x is inputed by user.
