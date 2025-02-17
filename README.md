# saf-development-lab-environment

This lab is a GitHub environment that makes it quick and easy for you to start learning and working on executing your own InSpec profiles.

## Overview of the Lab

The repository is setup to be very low overhead, we use a simple `build-lab.sh` script to quickly add the tools you need to get started easily, along with two containers to act as testing targets. You can modify this as needed when working in your codespace, but remember to use git configuration management if you need to persist changes beyond the life of one Codespace.

## Lab Components

- CodeSpaces Linux Base Community Image
  - <https://github.com/microsoft/vscode-dev-containers/tree/main/containers/codespaces-linux>
- InSpec Omnitruck install of the latest InSpec
  - `curl https://omnitruck.chef.io/install.sh | sudo bash -s -- -c stable -P inspec`
- MITRE SAF CLI
  - <https://saf-cli.mitre.org>
  - <https://github.com/mitre/saf>
- MITRE Heimdall Lite
  - <https://heimdall-lite.mitre.org>
  - <https://github.com/mitre/heimdall2>
- Docker Compose File which starts:
  - RedHat UBI8 Container
  - NGINX Web Server Container

## Using the Lab

Refer to the instructions [here](https://mitre.github.io/saf-training/resources/02.html#instructions) as a start. More information will be added specific to the development lab environment.

## Adding Services and Software

Your repository is yours to command, you have full `sudo` access and can install any software or services you like, run databases, web-servers, etc. and expose any ports that you might need to do your work.

## Creating a Pull Request

<https://www.digitalocean.com/community/tutorials/how-to-create-a-pull-request-on-github>

Go for it and if for some reason you break your environment, just start a new one.

### NOTICE

© 2018-2025 The MITRE Corporation.

Approved for Public Release; Distribution Unlimited. Case Number 18-3678.

### NOTICE

MITRE hereby grants express written permission to use, reproduce, distribute, modify, and otherwise leverage this software to the extent permitted by the licensed terms provided in the LICENSE.md file included with this project.

### NOTICE

This software was produced for the U. S. Government under Contract Number HHSM-500-2012-00008I, and is subject to Federal Acquisition Regulation Clause 52.227-14, Rights in Data-General.

No other use other than that granted to the U. S. Government, or to those acting on behalf of the U. S. Government under that Clause is authorized without the express written permission of The MITRE Corporation.

For further information, please contact The MITRE Corporation, Contracts Management Office, 7515 Colshire Drive, McLean, VA 22102-7539, (703) 983-6000.
