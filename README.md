Role Name
=========

Role to install PhantomJS.

Requirements
------------

None.

Role Variables
--------------

```yml
phantomjs_file:   phantomjs-2.1.1-linux-x86_64
phantomjs_ext:    .tar.bz2
phantomjs_md5:    1c947d57fce2f21ce0b43fe2ed7cd361
phantomjs_sha256: 86dd9a4bf4aee45f1a84c9f61cf1947c1d6dce9b9e8d2a907105da7852460d2f
```

Dependencies
------------

```
bearandgiraffe.base
```

Example Playbook
----------------

```yml
  - hosts: servers
    roles:
    - { role: bearandgiraffe.phantomjs, phantomjs_file: phantomjs-2.1.1-linux-x86_64 }
```

License
-------

The Unlicense (see LICENSE)

Author Information
------------------

Youssef Chaker (@ychaker) from Bear & Giraffe LLC (@bearandgiraffe).
