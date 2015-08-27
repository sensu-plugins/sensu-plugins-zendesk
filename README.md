## Sensu-Plugins-zendesk

[ ![Build Status](https://travis-ci.org/sensu-plugins/sensu-plugins-zendesk.svg?branch=master)](https://travis-ci.org/sensu-plugins/sensu-plugins-zendesk)
[![Gem Version](https://badge.fury.io/rb/sensu-plugins-zendesk.svg)](http://badge.fury.io/rb/sensu-plugins-zendesk)
[![Code Climate](https://codeclimate.com/github/sensu-plugins/sensu-plugins-zendesk/badges/gpa.svg)](https://codeclimate.com/github/sensu-plugins/sensu-plugins-zendesk)
[![Test Coverage](https://codeclimate.com/github/sensu-plugins/sensu-plugins-zendesk/badges/coverage.svg)](https://codeclimate.com/github/sensu-plugins/sensu-plugins-zendesk)
[![Dependency Status](https://gemnasium.com/sensu-plugins/sensu-plugins-zendesk.svg)](https://gemnasium.com/sensu-plugins/sensu-plugins-zendesk)
[![Codeship Status for sensu-plugins/sensu-plugins-zendesk](https://codeship.com/projects/de182970-e203-0132-9c61-4ea0dd54b93d/status?branch=master)](https://codeship.com/projects/81356)

## Functionality

## Files
 * bin/handler-zendesk.rb

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

[Installation and Setup](http://sensu-plugins.io/docs/installation_instructions.html)


## Notes
