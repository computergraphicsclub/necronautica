# Game Project

## Setup

1. Install [NodeJS v.6 & NPM v.3](https://nodejs.org/en/)

   Usually NPM installation comes with NodeJS installation. After installation check your NodeJS version and NPM version by typing `node -v` and `npm -v`

3. Install [SASS](http://sass-lang.com/)

   This is necessary for CSS

4. `git clone` this repository 

5. `cd` into this repository and type `npm install`

6. Type `npm run dev` to start development mode

## Commands

* `npm run dev` to run in development mode

  * Most code changes update automatically

* `npm run prod` to run in production mode

  * For deployment later

## Notes

* Phaser is copied from `node_modules` to `app/assets/phaser/phaser.js` because of incompatible build with Brunch. Therefore Phaser is available as __global__ object for now.

* Please use `spaces` instead of `tabs` and please use `two spaces`.

## Git Workflow

1. Checkout on a branch

2. Code your changes, commit your changes

3. Checkout on development branch, pull the latest development

4. Locally, merge the latest development that you just pulled with your branch that you just worked on. Any conflicts, please resolve here

5. Rebase the merged branch to squash all the commits into one, please make a short concise description on what you worked on

5. Push the branch to origin

## Useful Links

* [Phaser examples](http://phaser.io/examples)

* [Game mechanic examples](http://gamemechanicexplorer.com/)

* [Brick-Breaker Game](https://github.com/christiansakai/brick_breaker)

* [Concentration Game](https://github.com/christiansakai/concentration)
