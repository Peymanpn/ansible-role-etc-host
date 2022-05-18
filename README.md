# ansible-etc-host

An ansible role to manage /etc/hosts.

## Requirements

No specific requirements

## Role Variables

None of the variables below are required.

| Variable                                 | Default                              | Comments                                                                                                          |
| :---                                     | :---                                 | :---                                                                                                              |
| `etc_hosts`                              | []                                   | A dictionary of host name / ip addresses.                                                                         |
|                                          |                                      |                                                                                                                   |

### Sample:etc_hosts dictionary

```yaml
etc_hosts:
  server_name: 192.168.0.1
  another_server: 192.168.0.2

```

## Dependencies

No dependencies.

## Example Playbook

See the [test playbook](tests/test.yml)

## License

MIT, see [License](LICENSE)
