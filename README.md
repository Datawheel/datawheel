datawheel
=========

## Installation
- Make sure [Ruby](https://www.ruby-lang.org/en/documentation/installation/) is installed
- Install Bundler (`gem install bundler`, or `sudo gem install bundler`)
- Clone this repo
- Install dependencies; from the local repo directory, run `bundle install`
- Once finished, run `bundle exec jekyll serve --watch` and get devin'!

## Notes
- If you push any changes, the site will recompile on the live server automatically
- Don't touch the `_site` folder — that's a build folder
- In html files:
  - Define front matter up top (yaml syntax)
  - Use `{{ }}` for liquid objects (i.e., `{{ page.title }}`)
  - Use `{% %}` for liquid tags (i.e., `{% if user %} Hello {{ user.name }}! {% endif %}`)
- @davelandry has given @perpetualgrimace full creative control over the aesthetics of this website 😼
