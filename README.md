andrewrothstein.go-dev
=========

```
Set yourself up for go development with GOPATH set to ~/go
```

Requirements
------------

See [meta/main.yml](meta/main.yml)

Role Variables
--------------

See [defaults/main.yml](defaults/main.yml)

Dependencies
------------

See [meta/main.yml](meta/main.yml)

Example Playbook
----------------

```yml
- hosts: servers
  roles:
    - role: andrewrothstein.go-dev
	  go_dev_get:
	    - github.com/cloudflare/cfssl/cmd/...
```

See [test.yml](test.yml)

License
-------

MIT

Author Information
------------------

Andrew Rothstein <andrew.rothstein@gmail.com>
