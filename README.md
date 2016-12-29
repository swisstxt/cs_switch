# cs_switch

cs_switch helps you with generating SQL queries required to change the domain of CloudStack compute offerings.

## Dependencies

  * Ruby
  * bundler gem

## Getting started

Make sure you have a working cloudstack-cli configuration file in your homedir.
Usually this is found under `~/.cloudstack-cli.yml`

Install gem dependencies:
`bundle install`

Run the CLI to generate SQL update statements (example):
`bin/cs_switch sql --source-domain Testdomain --limit 1cpu_1gb`
