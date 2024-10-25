ldap
=================

your description

OS Platform
-----------------

### Debian

- bookworm
- bullseye

Role Variables
--------------

### [defaults/main.yml](defaults/main.yml)

設定方法の詳細については[defaults/main.yml](defaults/main.yml)のサンプルコードなどを参照してください。

#### `ldap_version`

インストールするバージョン

#### `ldap_packages`

インストールするパッケージ

### [vars/main.yml](vars/main.yml)

設定値については[vars/main.yml](vars/main.yml)を参照してください。

#### `ldap_dependency_packages`

#### `ldap_home`

#### `ldap_user`

#### `ldap_group`

Example Playbook
--------------

```yaml
- hosts: servers
  roles:
    - role: ldap
```

License
--------------

Apache License 2.0
