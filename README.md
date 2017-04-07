# Awesome Hanami [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
A collection of awesome ruby gems and projects for hanami development.

The goal is to help every hanami developer to build an awesome product/service.

* [Hanami Gem List](#hanami-gem-list)
  * [Assets](#assets)
  * [Authentication and OAuth](#authentication-and-oauth)
  * [File Uploading](#file-uploading)
  * [Performance Monitoring](#performance-monitoring)
  * [Testing](#testing)
  * [Database](#database)
  * [CLI](#cli)
  * [Building APIs](#building-apis)
  * [Deploy](#deploy)
  * [Editors and IDE](#editors-and-ide)
* [Vanilla Libraries and Hanami](#vanilla-libraries-and-hanami)
* [Hanami Project List](#hanami-project-list)
* [Useful Links](#useful-links)
  * [Blog Posts](#blog-posts)
  * [Benchmarks](#benchmarks)
  * [User Groups](#user-groups)

## Hanami Gem List
### Assets
* [hanami-bootstrap](https://github.com/davydovanton/hanami-bootstrap) - Bootstrap wrapper for hanami framework.
* [jquery-hanami](https://rubygems.org/gems/jquery-hanami) - This gem provides jQuery and the jQuery-ujs driver for your Hanami application.
* [hanami-webpack](https://github.com/samuelsimoes/hanami-webpack) - A RubyGem to allow you to use the Webpack as your asset pipeline in Hanami.

### Authentication and OAuth
* [hanami-rodauth](https://github.com/davydovanton/hanami-rodauth) - Rodauth wrapper for hanami apps
* [hanami-fumikiri](https://github.com/theCrab/hanami-fumikiri) - JWT authentication wrapper for hanami apps
* [tachiban](https://github.com/sebastjan-hribar/tachiban) - Authentication with bcrypt for Hanami apps

### File Uploading
* [hanami-shrine](https://github.com/katafrakt/hanami-shrine) - Upload solution for Hanami using Shrine library

### Performance Monitoring
* [newrelic-hanami](https://github.com/artemeff/newrelic-hanami) - Gem for connecting NewRelic and Hanami

### Testing
* [rspec-hanami](https://github.com/davydovanton/rspec-hanami) - RSpec Matchers for Hanami
* [shoulda-hanami](https://github.com/mcorp/shoulda-hanami) - Making tests easy on the fingers and eyes, but on hanami (old shoulda-lotus)
* [hanami-fabrication](https://github.com/jodosha/hanami-fabrication) - Utility to easily integrate [Fabrication](https://www.fabricationgem.org/) gem and Hanami

### Database
* [hanami-rethinkdb](https://github.com/angeloashmore/hanami-rethinkdb) - **works only with hanami < 0.9**RethinkDB adapter for Hanami::Model
* [rom_sql_graph](https://github.com/davydovanton/rom_sql_graph) - DB (sql) association graph for hanami and rom projects

### CLI
* [hanami-scaffold](https://github.com/davydovanton/hanami-scaffold) - Make hanami scaffolds faster.

### Building APIs
* [jsonapi-hanami](http://jsonapi-rb.org) - Efficiently and conveniently build [JSON API](http://jsonapi.org)-compliant APIs with Hanami.
* [hanami-jbuilder](https://github.com/vladfaust/hanami-jbuilder) - Support for rendering JBuilder templates for Hanami apps

### Deploy
* [mina-hanami](https://github.com/mgrachev/mina-hanami) - [Mina](https://github.com/mina-deploy/mina) plugin for Hanami.
* [capistrano-hanami](https://github.com/mgrachev/capistrano-hanami) - Hanami tasks for [Capistrano](https://github.com/capistrano/capistrano).

### Editors and IDE
* [How to run Hanami in RubyMine](https://medium.com/@tetyanachupryna/how-to-run-hanami-in-rubymine-dff342cb0114#.7jb2bjq9f)
* [projectile-hanami](https://github.com/avdgaag/projectile-hanami) - Projectile Hanami is an Emacs minor mode, based on Projectile, for navigating Hanami projects.

## Vanilla Libraries and Hanami
* [omniauth](https://github.com/intridea/omniauth) - [Hanami with OAuth](http://codetunes.com/2016/hanami-with-oauth/)
* [Sidekiq](http://sidekiq.org) - [From Rails to Hanami Part 3](http://rpanachi.com/2016/04/25/from-rails-to-hanami-part3-sidekiq-workers-i18n-timezone-issues-core-ext), [Use Sidekiq With Hanami](http://www.strauss.io/blog/2016-use-sidekiq-with-hanami.html)
* [I18n](https://github.com/svenfuchs/i18n) - [From Rails to Hanami Part 3](http://rpanachi.com/2016/04/25/from-rails-to-hanami-part3-sidekiq-workers-i18n-timezone-issues-core-ext)
* [Sequel plugins](http://sequel.jeremyevans.net/plugins.html) - [From Rails to Hanami Part 3](http://rpanachi.com/2016/04/25/from-rails-to-hanami-part3-sidekiq-workers-i18n-timezone-issues-core-ext)
* [letter_opener](https://github.com/ryanb/letter_opener) - [Preview hanami emails in browser](http://blog.davydovanton.com/2016/05/21/preview-hanami-emails-in-browser/)
* [mongoid](https://github.com/mongodb/mongoid) - [github](https://github.com/michalvalasek/hanami-mongoid)
* [Trailblazer](https://github.com/apotonick/trailblazer) - [Hanami with Trailblazer](https://github.com/apotonick/gemgem-hanami)
* [Factory Girl](https://github.com/thoughtbot/factory_girl) - [Hanami with Factory Girl](https://gist.github.com/rafaels88/8437edababcf38ee193b2ba0265e78b9)

## Hanami Project List
* [scripta.io](http://www.scripta.io/home) - A platform for creating and sharing documents on the web ([Sources](https://github.com/jxxcarlson/noteshare)).
* [firefly](https://github.com/ariejan/firefly) - Firefly is an elegant solution for personal media hosting and URL shortening.
* [repressed_museum](https://github.com/vasspilka/repressed_museum) - A simple mostly static website, features basic i18n and docker integration
* [bookshelf-delivery-example](https://github.com/bruz/bookshelf-delivery-example) - An example app with a web GUI, API and CLI using shared interactors.
* [pinfluence](https://github.com/prosi-org/pinfluence) - All world influencers in a map
* [OSSBoard](http://www.ossboard.org) - Simple way to connect developers and oss maintainers ([Sources](https://github.com/davydovanton/ossboard)).
* [hanami-jwt-example](https://github.com/nickgnd/hanami-jwt-example) - A simple JSON API web application built with Hanami which provides jwt-authentication, password encryption and CORS support.
* [app.dartboard.io](http://app.dartboard.io) - Online darts scorer app built with Hanami([Sources](https://github.com/stravid/datsu-api))
* [distruct-me](https://github.com/MorozovaLiuda/distruct-me) - App on Hanami for self-distructing messages
* [contributors.hanamirb.org](http://contributors.hanamirb.org) - All hanami contributors in one place

## Useful Links
* [StackOverflow questions](http://stackoverflow.com/questions/tagged/hanami)
* [reddit.com/r/hanamirb](https://www.reddit.com/r/hanamirb/)
* [Discourse](https://discourse.hanamirb.org/)

### Blog Posts
* [What I learned building an app in Hanami](https://rossta.net/blog/what-i-learned-about-hanami.html)
* [Livereload and Hanami](https://defman.me/blog/hanami-love-livereload/)
* [Deploying Hanami web application with Puma, Nginx and PostgreSQL using Docker](http://codrspace.com/sebastjan-hribar/deploying-hanami-web-application-with-puma-nginx-postgresql/)
* [Getting Started with Hanami and GraphQL](https://blog.simplificator.com/2016/12/07/getting-started-with-hanami-and-graphql/)
* [From Rails to Hanami: Models](https://blog.codeminer42.com/from-rails-to-hanami-models-d1175d2d5b33)
* [IoT Saga - My first (for development) setup for a Hanami application](http://gabrielmalakias.com.br/hanami/iot/docker/2017/02/14/iot-saga-my-setup-for-a-hanami-application.html)

### User Groups
* [São Paulo, Brasil](https://twitter.com/hanamirb_sp) - Grupo de usuários Hanami-rb de São Paulo.
* [Facebook, Brasil](https://www.facebook.com/groups/1415625271796799) - Grupo brasileiro de discussão no Facebook.

### Benchmarks
* [hanami-bench](https://github.com/davydovanton/hanami-bench) - Benchmarks for hanami

## Contribute
Contributions welcome! Read the [contribution guidelines](contributing.md) first.
