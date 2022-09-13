# ansible-role-vault

![Ansible](https://github.com/avnes/ansible-role-vault/actions/workflows/ansible.yaml/badge.svg)

Ansible role for installing vault.

## Requirements

Poetry. Install it from <https://python-poetry.org/docs/>

## Role Variables

```yaml
vault_version: 3.7.2
```

## Dependencies

None

## Example Playbook

```yaml
- hosts: all
  roles:
     - { role: avnes.vault }
```

## For pip compability

```bash
poetry export --dev --output requirements.txt
```

## Test

```bash
poetry install
poetry shell
poetry run molecule test
```

## License

MIT

## Author Information

<https://github.com/avnes>
