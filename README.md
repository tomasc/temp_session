# Temp Session

[![Build Status](https://travis-ci.org/tomasc/temp_session.svg)](https://travis-ci.org/tomasc/temp_session) [![Gem Version](https://badge.fury.io/rb/temp_session.svg)](http://badge.fury.io/rb/temp_session) [![Coverage Status](https://img.shields.io/coveralls/tomasc/temp_session.svg)](https://coveralls.io/r/tomasc/temp_session)

Rails Engine with a controller that handles the following process:
* user submits email address
* receives a link that sets a session and lets him/her sign in
* helper link lets the user to sign out

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'temp_session'
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install temp_session

## Usage

TODO: Write usage instructions here

## Development

After checking out the repo, run `bin/setup` to install dependencies. Then, run `rake test` to run the tests. You can also run `bin/console` for an interactive prompt that will allow you to experiment.

To install this gem onto your local machine, run `bundle exec rake install`. To release a new version, update the version number in `version.rb`, and then run `bundle exec rake release`, which will create a git tag for the version, push git commits and tags, and push the `.gem` file to [rubygems.org](https://rubygems.org).

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/tomasc/temp_session.


## License

The gem is available as open source under the terms of the [MIT License](http://opensource.org/licenses/MIT).
