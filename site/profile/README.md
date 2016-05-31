A Profile defines some re-usable concept, component, or best practice for
a given infrastructure.  Profiles are created out of classes and defined
types packaged in re-usable modules.

A profile maps defaults to hiera data included in the `data` directory.

In its simplest form a profile describes what it means to run an application
or class of application within an infrastructure.  For example, in a
relatively homogenious environment, it might define what it means to run a
webserver, packaging up the best practices, as agreed to by your org,
involved with running a webserver.  The consumer of this profile (a role)
should not need to be concerned about which webserver. Doing this allows you
to move, ideally, from apache to nginx, without the consumer caring.

That level of homogeniety might not exist in an infrastructure, or consumers
may need to care about the particular technologies underlying their
infrastructure, but a profile can still have considerable value in defining
what it means to run a more specific application, rather than a class of
applications, in an infrastructure. For example, creating a default,
batteries-included Apache install that epitomizes how Apache should be ran
within an org.


User    \
         |
Package -|
         |
Service -|
         |--- profile::base
Group   -|
         |
Motd    -|
         |
Ntp    -'
