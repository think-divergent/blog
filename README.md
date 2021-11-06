# Think Divergent Blog

This repository powers the blog for Think Divergent

Its contents are hosted on Think Divergent [here](https://thinkdivergent.com/blog).

## Submitting New Articles

Wanna submit an article to or blog? You can fork this repository on GitHub and make a pull request!

## Building the Site Locally

You can make changes to the markdown files holding site content here on GitHub, but if you'd like to see your changes
locally before you submit, you can follow these steps.

1. Install [RVM](https://rvm.io/rvm/basics) first
```
brew install gnupg
curl -sSL https://rvm.io/mpapis.asc | gpg --import -
curl -sSL https://rvm.io/pkuczynski.asc | gpg --import -
curl -sSL https://get.rvm.io | bash
source ~/.rvm/scripts/rvm
rvm list
rvm install 2.5.0
rvm alias create default 2.5.0
rvm use 2.5.0
gem install bundler:2.1.4
bundle install
```
2. Once RVM is installed run `rvm use 2.5.0`
3. In the project directory, run `./run_server.sh`.
4. If you follow the link in jekyll's output(usually http://127.0.0.1:4000/blog), you'll be taken to a local version of the site with your changes

