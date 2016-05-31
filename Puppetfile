# A Puppetfile for a control repo that represents a more realistic deployment base



# Customers may have a security policies that prevent direct access to
# the internet, do not assume forge access, though to bootstrap this
# we will use Github as our "internal mirror"
forge "http://forge.puppetlabs.com"


# Additional modules to complement and complete a PE installation
mod 'hunner/hiera',                     git: 'https://github.com/voxpupuli/puppet-hiera',                ref: '2.0.1'
mod 'puppetlabs/puppetserver_gem',      git: 'https://github.com/puppetlabs/puppetlabs-puppetserver_gem' ref: '0.2.0'
mod 'puppetlabs/inifile',               git: 'https://github.com/puppetlabs/puppetlabs-inifile',         ref: '1.2.0'
mod 'puppetlabs/concat',                git: 'https://github.com/puppetlabs/puppetlabs-concat',          ref: '2.1.0'
mod 'puppetlabs/hocon',                 git: 'https://github.com/puppetlabs/puppetlabs-hocon',           ref: '0.9.4'
mod 'puppetlabs/stdlib',                git: 'https://github.com/puppetlabs/puppetlabs-stdlib',          ref: '4.11.0'
mod 'puppetlabs/vcsrepo',               git: 'https://github.com/puppetlabs/puppetlabs-vcsrepo',         ref: '1.3.2'
mod 'puppet/archive',                   git: 'https://github.com/puppet-community/puppet-archive',       ref: '0.5.1'
mod 'npwalker/pe_code_manager_webhook', git: 'https://github.com/npwalker/pe_code_manager_webhook',      ref: '1.0.7'


# Basic linux host management
mod 'puppetlabs/accounts',  git: 'https://github.com/puppetlabs/puppetlabs-accounts',  ref: '1.0.0'
mod 'puppetlabs/apt',       git: 'https://github.com/puppetlabs/puppetlabs-apt',       ref: '2.2.2'
mod 'jlambert121/yum',      git: 'https://github.com/jlambert121/jlambert121-yum',     ref: '0.2.1'
mod 'puppetlabs/ntp',       git: 'https://github.com/puppetlabs/puppetlabs-ntp',       ref: '4.2.0'
mod 'puppetlabs/firewall',  git: 'https://github.com/puppetlabs/puppetlabs-firewall',  ref: '1.8.1'
mod 'puppetlabs/motd',      git: 'https://github.com/puppetlabs/puppetlabs-motd',      ref: '1.4.0'
mod 'yo61/logrotate',       git: 'https://github.com/yo61/puppet-logrotate',           ref: '1.4.0'
mod 'ghoneycutt/logrotate', git: 'https://github.com/ghoneycutt/puppet-module-ssh',    ref: '3.36.0'
mod 'ghoneycutt/pam',       git: 'https://github.com/ghoneycutt/puppet-module-pam',    ref: '2.22.0'
mod 'saz/rsyslog',          git: 'https://github.com/saz/puppet-rsyslog',              ref: '3.5.1'


# Advanced linux host management
mod 'garethr/docker', git: 'https://github.com/garethr/garethr-docker', ref: '5.2.0'
mod 'vshn/gitlab',    git: 'https://github.com/vshn/puppet-gitlab',     ref: '1.8.0'
mod 'gms',            git: 'https://github.com/abrader/abrader-gms',    ref: 'v1.0.2'



# Common tools in an infrastructure
mod 'puppetlabs/postgresql',       git: 'https://github.com/puppetlabs/puppetlabs-postgresql', ref: '4.7.1'
mod 'camptocamp/openldap',         git: 'https://github.com/camptocamp/puppet-openldap',       ref: '1.14.0'
mod 'arioch/redis',                git: 'https://github.com/arioch/puppet-redis',              ref: '1.2.2'
mod 'golja/influxdb',              git: 'https://github.com/n1tr0g/golja-influxdb',            ref: '3.0.1'
mod 'saz/memcached',               git: 'https://github.com/saz/puppet-memcached',             ref: '2.8.1'

