# Frontend Assignment

**Thank you for taking the time to work on our Frontend assignment!** This document will explain the assignment and tell you more about the tech stack and requirements. Try to spend at most 6 hours on it and don't worry if you can't complete the assignment within that time. What matters most is not if you fully complete the assignment, but the decisions you make along the way and why. That is what we will be mostly interested in.

Think upfront about what you think is important, so you can focus on that.

## Context

Within Cryptohopper we have multiple tech stacks. The backend is mainly PHP and Go, while the frontend is mostly React (sometimes in combination with NextJS). As a Frontender at Cryptohopper you will be working with NextJS when server side rendering is required and sometimes React when server side rendering is not required. On the platform, the tech stack is mainly PHP, HTML, CSS and vanilla JavaScript.

## For this assignment

We've set up a new (pristine) [NextJS](https://nextjs.org/) + [TypeScript](https://nextjs.org/docs/basic-features/typescript) project with `create-next-app`.

### What we would like you to build

Using NextJS, build a page that lists crypto currencies like [this one](https://www.cryptohopper.com/website-widgets?widget=marketcap) (see [screenshot](./public//screenshot.png)). You can use this public [coingecko API](https://api.coingecko.com/api/v3/coins/markets?vs_currency=usd&order=market_cap_desc&per_page=100&page=1&sparkline=false) and the accompanying [documentation](https://www.coingecko.com/en/api/documentation) (check documentation for the `/coins/markets` endpoint).

_Feel free to style it differently than the example screenshot and add your own creativity._

### Requirements

- The page should be SEO friendly eg. server side rendered
- It should list the `icon`, `name`, `ticker`, `price`, `marketcap` and `24h volume` per coin
- It should be sortable on every column, except for the icon
- It should have pagination (50 item batch) that does not require to reload the page

**Extra** (optional)

- Add a unit test if there is a unit you can test
- Add an end to end test with cypress

**Workflow**

- Clone or Fork this git repository with your preferred software development platform
- Commit your changes frequently
- Once you're done, send us a link to your repository

### Tech stack

- React
- TypeScript
- NextJS
- Jest (optional)
- Cypress (optional)

**Good luck!** 🍀
