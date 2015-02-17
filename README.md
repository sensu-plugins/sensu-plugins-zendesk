## Sensu-Plugins-zendesk

[![Build Status](https://travis-ci.org/sensu-plugins/sensu-plugins-zendesk.svg?branch=master)](https://travis-ci.org/sensu-plugins/sensu-plugins-zendesk)
[![Gem Version](https://badge.fury.io/rb/sensu-plugins-zendesk.svg)](http://badge.fury.io/rb/sensu-plugins-zendesk)
[![Code Climate](https://codeclimate.com/github/sensu-plugins/sensu-plugins-zendesk/badges/gpa.svg)](https://codeclimate.com/github/sensu-plugins/sensu-plugins-zendesk)
[![Test Coverage](https://codeclimate.com/github/sensu-plugins/sensu-plugins-zendesk/badges/coverage.svg)](https://codeclimate.com/github/sensu-plugins/sensu-plugins-zendesk)
[![Dependency Status](https://gemnasium.com/sensu-plugins/sensu-plugins-zendesk.svg)](https://gemnasium.com/sensu-plugins/sensu-plugins-zendesk)

## Functionality

## Files
 * bin/handler-zendesk

## Usage

```
{
    "zendesk": {
        "url": "https://mydesk.zendesk.com/api/v2",
        "username" : "login.email@zendesk.com",
        "token": "your zendesk token",
        "password": "your zendesk password",
        "type": "incident",
        "priority": "urgent",
        "tags": [
            "tag1"
        ],
        "subscriptions_to_tags": false,
        "status_to_use": [2]
  }
}
```
## Installation

Add the public key (if you haven’t already) as a trusted certificate

```
gem cert --add <(curl -Ls https://raw.githubusercontent.com/sensu-plugins/sensu-plugins.github.io/master/certs/sensu-plugins.pem)
gem install sensu-plugins-zendesk -P MediumSecurity
```

You can also download the key from /certs/ within each repository.

#### Rubygems

`gem install sensu-plugins-zendesk`

#### Bundler

Add *sensu-plugins-disk-checks* to your Gemfile and run `bundle install` or `bundle update`

#### Chef

Using the Sensu **sensu_gem** LWRP
```
sensu_gem 'sensu-plugins-zendesk' do
  options('--prerelease')
  version '0.0.1'
end
```

Using the Chef **gem_package** resource
```
gem_package 'sensu-plugins-zendesk' do
  options('--prerelease')
  version '0.0.1'
end
```

## Notes
