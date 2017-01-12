# Ansible Role: Percaon Package Repo

Ansible role for Percona's package repos.

Based on [Jeff Geerling's EPEL role](https://github.com/geerlingguy/ansible-role-repo-epel)

## Requirements

None

## Role Variables

See `defaults/main.yml`.

## Dependencies

None

## Add to Requirements

    - src: https://github.com/nexcess/ansible-role-repo-percona.git
      name: nexcess.repo-percona

## Example Playbook

    - hosts: db
      roles:
        - nexcess.repo-percona

## License

MIT
