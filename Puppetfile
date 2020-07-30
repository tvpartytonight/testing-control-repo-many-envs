# A Puppetfile for a control repo that represents a more realistic deployment base



# Customers may have a security policies that prevent direct access to
# the internet, do not assume forge access, though to bootstrap this
# we will use Github as our "internal mirror"
forge "http://forge.puppetlabs.com"


# Additional modules to complement and complete a PE installation
mod 'puppetlabs/staging', :git => 'https://github.com/nanliu/puppet-staging', :ref => '1.0.4'
mod 'puppetlabs/concat', :git => 'https://github.com/puppetlabs/puppetlabs-concat', :ref => 'v6.2.0'
mod 'puppetlabs/inifile', :git => 'https://github.com/puppetlabs/puppetlabs-inifile', :ref => '2.2.0'
mod 'stdlib', :git => 'https://github.com/puppetlabs/puppetlabs-stdlib', :ref => 'v6.3.0'
mod 'vcsrepo', :git => 'https://github.com/puppetlabs/puppetlabs-vcsrepo', :ref => 'v3.1.1'
mod 'puppet/archive', :git => 'https://github.com/voxpupuli/puppet-archive', :ref => 'v4.5.0'
mod 'npwalker/pe_code_manager_webhook', git: 'https://github.com/npwalker/pe_code_manager_webhook',       tag: '1.0.7'


# Basic linux host management
mod 'puppetlabs/accounts',  git: 'https://github.com/puppetlabs/puppetlabs-accounts',  tag: '1.0.0'
mod 'puppetlabs/apt',       git: 'https://github.com/puppetlabs/puppetlabs-apt',       tag: 'v7.4.2'
mod 'jlambert121/yum',      git: 'https://github.com/jlambert121/jlambert121-yum',     tag: '0.2.1'
mod 'puppetlabs/ntp',       git: 'https://github.com/puppetlabs/puppetlabs-ntp',       tag: '4.2.0'
mod 'puppetlabs/firewall',  git: 'https://github.com/puppetlabs/puppetlabs-firewall',  tag: 'v2.5.0'
mod 'puppetlabs/motd',      git: 'https://github.com/puppetlabs/puppetlabs-motd',      tag: '1.4.0'
mod 'yo61/logrotate',       git: 'https://github.com/yo61/puppet-logrotate',           tag: 'v1.4.0'
mod 'ghoneycutt/ssh',       git: 'https://github.com/ghoneycutt/puppet-module-ssh',    tag: 'v3.36.0'
mod 'ghoneycutt/pam',       git: 'https://github.com/ghoneycutt/puppet-module-pam',    tag: 'v2.22.0'
mod 'saz/rsyslog',          git: 'https://github.com/saz/puppet-rsyslog',              tag: 'v3.5.1'
mod 'kmod', :git => 'https://github.com/camptocamp/puppet-kmod', :ref => '2.5.0'
mod 'sysctl', :git => 'https://github.com/duritong/puppet-sysctl', :ref => 'v0.0.12'
mod 'rsync', :git => 'https://github.com/puppetlabs/puppetlabs-rsync', :ref => '1.1.1'


# Advanced linux host management
mod 'garethr/docker', git: 'https://github.com/garethr/garethr-docker', tag: 'v5.2.0'
mod 'vshn/gitlab',    git: 'https://github.com/vshn/puppet-gitlab',     tag: 'v1.8.0'
mod 'gms',            git: 'https://github.com/abrader/abrader-gms',    tag: 'v1.0.2'



