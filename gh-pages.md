title: What is Ruby on Rails
author:
  name: "Daniel Kehoe"
  twitter: "rails_apps"
  url: "http://railsapps.github.io/"
output: index.html

--

# What is Ruby on Rails
--

## [railsapps.github.io/rails-composer-talk](http://railsapps.github.io/rails-composer-talk/)
## for this slideshow

--

<img src="http://learn-rails.com/images/learn-rails-book-cover.jpg" height="400px">

--

### If you like the book

* tell your friends
* write a blog post
* add a link to the book

--

### The RailsApps project

* [example applications](https://github.com/RailsApps)
* [Rails Composer](https://github.com/RailsApps/rails-composer/)
* [tutorials](http://railsapps.github.io/)

--

### Support for open source projects

* part-time/weekend side projects <--> babies/burnout
* corporate 20% time <--> budget cuts
* what else works?

--

### $19/month subscription

* example applications - free
* Rails Composer - free
* tutorials - for subscribers only

--

### RailsApps Milestones

* 500 subscribers - July 10, 2014
* apprenticeships - next summer?

--

### Example applications

* starter applications
* reference implementations
* issues and pull requests

--

### Examples for Rails and ...

* Bootstrap or Foundation
* OmniAuth or Devise (authentication)
* Pundit (authorization)
* more to come

--

### Tutorials for Rails and ...

* Bootstrap
* Devise
* Pundit
* RSpec
* more to come

--

### No mystery code!

--

### Rails Composer

```
$ rails new myapp -m
 https://raw.github.com/RailsApps/rails-composer/master/composer.rb

```
rails new myapp -m

https://raw.github.com/RailsApps/rails-composer/master/composer.rb
--
```
option  Build a starter application?
          1)  Build a RailsApps example application
          2)  Contributed applications (none available)
          3)  Custom application (experimental)
      choose  Enter your selection: 1

```

--
```
option  Choose a starter application.
          1)  learn-rails
          2)  rails-bootstrap
          3)  rails-foundation
          4)  rails-mailinglist-signup
          5)  rails-omniauth
          6)  rails-devise
          7)  rails-devise-pundit
          8)  rails-signup-download
      choose  Enter your selection: 7

```

--
```
Get on the mailing list for Rails Composer news?
      option  Enter your email address:

```

--
```
option  Web server for development?
          1)  WEBrick (default)
          2)  Thin
          3)  Unicorn
          4)  Puma
          5)  Phusion Passenger (Apache/Nginx)
          6)  Phusion Passenger (Standalone)
      choose  Enter your selection: 1

```

--
```
option  Web server for production?
          1)  Same as development
          2)  Thin
          3)  Unicorn
          4)  Puma
          5)  Phusion Passenger (Apache/Nginx)
          6)  Phusion Passenger (Standalone)
      choose  Enter your selection: 1

```

--
```
option  Database used in development?
        1)  SQLite
        2)  PostgreSQL
        3)  MySQL
    choose  Enter your selection: 1
```

--
```
option  Template engine?
          1)  ERB
          2)  Haml
          3)  Slim
      choose  Enter your selection: 1
```

--
```
option  Test framework?
          1)  None
          2)  RSpec with Capybara
      choose  Enter your selection: 2
```

--
```
option  Continuous testing?
          1)  None
          2)  Guard
      choose  Enter your selection: 1
```

--
```
option  Front-end framework?
          1)  None
          2)  Bootstrap 3.0
          3)  Bootstrap 2.3
          4)  Zurb Foundation 5.0
          5)  Zurb Foundation 4.0
          6)  Simple CSS
      choose  Enter your selection: 2
```

--
```
option  Add support for sending email?
          1)  None
          2)  Gmail
          3)  SMTP
          4)  SendGrid
          5)  Mandrill
      choose  Enter your selection: 2
```

--
```
option  Devise modules?
          1)  Devise with default modules
          2)  Devise with Confirmable module
          3)  Devise with Confirmable and Invitable modules
      choose  Enter your selection: 1
```

--
```
option  Use a form builder gem?
          1)  None
          2)  SimpleForm
      choose  Enter your selection: 1
```

--
```
option  Install page-view analytics?
          1)  None
          2)  Google Analytics
          3)  Segment.io
      choose  Enter your selection: 1
```

--
```
option  Set a robots.txt file to ban spiders? (y/n) n
```

--
```
option  Create a GitHub repository? (y/n) n
```

--
```
option  Use or create a project-specific rvm gemset? (y/n) y
```

--
```
$ cd myapp
$ rspec
$ rails server
```

--
### Sign in

* user@example.com
* changeme

--
### Forget what you've seen, if ...

* you're a student
* you work on one Rails app

--
### It's for you, if ...

* you frequently build Rails applications
* you build a new Rails application once a year

--
### What is it, really?

* a Rails application template
* a Ruby script using the Thor API
* 2128 lines of code

See the code:
https://raw.github.com/RailsApps/rails-composer/master/composer.rb

--
### Built from recipes

* [rails_apps_composer](https://github.com/RailsApps/rails_apps_composer) gem
* new features? add to the rails_apps_composer gem
* issues? fix in the rails_apps_composer gem

--
### Similar projects

* [Prelang](http://prelang.com/)
* [RailsBricks](http://www.railsbricks.net/)

--
### Advantages

* open source
* more eyes, fewer bugs
* stays current as Rails and gems change

--
### Drawbacks

* difficult to test every option
* some options are neglected
* "build your own" option is a minefield

--
### Roadmap

* more example applications
* more options

--
### Like it?

* Support the project with a subscription

--

<img src="http://learn-rails.com/images/rails-trucker-hat.jpg" height="210px">

--
