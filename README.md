# Solidus Wishlist

[![CircleCI](https://circleci.com/gh/deseretbook/solidus_wishlist.svg?style=svg)](https://circleci.com/gh/deseretbook/solidus_wishlist)

A Solidus Wishlist extension enables multiple wishlists per user, as well as managing those as public (sharable) and private. It also includes the ability to notify a friend via email of a recommended product.

---

## Installation

Add the following to your `Gemfile`
```ruby
gem 'solidus_wishlist', github: 'deseretbook/solidus_wishlist'
gem 'solidus_email_to_friend', github: 'welitonfreitas/solidus_email_to_friend'
```

Run
```sh
$ bundle install
$ bundle exec rails g solidus_wishlist:install
```

---

## Gem is under development

Feature "share wish list with friend" with URL contains access hash is not available right now, see [PR](https://github.com/denkungsart/solidus_wishlist/pull/1).

## 1.5.0 version

Introduce session-based wish lists. When user logged in, session-based wish lists will be added to this user.

---
Copyright (c) 2016 Deseret Book, released under the New BSD License
