# play-argument-spec
Ansible Play Argument Spec PoC

## Notes

1. play argument specs live in a `meta` directory adjacent to the playbook file
1. Within the `meta` dir the argspec file should match the playbook filename
1. Under the `argument_specs` top level key, play names will be used as keys
1. `return` is currently used for `set_stats`, could be renamed to `stats`
