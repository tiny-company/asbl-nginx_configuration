# nginx_configuration

## Description

ansible playbook role to configure nginx service.

## Prerequisite

- None

## Usage

### Use role

- Add the role git source in "requirements.yml" file :
```
  - name: role_name
    scm: git
    src: https://github.com/tiny-company/<repository_name>.git
    version: main
```

- And then use the galaxy command to load the file dependencies :
```
ansible-galaxy install -r requirements.yml
```

- Or manually get the playbook as collection (with ansible-galaxy) :
```
ansible-galaxy collection install https://github.com/tiny-company/<repository_name>.git
```

- finally use role in playbook : [see test_playbook example](./test_playbook.yml)

### Variables

For an exhaustive list of variables check the [defaults](defaults/main.yml)
file. Ideally, all values will have commentaries describing what are their
purposes and by the default value you can tell the type.

## Source :

- [nginx configuration role ansible from nginxinc](https://github.com/nginxinc/ansible-role-nginx-config/tree/main)
- [nginx official documentation](https://nginx.org/en/docs/beginners_guide.html)


