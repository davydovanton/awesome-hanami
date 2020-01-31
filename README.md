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
  * [Pagination](#pagination)
  * [CLI](#cli)
  * [Building APIs](#building-apis)
  * [API Documentation](#api-documentation)
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
* [omniauth-hanami](https://github.com/katafrakt/omniauth-hanami) – Allows to use Hanami repository as OAuth provider (similar to [omniauth-identity](https://github.com/intridea/omniauth-identity))
* [hanami-id](https://github.com/leemour/hanami_id) - Large authentication library, with generators

### Authorization
* [kan](https://github.com/davydovanton/kan) - Simple, light and functional authorization library

### File Uploading
* [hanami-shrine](https://github.com/katafrakt/hanami-shrine) - Upload solution for Hanami using Shrine library

### Performance Monitoring
* [newrelic-hanami](https://github.com/artemeff/newrelic-hanami) - Gem for connecting NewRelic and Hanami

### Testing
* [rspec-hanami](https://github.com/davydovanton/rspec-hanami) - RSpec Matchers for Hanami
* [shoulda-hanami](https://github.com/mcorp/shoulda-hanami) - Making tests easy on the fingers and eyes, but on hanami (old shoulda-lotus)
* [hanami-fabrication](https://github.com/jodosha/hanami-fabrication) - Utility to easily integrate [Fabrication](https://www.fabricationgem.org/) gem and Hanami

### Database
* [rom_sql_graph](https://github.com/davydovanton/rom_sql_graph) - DB (sql) association graph for hanami and rom projects
* [hanami-sequel](https://github.com/malin-as/hanami-sequel) - A Sequel-only replacement of [hanami-model](https://github.com/hanami/model), including CLI extension and model generation.
* [hanami-rethinkdb](https://github.com/angeloashmore/hanami-rethinkdb) - RethinkDB adapter for Hanami::Model

### Pagination
* [pagy](https://github.com/ddnexus/pagy) - The ultimate pagination ruby gem. [Integration to hanami](http://katafrakt.me/2018/06/01/integrating-pagy-with-hanami/).
* [hanami-pagination](https://github.com/davydovanton/hanami-pagination) - Pagination gem for your hanami applications. Based on ROM::Pagination plugin.

### CLI
* [hanami-events-cloud_pubsub](https://github.com/adHawk/hanami-events-cloud_pubsub) - A hanami-events adapter for Google Cloud Pub/Sub.

### Events
* [hanami-scaffold](https://github.com/davydovanton/hanami-scaffold) - Make hanami scaffolds faster.
* [hanami-zsh](https://github.com/davydovanton/hanami-zsh) - Zsh plugin for hanami projects.

### Building APIs
* [jsonapi-hanami](http://jsonapi-rb.org) - Efficiently and conveniently build [JSON API](http://jsonapi.org)-compliant APIs with Hanami.
* [hanami-jbuilder](https://github.com/vladfaust/hanami-jbuilder) - Support for rendering JBuilder templates for Hanami apps
* [hanami-serializer](https://github.com/davydovanton/hanami-serializer) - Serializer library for hanami applications

### API Documentation
* [had](https://github.com/nsheremet/had) - Hanami API Documentation

### Deploy
* [mina-hanami](https://github.com/mgrachev/mina-hanami) - [Mina](https://github.com/mina-deploy/mina) plugin for Hanami.
* [capistrano-hanami](https://github.com/mgrachev/capistrano-hanami) - Hanami tasks for [Capistrano](https://github.com/capistrano/capistrano).
* [hanami-docker](https://github.com/gruz0/hanami-docker) - Dockerize your Hanami application
* [mina-proteus](https://github.com/apontini/mina-proteus) - [Mina](https://github.com/mina-deploy/mina) plugin for Hanami than allows you to deploy a specific application in a specific environment.

### Editors and IDE
* [How to run Hanami in RubyMine](https://medium.com/@tetyanachupryna/how-to-run-hanami-in-rubymine-dff342cb0114#.7jb2bjq9f)
* [projectile-hanami](https://github.com/avdgaag/projectile-hanami) - Projectile Hanami is an Emacs minor mode, based on Projectile, for navigating Hanami projects.
* [Vim Hanami](https://github.com/sovetnik/vim-hanami) - plugin that gives you faster navigation between semantically associated files, like Action <-> View, Entity <-> Repository or Spec <-> Entity.
* [Vim Minispec](https://github.com/sovetnik/vim-minispec) - plugin runs your Gem or Hanami Minitest specs and displays the results in Vim quickfix.

## Vanilla Libraries and Hanami
* [omniauth](https://github.com/intridea/omniauth) - [Hanami with OAuth](http://codetunes.com/2016/hanami-with-oauth/)
* [Sidekiq](http://sidekiq.org) - [From Rails to Hanami Part 3](http://rpanachi.com/2016/04/25/from-rails-to-hanami-part3-sidekiq-workers-i18n-timezone-issues-core-ext), [Use Sidekiq With Hanami](http://www.strauss.io/blog/2016-use-sidekiq-with-hanami.html)
* [I18n](https://github.com/svenfuchs/i18n) - [From Rails to Hanami Part 3](http://rpanachi.com/2016/04/25/from-rails-to-hanami-part3-sidekiq-workers-i18n-timezone-issues-core-ext)
* [Sequel plugins](http://sequel.jeremyevans.net/plugins.html) - [From Rails to Hanami Part 3](http://rpanachi.com/2016/04/25/from-rails-to-hanami-part3-sidekiq-workers-i18n-timezone-issues-core-ext)
* [letter_opener](https://github.com/ryanb/letter_opener) - [Preview hanami emails in browser](http://blog.davydovanton.com/2016/05/21/preview-hanami-emails-in-browser/)
* [mongoid](https://github.com/mongodb/mongoid) - [github](https://github.com/michalvalasek/hanami-mongoid)
* [Trailblazer](https://github.com/apotonick/trailblazer) - [Hanami with Trailblazer](https://github.com/apotonick/gemgem-hanami)
* [Factory Bot](https://github.com/thoughtbot/factory_bot) - [Hanami with Factory Bot](https://gist.github.com/rafaels88/8437edababcf38ee193b2ba0265e78b9)

## Hanami Project List
### Closed Source
* [loan application platform](http://creditas.com.br) - A Brazilian startup for credit loan using a car or house as a guarantee.

### Open Source
* [cookie_box](https://github.com/davydovanton/cookie_box) - Follow and control issues from several repositories from one place.
* [OSSBoard](http://www.ossboard.org) - Simple way to connect developers and oss maintainers ([Sources](https://github.com/davydovanton/ossboard)).
* [contributors.hanamirb.org](http://contributors.hanamirb.org) - All hanami contributors in one place ([Sources](https://github.com/hanami/contributors)).
http://github.com/makedecision-org/core
* [makedecision](http://github.com/makedecision-org/core) - Make decision faster.
* [app.dartboard.io](http://app.dartboard.io) - Online darts scorer app built with Hanami([Sources](https://github.com/stravid/datsu-api))
* [pinfluence](https://github.com/prosi-org/pinfluence) - All world influencers in a map
* [scripta.io](http://www.scripta.io/home) - A platform for creating and sharing documents on the web ([Sources](https://github.com/jxxcarlson/noteshare)).

### Play/Pet projects
* [upment-hanami](https://github.com/AlexanderMint/upment-hanami) - App on Hanami: JWT, GraphQL, RSpec and [REACT client](https://github.com/AlexanderMint/upment-client)
* [distruct-me](https://github.com/MorozovaLiuda/distruct-me) - App on Hanami for self-distructing messages
* [hanami-jwt-example](https://github.com/nickgnd/hanami-jwt-example) - A simple JSON API web application built with Hanami which provides jwt-authentication, password encryption and CORS support.
* [repressed_museum](https://github.com/vasspilka/repressed_museum) - A simple mostly static website, features basic i18n and docker integration
* [bookshelf-delivery-example](https://github.com/bruz/bookshelf-delivery-example) - An example app with a web GUI, API and CLI using shared interactors.
* [hanami-chat-example](https://github.com/nickgnd/hanami-chat-example) - A basic chat application built with Hanami and [LiteCable](https://github.com/palkan/litecable) (compatible with [AnyCable](http://anycable.io/))
* [Deutsch](https://github.com/mjacobus/deutsch) - prototype tool for learning German, available [here](http://salat.netapps.website/).
* [Burn My Fat!](https://github.com/burn-my-fat/web) (ru) – Backend for a mobile application that will help you make your body more beatiful. [YouTube](https://www.youtube.com/channel/UCDAXAwUlu-lIbjRXCUtc6oA)

## Useful Links
* [Community page on the official site](http://hanamirb.org/community/)

### Blog Posts
* [What I learned building an app in Hanami](https://rossta.net/blog/what-i-learned-about-hanami.html)
* [Livereload and Hanami](https://defman.me/blog/hanami-love-livereload/)
* [Deploying Hanami web application with Puma, Nginx and PostgreSQL using Docker](https://sebastjan-hribar.github.io/programming/2018/07/19/hanami-app-deployment-example.html)
* [Getting Started with Hanami and GraphQL](https://blog.simplificator.com/2016/12/07/getting-started-with-hanami-and-graphql/)
* [From Rails to Hanami: Models](https://blog.codeminer42.com/from-rails-to-hanami-models-d1175d2d5b33)
* [IoT Saga - My first (for development) setup for a Hanami application](http://gabrielmalakias.com.br/hanami/iot/docker/2017/02/14/iot-saga-my-setup-for-a-hanami-application.html)
* [Websockets! Connecting LiteCable to Hanami](http://gabrielmalakias.com.br/ruby/hanami/iot/2017/05/26/websockets-connecting-litecable-to-hanami.html)

### User Groups
* [São Paulo, Brasil](https://twitter.com/hanamirb_sp) - Grupo de usuários Hanami-rb de São Paulo.
* [Facebook, Brasil](https://www.facebook.com/groups/1415625271796799) - Grupo brasileiro de discussão no Facebook.
* [Russian telegram community](https://t.me/hanamirb_ru).

### Benchmarks
* [hanami-bench](https://github.com/davydovanton/hanami-bench) - Benchmarks for hanami

## Contribute
Contributions welcome! Read the [contribution guidelines](contributing.md) first.
