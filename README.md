# New Relic

Software Analytics for better app performance customer experience business results.

## Role Variables

* `newrelic_license_key` - **Required**. Your license key from [New Relic](http://newrelic.com/).
* `newrelic_sysmond` - Boolean. Install the system monitoring agent. Defaults to `True`.
* `newrelic_sysmond_upgrade` - Boolean. Use it to perform a package upgrade.

## Example Playbook

```yaml
- hosts: servers
  roles:
    - { role: SobanVuex.newrelic, newrelic_license_key: <your_newrelic_license_key> }
```

## License

MIT
