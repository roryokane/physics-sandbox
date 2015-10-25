# Physics Sandbox

This repo contains simple physics simulations. Its website is http://www.physicsandbox.com/.

### How to develop this locally

To view the site, serve the root directory on localhost using a tool such as `python -m SimpleHTTPServer` or [http-server](https://github.com/indexzero/http-server).

To compile the Haml and Sass files, you need Ruby and [Bundler](http://bundler.io/). First, `bundle install` the dependencies. Then you can run `bundle exec guard` to automatically recompile when changes are detected.

The files in `assets/javascripts/` and `assets/images/` can be edited directly. They are not compiled from anything.
