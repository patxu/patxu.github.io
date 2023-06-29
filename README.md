# patrickxu.com
Personal website made with [Jekyll](https://jekyllrb.com/).

## Setup
This site runs on Jekyll, an opensource static site generating platform.

- Clone or download a zip of this project to your computer and navigate to the
  project directory in your terminal
  
- Make sure Ruby is installed, to check if it is, run:
  ```
  ruby -v
  ``` 
  For more information about installing Ruby, refer to the [Ruby installation ](https://www.ruby-lang.org/en/documentation/installation/).

- Install the Jekyll and bundler [gems](https://jekyllrb.com/docs/ruby-101/#gems) from the commandline:
  ```
  gem install jekyll bundler
  ```
  For more information about installing Jekyll, refer to the [Jekyll quickstart guide](https://jekyllrb.com/docs/quickstart/)


- Install Gem dependencies for the project by running:
  ```
  bundle install
  ```
  
- To run the server in your local environment run:
  ```
  bundle exec jekyll serve
  ```
  
- Go to http://localhost:4000/ in your browser

## TODOs
A few things up next:
- [ ] a simpler design that doesn't deal with posts at all - Jekyll is probably overkill
- [ ] including some other links like Github, Contact page
- [ ] perf improvements on load time from https://pagespeed.web.dev/

## Theme
This website is based of the [Minimal Mistakes](https://github.com/mmistakes/minimal-mistakes) Jekyll theme.

## Assets
- "PX" logo designed on [Canva](https://www.canva.com/create/logos/)
- Photos taken by me

## Inspiration websites
* https://himatt.com/
* https://rehanbutt.com/
* https://github.com/alshedivat/al-folio
* https://github.com/poole/hyde
* Resume-style themes
  * https://jekyllthemes.io/theme/online-cv
  * https://jekyllthemes.io/theme/resume-template
