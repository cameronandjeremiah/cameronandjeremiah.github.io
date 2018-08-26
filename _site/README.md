# cameronandjeremiah.github.io

This repository is the home of our wedding website.

---

### Attribution:

This page is based on a [Jekyll, Foundation 6 starter](https://github.com/daigofuji/jekyll-foundation-6-starter) created by [@diagofuji](https://twitter.com/DaigoFuji). You can see a [working example site here](http://daigofuji.github.io/jekyll-foundation-6-starter/).

---

## To run:

Run this once:
  `npm install` and `bundle install`

Make sure you don't get errors. (See below if you get errors.)

Then 
  `npm start`
which will compile css from sass and watch scss file changes. (`control-c` to quit)

Open another terminal window and run:

`bundle exec jekyll serve --watch`

This will compile the web site.

dev site will appear on http://0.0.0.0:4000/

### Trouble shooting and useful commands

**If you don't have node.js:**
Install [node.js](https://nodejs.org/en/). Easiest way it to use [Homebrew](http://brew.sh/) by

  `ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"`

then

  `brew install node`

**Gulp or Bower problem?**
Try installing gulp globally by running 

  `npm install gulp -g`

** gulp issues **

Run gulp to compile css from sass by simply run `gulp` or `npm start` from your terminal within your repo. 
It will launch watch by default. <code>control-c</code> to stop. 

**If you only want the css compiled once:** 
run `gulp sass`

**Jeckyll issues**
To run jekyll locally to test your website while developing, run `bundle install` then `bundle exec jekyll serve --watch` (Requires ruby *) Your website should be viewable by going to [localhost:4000](http://localhost:4000/)
Github's doc on [how to use Jekyll on Github Pages](https://help.github.com/articles/using-jekyll-with-pages) is also helpful. 

**Ruby bundle install issue:**
You may have to run `brew install ruby` and `sudo gem install bundler`. [Mac OS X 10.11 nokogiri trouble](http://stackoverflow.com/questions/23668684/failed-to-build-gem-native-extension-when-i-run-bundle-install)

**Foundtion Update**
You can update to the latest foundation by running `bower update foundation-sites --save`. Ping me and I will update this repo. Any questions, make an issue or ask on twitter @DaigoFuji