mod 'thais/squid3',          git: 'https://github.com/thias/puppet-squid3',              ref: '1.0.0'
mod 'puppetlabs/haproxy',    git: 'https://github.com/puppetlabs/puppetlabs-haproxy',    ref: '1.4.0'
mod 'puppetlabs/apache',     git: 'https://github.com/puppetlabs/puppetlabs-apache',     ref: '1.10.0'
mod 'jfryman/nginx',         git: 'http://github.com/jfryman/puppet-nginx',              ref: '0.3.0'
mod 'puppetlabs/tomcat',     git: 'https://github.com/puppetlabs/puppetlabs-tomcat',     ref: '1.5.0'

mod 'rtyler/jenkins',        git: 'https://github.com/jenkinsci/puppet-jenkins',         ref: '1.6.1'
mod 'sensu/sensu',           git: 'https://github.com/sensu/sensu-puppet',               ref: '2.1.0'
mod 'bfraser/grafana',       git: 'https://github.com/bfraser/puppet-grafana',           ref: '2.5.0'

mod 'elasticsearch/elasticsearch',     git: 'https://github.com/elastic/puppet-elasticsearch',     ref: '0.11.0'
mod 'elasticsearch/logstash',          git: 'https://github.com/elastic/puppet-logstash',          ref: '0.6.4'
mod 'elasticsearch/logstashforwarder', git: 'https://github.com/elastic/puppet-logstashforwarder', ref: '0.1.1'

mod 'puppetlabs/java',       git: 'https://github.com/puppetlabs/puppetlabs-java',       ref: '1.5.0'
mod 'puppetlabs/java_ks',    git: 'https://github.com/puppetlabs/puppetlabs-java_ks',    ref: '1.4.1'


# Basic Windows host management
mod 'puppetlabs/acl',            git: 'https://github.com/puppetlabs/puppetlabs-acl',           ref: '1.1.2'
mod 'puppetlabs/reboot',         git: 'https://github.com/puppetlabs/puppetlabs-reboot',        ref: '1.2.1'
mod 'chocolatey/chocolatey',     git: 'https://github.com/chocolatey/puppet-chocolatey',        ref: '1.2.3'
mod 'puppetlabs/powershell',     git: 'https://github.com/puppetlabs/puppetlabs-powershell',    ref: '2.0.1'
mod 'puppetlabs/registry',       git: 'https://github.com/puppetlabs/puppetlabs-registry',      ref: '1.1.3'
mod 'puppetlabs/wsus_client',    git: 'https://github.com/puppetlabs/puppetlabs-wsus_client',   ref: '1.0.2'
mod 'badgerious/windows_env',    git: 'https://github.com/badgerious/puppet-windows-env',       ref: '2.2.2'
mod 'puppet/windows_firewall',   git: 'https://github.com/voxpupuli/puppet-windows_firewall',   ref: '1.0.3'
mod 'puppet/windows_autoupdate', git: 'https://github.com/voxpupuli/puppet-windows_autoupdate', ref: '1.1.0'
mod 'puppet/dotnet',             git: 'https://github.com/puppet-community/puppet-dotnet',      ref: '1.0.2'
mod 'puppet/windowsfeature',     git: 'https://github.com/puppet-community/windowsfeature',     ref: '1.1.0'
mod 'puppet/windows_eventlog',   git: 'https://github.com/voxpupuli/puppet-windows_eventlog',   ref: '1.1.1'


# Advanced Windows host management
mod 'chocolatey/chocolatey_server', git: 'https://github.com/chocolatey/puppet-chocolatey_server', ref: '0.0.4'
mod 'puppetlabs/sqlserver',         git: 'https://github.com/puppetlabs/puppetlabs-sqlserver',     ref: '1.1.2'
mod 'puppet/iis',                   git: 'https://github.com/voxpupuli/puppet-iis',                ref: '2.0.2'
mod 'puppet/graphite_powershell',   git: 'https://github.com/voxpupuli/puppet-windows_eventlog',   ref: '1.0.1'


# And while we're at it, lets do this all in the cloud
mod 'puppetlabs/aws', git: 'https://github.com/puppetlabs/puppetlabs-aws', ref: '1.4.0'
