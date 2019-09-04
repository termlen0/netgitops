```
$ tree -d
.
├── inventory
│   ├── group_vars
│   │   ├── core
│   │   ├── remote
│   │   ├── site1
│   │   └── site2
│   └── host_vars
│       ├── core1
│       ├── core2
│       ├── remote1
│       └── remote2
└── tests
    ├── pipelines
    │   ├── core
    │   ├── core1
    │   ├── core2
    │   ├── remote
    │   ├── site1
    │   └── site2
    └── roles
        ├── ansible
        │   └── tasks
        ├── ansible_lint
        │   ├── meta
        │   └── tasks
        ├── ansible_review
        │   ├── meta
        │   └── tasks
        ├── do_ansible_lint
        │   ├── meta
        │   └── tasks
        ├── do_ansible_review
        │   ├── meta
        │   └── tasks
        ├── do_prepare
        │   └── meta
        ├── do_test
        │   └── meta
        ├── docker
        │   └── tasks
        └── ios_ospfv2
            └── tasks
```
