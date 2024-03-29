# SlackCli

A simple command-line interface for Slack.

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'slack_cli'
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install slack_cli

## Usage (not yet implemented)

If it is your first time running the Slack CLI, run `slack auth` to authorize the application to access your Slack account. This will open your browser and prompt you to log in to Slack.

After you've authorized the application, use `slack [channel name]` to open up communication on a particular channel.

## Development

After checking out the repo, run `bin/setup` to install dependencies. Then, run `rake spec` to run the tests. You can also run `bin/console` for an interactive prompt that will allow you to experiment.

To install this gem onto your local machine, run `bundle exec rake install`. To release a new version, update the version number in `version.rb`, and then run `bundle exec rake release`, which will create a git tag for the version, push git commits and tags, and push the `.gem` file to [rubygems.org](https://rubygems.org).

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/jdormit/slack_cli. This project is intended to be a safe, welcoming space for collaboration, and contributors are expected to adhere to the [Contributor Covenant](http://contributor-covenant.org) code of conduct.


## License

The gem is available as open source under the terms of the [MIT License](http://opensource.org/licenses/MIT).
