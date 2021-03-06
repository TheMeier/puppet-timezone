# puppet-timezone [![Build Status](https://secure.travis-ci.org/saz/puppet-timezone.png)](http://travis-ci.org/saz/puppet-timezone)

Manage timezone settings via Puppet

### Supported Puppet versions
* Puppet >= 4
* Last version supporting Puppet 3: v3.5.0

## Usage

### Set timezone to UTC
```
    class { 'timezone':
        timezone => 'UTC',
    }
```

### Set timezone to Europe/Berlin
```
    class { 'timezone':
        timezone => 'Europe/Berlin',
    }
```

## Other class parameters
* ensure: present or absent, default: present
* autoupgrade: true or false, default: false. Auto-upgrade package, if there is a newer version
