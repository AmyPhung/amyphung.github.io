# Notes
+ General local setup:
  + Follow the instructions here to install rvm https://github.com/rvm/ubuntu_rvm
  + To set this up, install ruby 2.6.3 with `rvm install 2.6.3`
  + Install bundler `gem install bundler`
  + Navigate to this directory and run `bundle install`
  + In the future, use `rvm use 2.6.3` to re-activate this environment

+ To test locally, navigate to this directory and run `bundle exec jekyll serve`
+ To update the `Gemfile.lock` file (to fix old dependency issues)
  + Delete the old `Gemfile.lock`
  + Navigate to this directory and run `bundle install`
  + There should be a new `Gemfile.lock` with the updated dependencies

# Documentation
+ Multiple Paginate example ([reference](https://github.com/scandio/jekyll-paginate-multiple-example
))
+ Deploying a jekyll blog with plugins around GitHub whitelist ([reference](http://joshfrankel.me/blog/deploying-a-jekyll-blog-to-github-pages-with-custom-plugins-and-travisci/))
+ To update site, push to source branch (Travis will update repo)
+ To update dependency list, remove Gemfile.lock and run `bundle install` within this directory

# Troubleshooting
+ If you get errors with an invalid token, double-check that TravisCI has an environment variable GITHUB_TOKEN with a properly set personal access token

# Features to be added
+ Image zooming/gallery
+ More dynamic homepage
+ Comments section
+ Fix display image
+ Last updated date in footer
