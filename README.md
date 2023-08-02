# API Test with Cypress

Project based in live realized by Walmir (https://github.com/wlsf82)

Sample project to experiment with [Typeform's API](https://developer.typeform.com/).

## Pre-requirements

It is required to have Node.js and npm installed to run this project.

> I used versions `v16.13.2` and `8.3.2` of Node.js and npm, respectively. I suggest you use the same or later versions.

## Installation

Run `npm install` (or `npm i` for the short version) to install the dev dependencies.

## Tests

> **Note:** Before running the tests, make a copy of the [`cypress.env.json`](./cypress.env.example.json) file as `cypress.env.json`, and update the `TYPEFORM_ACCESS_TOKEN`, `username`, `password`, etc. accordingly.

Run `npm test` (or `npm t` for the short version) to run the test in headless mode.

Or, run `npm run cy:open` to open Cypress in interactive mode.

## Support this project

If you want to support this project, leave a ⭐.

---

This project was created by Rodrigo Abreu.