# Common tools in an infrastructure
mod 'mysql', :git => 'https://github.com/puppetlabs/puppetlabs-mysql', :ref => 'v10.6.0'
mod 'puppetlabs/postgresql',       git: 'https://github.com/puppetlabs/puppetlabs-postgresql', tag: 'v6.6.0'
mod 'camptocamp/openldap',         git: 'https://github.com/camptocamp/puppet-openldap',       tag: '1.14.0'
mod 'arioch/redis',                git: 'https://github.com/arioch/puppet-redis',              tag: '1.2.2'
mod 'golja/influxdb',              git: 'https://github.com/n1tr0g/golja-influxdb',            tag: '3.0.1'
mod 'saz/memcached',               git: 'https://github.com/saz/puppet-memcached',             tag: 'v3.5.0'
mod 'rabbitmq', :git => 'https://github.com/voxpupuli/puppet-rabbitmq', :ref => 'v10.1.1'

mod 'thais/squid3',          git: 'https://github.com/thias/puppet-squid3',              tag: '1.0.0'
mod 'puppetlabs/haproxy',    git: 'https://github.com/puppetlabs/puppetlabs-haproxy',    tag: '1.4.0'
mod 'puppetlabs/apache',     git: 'https://github.com/puppetlabs/puppetlabs-apache',     tag: 'v5.5.0'
mod 'jfryman/nginx',         git: 'https://github.com/jfryman/puppet-nginx',              tag: 'v0.3.0'
mod 'puppetlabs/tomcat',     git: 'https://github.com/puppetlabs/puppetlabs-tomcat',     tag: '1.5.0'

mod 'rtyler/jenkins',        git: 'https://github.com/jenkinsci/puppet-jenkins',         tag: 'v1.6.1'
mod 'sensu/sensu',           git: 'https://github.com/sensu/sensu-puppet',               tag: 'v2.1.0'
mod 'bfraser/grafana',       git: 'https://github.com/bfraser/puppet-grafana',           tag: 'v2.5.0'

mod 'elasticsearch/elasticsearch',     git: 'https://github.com/elastic/puppet-elasticsearch',     tag: '0.11.0'
mod 'elasticsearch/logstash',          git: 'https://github.com/elastic/puppet-logstash',          tag: '0.6.4'
mod 'elasticsearch/logstashforwarder', git: 'https://github.com/elastic/puppet-logstashforwarder', tag: '0.1.1'

mod 'puppetlabs/java',       git: 'https://github.com/puppetlabs/puppetlabs-java',       tag: '1.5.0'
mod 'puppetlabs/java_ks',    git: 'https://github.com/puppetlabs/puppetlabs-java_ks',    tag: '1.4.1'


# Basic Windows host management
mod 'puppetlabs/acl',            git: 'https://github.com/puppetlabs/puppetlabs-acl',           tag: '1.1.2'
mod 'puppetlabs/reboot',         git: 'https://github.com/puppetlabs/puppetlabs-reboot',        tag: '1.2.1'
mod 'chocolatey/chocolatey',     git: 'https://github.com/chocolatey/puppet-chocolatey',        tag: '1.2.3'
# Very chonky in terms of file count. Cloning from git, because you get twice the chonk that way.
mod 'puppetlabs/dsc',            git: 'https://github.com/puppetlabs/puppetlabs-dsc',           tag: 'v1.9.3'
mod 'puppetlabs/powershell',     git: 'https://github.com/puppetlabs/puppetlabs-powershell',    tag: '2.0.1'
mod 'puppetlabs/registry',       git: 'https://github.com/puppetlabs/puppetlabs-registry',      tag: '1.1.3'
mod 'puppetlabs/wsus_client',    git: 'https://github.com/puppetlabs/puppetlabs-wsus_client',   tag: '1.0.2'
mod 'badgerious/windows_env',    git: 'https://github.com/badgerious/puppet-windows-env',       tag: 'v2.2.2'
mod 'puppet/windows_firewall',   git: 'https://github.com/voxpupuli/puppet-windows_firewall',   tag: 'v1.0.3'
mod 'puppet/windows_autoupdate', git: 'https://github.com/voxpupuli/puppet-windows_autoupdate', tag: 'v1.1.0'
mod 'puppet/windowsfeature',     git: 'https://github.com/voxpupuli/puppet-windowsfeature',     tag: 'v1.1.0'
mod 'puppet/windows_eventlog',   git: 'https://github.com/voxpupuli/puppet-windows_eventlog',   tag: 'v1.1.1'


