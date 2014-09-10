# jquery-tokeninput-rails

Integration [jquery-tokeninput](https://github.com/loopj/jquery-tokeninput) with the asset pipeline.

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'jquery-tokeninput-rails', :github => 'progresspoint/jquery-tokeninput-rails'
```

And then execute:

```sh
$ bundle install
```

Or install it yourself as:

```sh
$ git clone git@github.com:progresspoint/jquery-tokeninput-rails.git
$ cd jquery-tokeninput-rails
$ gem build jquery-tokeninput-rails.gemspec
$ gem install jquery-tokeninput-rails-version.gem
```

## Usage

### Javascript include

```javascript
//= require jquery.tokeninput
```

### Stylesheet include

```css
 *=  require token-input
```

Or

```css
 *= require token-input-facebook
```

Or

```css
 *=  require token-input-mac
```
