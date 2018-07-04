# Official website for tinydog, llc.

There isn't much to see here yet. We plan to use [VuePress](https://vuepress.vuejs.org/) to build it out.

## Dependencies

* [Node.js](https://nodejs.org/)

**Setup**

Open the project in a terminal and enter ```npm install```

## Run Project - Dev

To run the project in dev mode, open it from a terminal and enter ```npm run site:dev```.

Once running you can visit the site by going to [http://localhost:8081/](http://localhost:8081/).

## Production Build

To create a production build, open the project from a terminal and enter ```npm run site:build```.

Once the script has completed, you'll find the static site in the ```./site/.vuepress/dist``` directory.

## Add a Page

To add a page, create a markdown file somewhere within the site directory.

Example: ```./site/services/README.md``` creates [http://localhost:8081/services/](http://localhost:8081/services/).
