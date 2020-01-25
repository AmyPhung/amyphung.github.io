# Notes
+ To test locally, open Git Bash and run `bundle exec jekyll serve`

# Documentation
+ Multiple Paginate example ([reference](https://github.com/scandio/jekyll-paginate-multiple-example
))
+ Deploying a jekyll blog with plugins around GitHub whitelist ([reference](http://joshfrankel.me/blog/deploying-a-jekyll-blog-to-github-pages-with-custom-plugins-and-travisci/))
+ To update site, push to source branch (Travis will update repo)
+ To update dependency list, remove Gemfile.lock and run `bundle install` within this directory

# Troubleshooting
+ If you get errors with an invalid token, double-check that TravisCI has an environment variable GITHUB_TOKEN with a properly set personal access token
