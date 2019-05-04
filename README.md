# hashicorp-vault cookbook

[![Cookbook Version](https://img.shields.io/cookbook/v/hashicorp-vault.svg)](https://supermarket.chef.io/cookbooks/hashicorp-vault)
[![Build Status](https://img.shields.io/circleci/project/github/sous-chefs/vault/master.svg)](https://circleci.com/gh/sous-chefs/vault)

[Application cookbook][0] for installing and configuring [Hashicorp Vault][1].

Vault is a tool, which when used properly, manages secure manage to
secrets for your infrastructure.

## Platform Support
The following platforms have been certified with integration tests
using Test Kitchen:

- CentOS (RHEL) 6.8, 7.2
- Ubuntu 12.04, 14.04, 16.04

## Basic Usage
This cookbook was designed from the ground up to make it dead simple
to install and configure the [Vault daemon][1] as a system service
using Chef. It highlights several of our best practices for developing
reusable infrastructure at Bloomberg.

This cookbook provides three sets of
[node attributes](attributes/default.rb) which can be used to fine
tune the default recipe which installs and configures Vault. The
values from these node attributes are fed directly into the custom
resources.

This cookbook can be added to the run list of all of the nodes that
you want to be part of the cluster. But the best way to use this is in
a [wrapper cookbook][2] which sets up a backend, and potentially even
TLS certificates. We provide an example [Vault Cluster cookbook][3]
which uses our [Consul cookbook][4] for a highly-available
storage solution.

[0]: http://blog.vialstudios.com/the-environment-cookbook-pattern/#thelibrarycookbook
[1]: https://www.vaultproject.io
[2]: http://blog.vialstudios.com/the-environment-cookbook-pattern/#thewrappercookbook
[3]: https://github.com/johnbellone/vault-cluster-cookbook
[4]: https://github.com/sous-chefs/consul
[5]: https://github.com/chef-cookbooks/chef-vault


## Contributors

This project exists thanks to all the people who contribute.
<img src="https://opencollective.com/sous-chefs/contributors.svg?width=890&button=false" /></a>


### Backers

Thank you to all our backers! 🙏 [[Become a backer](https://opencollective.com/sous-chefs#backer)]
<a href="https://opencollective.com/sous-chefs#backers" target="_blank"><img src="https://opencollective.com/sous-chefs/backers.svg?width=890"></a>

### Sponsors

Support this project by becoming a sponsor. Your logo will show up here with a link to your website. [[Become a sponsor](https://opencollective.com/sous-chefs#sponsor)]
<a href="https://opencollective.com/sous-chefs/sponsor/0/website" target="_blank"><img src="https://opencollective.com/sous-chefs/sponsor/0/avatar.svg"></a>
<a href="https://opencollective.com/sous-chefs/sponsor/1/website" target="_blank"><img src="https://opencollective.com/sous-chefs/sponsor/1/avatar.svg"></a>
<a href="https://opencollective.com/sous-chefs/sponsor/2/website" target="_blank"><img src="https://opencollective.com/sous-chefs/sponsor/2/avatar.svg"></a>
<a href="https://opencollective.com/sous-chefs/sponsor/3/website" target="_blank"><img src="https://opencollective.com/sous-chefs/sponsor/3/avatar.svg"></a>
<a href="https://opencollective.com/sous-chefs/sponsor/4/website" target="_blank"><img src="https://opencollective.com/sous-chefs/sponsor/4/avatar.svg"></a>
<a href="https://opencollective.com/sous-chefs/sponsor/5/website" target="_blank"><img src="https://opencollective.com/sous-chefs/sponsor/5/avatar.svg"></a>
<a href="https://opencollective.com/sous-chefs/sponsor/6/website" target="_blank"><img src="https://opencollective.com/sous-chefs/sponsor/6/avatar.svg"></a>
<a href="https://opencollective.com/sous-chefs/sponsor/7/website" target="_blank"><img src="https://opencollective.com/sous-chefs/sponsor/7/avatar.svg"></a>
<a href="https://opencollective.com/sous-chefs/sponsor/8/website" target="_blank"><img src="https://opencollective.com/sous-chefs/sponsor/8/avatar.svg"></a>
<a href="https://opencollective.com/sous-chefs/sponsor/9/website" target="_blank"><img src="https://opencollective.com/sous-chefs/sponsor/9/avatar.svg"></a>
