<mkdocs>
mkdocs build --clean
mkdocs gh-deploy --clean
mkdocs serve -a 127.0.0.1:7999


<new one>
go to gh
new repository
important: select the option to add a readme to get a template for the theme
settings>gh pages> select the master banch
change theme

<edit locally>
git clone
enter that dir
ls > check if there is no gemfile
If you don't have a Gemfile

add
source 'https://rubygems.org'
gem 'github-pages', group: :jekyll_plugins
to Gemfile

add in _config.yml
exclude: [vendor, additional]


bundle install --path vendor/bundle

bundle update

bundle exec jekyll serve
gave me a warning which can be ignored

GitHub Metadata: No GitHub API authentication could be found. Some fields may be missing or have incorrect data. 

got a blank page first -> make a small change to a file, then it appeared


<theme adaption>
https://jekyllrb.com/docs/themes/#overriding-theme-defaults
To locate a themes' files...
