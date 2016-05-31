Roles encapsulate "domain" like concepts within an infrastructure.  They
are built out of the infrastructure components and concepts defined in
profiles.  Many hosts may have the same role, though a host may only have
one role.

```
profile::base  _____                                 ____  i-23ac75ba.us-east-1b.cloud.corp.com
                    \                               /
profile::webserver ----- role::our_app_frontend ---------  i-22dfaec6.us-east-1b.cloud.corp.com
                    /                               \
profile::dmz  -----`                                 `---  i-2dac73fe.us-east-1b.cloud.corp.com
```