# Advanced Windows host management
mod 'chocolatey/chocolatey_server', git: 'https://github.com/chocolatey/puppet-chocolatey_server',  tag: '0.0.4'
mod 'puppetlabs/sqlserver',         git: 'https://github.com/puppetlabs/puppetlabs-sqlserver',      tag: 'v2.6.2'
mod 'puppet/iis',                   git: 'https://github.com/voxpupuli/puppet-iis',                 tag: 'v2.0.2'
mod 'puppet/graphite_powershell',   git: 'https://github.com/voxpupuli/puppet-graphite_powershell', tag: 'v1.0.1'


# And while we're at it, lets do this all in the cloud
mod 'puppetlabs/aws',               git: 'https://github.com/puppetlabs/puppetlabs-aws', tag: '2.1.0'
mod 'puppetlabs/amazon_aws',        git: 'https://github.com/puppetlabs/puppetlabs-amazon_aws', tag: '0.3.0'
# One chonky boi. Twice as big as puppetlabs/dsc.
mod 'puppetlabs/azure_arm',         git: 'https://github.com/puppetlabs/puppetlabs-azure_arm', tag: '0.2.2'
mod 'puppetlabs/kubernetes',        git: 'https://github.com/puppetlabs/puppetlabs-kubernetes', tag: 'v5.1.0'
mod 'puppetlabs/vsphere',           git: 'https://github.com/puppetlabs/puppetlabs-vsphere', tag: 'v1.5.0'
mod 'google/gauth',                 '0.3.0'
mod 'google/gcompute',              '0.3.0'


