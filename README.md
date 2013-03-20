# Newrelic::Rake

NewRelic instrument for rake task.

## Installation

Add this line to your application's Gemfile:

    gem 'newrelic-rake'

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install newrelic-rake

## Usage

This gem does not provide automatic agent start and dispatcher discovery, to make sure your rake tasks are properly monitored, prefix them with `NEWRELIC_DISPATCHER=rake` environment variable.

```
NEWRELIC_DISPATCHER=rake rake foo:bar:baz
```

## Authors and Contributors

* [Richard Huang](https://github.com/flyerhzm) - Creator of the project
* [Yury Velikanau](yury.velikanau@gmail.com) - Main contributor

Please fork and contribute, any help in making this project better is appreciated!

This project is a member of the [OSS Manifesto](http://ossmanifesto.org/).

## Copyright

Copyright @ 2012 - 2013 Richard Huang. See
[MIT-LICENSE](https://github.com/flyerhzm/newrelic-rake/blob/master/MIT-LICENSE) for details
