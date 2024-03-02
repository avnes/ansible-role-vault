# ansible-role-vault

![Ansible](https://github.com/avnes/ansible-role-vault/actions/workflows/ansible.yaml/badge.svg)

Ansible role for installing vault.

# :warning: Repository not maintained :warning:

Please note that this repository is currently archived, and is no longer being maintained.

- It may contain code, or reference dependencies, with known vulnerabilities
- It may contain out-dated advice, how-to's or other forms of documentation

The contents might still serve as a source of inspiration, but please review any contents before reusing elsewhere.

## Requirements

Poetry. Install it from <https://python-poetry.org/docs/>

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