# Since we're doing cloud, why not manage an OpenStack install.
# From the Openstack control repo:
#   https://opendev.org/openstack/puppet-openstack-integration/src/branch/master/Puppetfile
mod 'aodh', :git => 'https://opendev.org/openstack/puppet-aodh', :ref => 'master'
mod 'barbican', :git => 'https://opendev.org/openstack/puppet-barbican', :ref => 'master'
mod 'ceilometer', :git => 'https://opendev.org/openstack/puppet-ceilometer', :ref => 'master'
mod 'ceph', :git => 'https://opendev.org/openstack/puppet-ceph', :ref => 'master'
mod 'cinder', :git => 'https://opendev.org/openstack/puppet-cinder', :ref => 'master'
mod 'cloudkitty', :git => 'https://opendev.org/openstack/puppet-cloudkitty', :ref => 'master'
mod 'designate', :git => 'https://opendev.org/openstack/puppet-designate', :ref => 'master'
mod 'ec2api', :git => 'https://opendev.org/openstack/puppet-ec2api', :ref => 'master'
mod 'glance', :git => 'https://opendev.org/openstack/puppet-glance', :ref => 'master'
mod 'gnocchi', :git => 'https://opendev.org/openstack/puppet-gnocchi', :ref => 'master'
mod 'heat', :git => 'https://opendev.org/openstack/puppet-heat', :ref => 'master'
mod 'horizon', :git => 'https://opendev.org/openstack/puppet-horizon', :ref => 'master'
mod 'ironic', :git => 'https://opendev.org/openstack/puppet-ironic', :ref => 'master'
mod 'keystone', :git => 'https://opendev.org/openstack/puppet-keystone', :ref => 'master'
mod 'magnum', :git => 'https://opendev.org/openstack/puppet-magnum', :ref => 'master'
mod 'manila', :git => 'https://opendev.org/openstack/puppet-manila', :ref => 'master'
mod 'mistral', :git => 'https://opendev.org/openstack/puppet-mistral', :ref => 'master'
mod 'monasca', :git => 'https://opendev.org/openstack/puppet-monasca', :ref => 'master'
mod 'murano', :git => 'https://opendev.org/openstack/puppet-murano', :ref => 'master'
mod 'neutron', :git => 'https://opendev.org/openstack/puppet-neutron', :ref => 'master'
mod 'nova', :git => 'https://opendev.org/openstack/puppet-nova', :ref => 'master'
mod 'octavia', :git => 'https://opendev.org/openstack/puppet-octavia', :ref => 'master'
mod 'openstack_extras', :git => 'https://opendev.org/openstack/puppet-openstack_extras', :ref => 'master'
mod 'openstacklib', :git => 'https://opendev.org/openstack/puppet-openstacklib', :ref => 'master'
mod 'oslo', :git => 'https://opendev.org/openstack/puppet-oslo', :ref => 'master'
mod 'ovn', :git => 'https://opendev.org/openstack/puppet-ovn', :ref => 'master'
mod 'panko', :git => 'https://opendev.org/openstack/puppet-panko', :ref => 'master'
mod 'placement', :git => 'https://opendev.org/openstack/puppet-placement', :ref => 'master'
mod 'qdr', :git => 'https://opendev.org/openstack/puppet-qdr', :ref => 'master'
mod 'sahara', :git => 'https://opendev.org/openstack/puppet-sahara', :ref => 'master'
mod 'swift', :git => 'https://opendev.org/openstack/puppet-swift', :ref => 'master'
mod 'tacker', :git => 'https://opendev.org/openstack/puppet-tacker', :ref => 'master'
mod 'tempest', :git => 'https://opendev.org/openstack/puppet-tempest', :ref => 'master'
mod 'trove', :git => 'https://opendev.org/openstack/puppet-trove', :ref => 'master'
mod 'vswitch', :git => 'https://opendev.org/openstack/puppet-vswitch', :ref => 'master'
mod 'vitrage', :git => 'https://opendev.org/openstack/puppet-vitrage', :ref => 'master'
mod 'watcher', :git => 'https://opendev.org/openstack/puppet-watcher', :ref => 'master'
mod 'zaqar', :git => 'https://opendev.org/openstack/puppet-zaqar', :ref => 'master'

## External OpenStack modules
mod 'powerdns', :git => 'https://github.com/antonlindstrom/puppet-powerdns', :ref => '0.0.5'
mod 'ipaclient', :git => 'https://github.com/joshuabaird/puppet-ipaclient', :ref => '2.5.2'
mod 'git_resource', :git => 'https://github.com/voxpupuli/puppet-git_resource', :ref => 'v1.0.2'
mod 'xinetd', :git => 'https://github.com/puppetlabs/puppetlabs-xinetd', :ref => 'v3.3.0'
mod 'python', :git => 'https://github.com/voxpupuli/puppet-python', :ref => 'v4.1.1'
mod 'dns', :git => 'https://github.com/theforeman/puppet-dns', :ref => '8.0.0'
mod 'corosync', :git => 'https://github.com/voxpupuli/puppet-corosync', :ref => 'v5.0.0'
mod 'ssh_keygen', :git => 'https://github.com/voxpupuli/puppet-ssh_keygen', :ref => 'v2.0.1'


# Large file counts. These modules were packaged with extranoeous directories
# like bundle/ and vendor/ that contain thousends of files.
mod 'dalen/dnsquery', '3.0.0'
mod 'ontotext/graphdb', '0.1.0'
mod 'optiz0r/sabayon', '0.0.2'
mod 'poxvupuli/inert', '0.1.0'
mod 'puppet/dotnet', '1.0.2'
mod 'puppet/rundeck', '2.1.0'
mod 'swisscom/scaleio', '3.0.1'
mod 'yuav/autofs', '1.2.2'
mod 'yuav/monitoring', '0.3.4'
mod 'yuav/monitoring_facts', '0.2.7'
