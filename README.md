## Sensu-Plugins-sftp

[![Build Status](https://travis-ci.org/sensu-plugins/sensu-plugins-sftp.svg?branch=master)](https://travis-ci.org/sensu-plugins/sensu-plugins-sftp)
[![Gem Version](https://badge.fury.io/rb/sensu-plugins-sftp.svg)](http://badge.fury.io/rb/sensu-plugins-sftp)
[![Code Climate](https://codeclimate.com/github/sensu-plugins/sensu-plugins-sftp/badges/gpa.svg)](https://codeclimate.com/github/sensu-plugins/sensu-plugins-sftp)
[![Test Coverage](https://codeclimate.com/github/sensu-plugins/sensu-plugins-sftp/badges/coverage.svg)](https://codeclimate.com/github/sensu-plugins/sensu-plugins-sftp)
[![Dependency Status](https://gemnasium.com/sensu-plugins/sensu-plugins-sftp.svg)](https://gemnasium.com/sensu-plugins/sensu-plugins-sftp)

## Functionality

## Files
 * bin/check-sftp

## Usage

## Installation

Add the public key (if you haven’t already) as a trusted certificate

```
gem cert --add <(curl -Ls https://raw.githubusercontent.com/sensu-plugins/sensu-plugins.github.io/master/certs/sensu-plugins.pem)
gem install sensu-plugins-sftp -P MediumSecurity
```

You can also download the key from /certs/ within each repository.

#### Rubygems

`gem install sensu-plugins-sftp`

#### Bundler

Add *sensu-plugins-disk-checks* to your Gemfile and run `bundle install` or `bundle update`

#### Chef

Using the Sensu **sensu_gem** LWRP
```
sensu_gem 'sensu-plugins-sftp' do
  options('--prerelease')
  version '0.0.1'
end
```

Using the Chef **gem_package** resource
```
gem_package 'sensu-plugins-sftp' do
  options('--prerelease')
  version '0.0.1'
end
```

## Notes
