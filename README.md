# Phaser 3 Boilerplate
A starting point for Phaser 3 projects. Multi-scene with preloading and click/keypress to start title screen.

Based on [this](https://github.com/nkholski/phaser3-es6-webpack) and [this](https://github.com/simiancraft/create-phaser-app) repos which also include more complete game examples.

# Setup
To get running

## 1. Clone this repo:

Navigate into your workspace directory.

Run:

```git clone git@github.com:DannyT/phaser3-boilerplate.git```

## 2. Install node.js and npm:

https://nodejs.org/en/


## 3. Install dependencies (optionally you could install [yarn](https://yarnpkg.com/)):

Navigate to the cloned repo’s directory.

Run:

```npm install```

or if you choose yarn, just run ```yarn```

## 4. Run the development server:

Run:

```npm run start```

This will run a server so you can run the game in a browser.

Open your browser and enter [localhost:3000](http://localhost:3000) into the address bar.

Also this will start a watch process, so you can change the source and the process will recompile and refresh the browser.


## Build for deployment:

Run:

```npm run build```

This will optimize and minimize the compiled bundle.
