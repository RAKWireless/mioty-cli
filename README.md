# Miro EdgeCard for Mioty setup script

This is a CLI script to setup and manage Miromico's Miro EgdeCard for Mioty.

## Quick Start Guide

Users can use remote bash execution script to install/upgrade mioty-cli.

To install:

`curl https://raw.githubusercontent.com/RAKWireless/mioty-cli/master/mioty-cli -sSf | bash -s -- install`


After the installation/upgrade is finished, users can use the command `mioty-cli` to get a list of available options. 

```
rak@rakpios:~ $ mioty-cli

Mioty CLI
Utility to configure and manage Miromico's Miro EdgeCard for Mioty board.

Host configuration:

  mioty-cli setup                --> setups connection and firewall rules
  mioty-cli remove               --> deletes connection
  mioty-cli up                   --> brings up connection to edge card
  mioty-cli down                 --> brings down connection to edge card

Edge card configuration:

  mioty-cli start                --> starts base station
  mioty-cli stop                 --> stops base station
  mioty-cli restart              --> restarts base station
  mioty-cli enable               --> enables base station on boot by default
  mioty-cli disable              --> disables base station on boot by default
  mioty-cli getall               --> gets params from builtin packer forwarder
  mioty-cli set <param> <value>  --> sets a param of the builtin packer forwarder
  mioty-cli cert <file>          --> pushes a certificate file to card
  mioty-cli reset                --> resets base station params to factory values

Tool management:

  mioty-cli version              --> show the currest script version
  mioty-cli install              --> installs tool to user path
  mioty-cli update               --> updates tool to the latest version
  mioty-cli credentials          --> shows default credentials based on uniqueBaseStationId

```
