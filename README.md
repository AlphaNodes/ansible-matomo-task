# Ansible Role: matomo-task

Run Matomo tasks for an installed matomo

- run console tasks
- run config.ini.php sync for cluster mode
- run import dump

## Dependencies

An installed redmine.

## Example Playbook

    - hosts: server-name
      vars:
        matomo_url: https://my.url-to-matomo.com
        matomo_console_name: core:archive
      roles:
        - AlphaNodes.matomo-task

## License

GPL Version 3

## Author Information

This role was created in 2019 by [AlphaNodes](https://alphanodes.com/).
