<!--


  ** DO NOT EDIT THIS FILE
  **
  ** 1) Make all changes to `README.yaml`
  ** 2) Run`make readme` to rebuild this file.
  **
  ** (We maintain HUNDREDS of open source projects. This is how we maintain our sanity.)
  **


  -->

# terraform-pagerduty-user

[![GitHub tag (latest SemVer)](https://img.shields.io/github/v/tag/inetum-peru/terraform-pagerduty-user?label=latest&sort=semver)](https://github.com/inetum-peru/terraform-pagerduty-user/releases) [![Latest Release](https://img.shields.io/github/release/inetum-peru/terraform-pagerduty-user)](https://github.com/inetum-peru/terraform-pagerduty-user/releases) [![Lint](https://img.shields.io/github/workflow/status/inetum-peru/terraform-pagerduty-user/lint-code)](https://github.com/inetum-peru/terraform-pagerduty-user/actions) [![Issues](https://img.shields.io/github/issues/inetum-peru/terraform-pagerduty-user)](https://github.com/inetum-peru/terraform-pagerduty-user/issues) [![Conventional Commits](https://img.shields.io/badge/Conventional%20Commits-1.0.0-yellow)](https://conventionalcommits.org) [![KeepAChangelog](https://img.shields.io/badge/Keep%20A%20Changelog-1.0.0-%23E05735)](https://keepachangelog.com)

terraform-pagerduty-user for project

```hcl
  module "main" {
    source = "inetum-peru/user/pagerduty"
    version = "0.0.0"
    source = "github"
    email = "bot@gmail.com"
    mobile = "51943876543"
    name = "test name"
  }
```

Full working examples can be found in [examples](./examples) folder.

## Examples

### common

 <!-- BEGIN_TF_DOCS -->

## Requirements

| Name                                                                     | Version |
| ------------------------------------------------------------------------ | ------- |
| <a name="requirement_terraform"></a> [terraform](#requirement_terraform) | >= 0.13 |
| <a name="requirement_pagerduty"></a> [pagerduty](#requirement_pagerduty) | >=1.9.6 |

## Providers

| Name                                                               | Version |
| ------------------------------------------------------------------ | ------- |
| <a name="provider_pagerduty"></a> [pagerduty](#provider_pagerduty) | >=1.9.6 |

## Modules

No modules.

## Resources

| Name | Type |
| --- | --- |
| [pagerduty_user.this](https://registry.terraform.io/providers/PagerDuty/pagerduty/latest/docs/resources/user) | resource |
| [pagerduty_user_contact_method.email](https://registry.terraform.io/providers/PagerDuty/pagerduty/latest/docs/resources/user_contact_method) | resource |
| [pagerduty_user_contact_method.phone](https://registry.terraform.io/providers/PagerDuty/pagerduty/latest/docs/resources/user_contact_method) | resource |

## Inputs

| Name                                                | Description        | Type     | Default | Required |
| --------------------------------------------------- | ------------------ | -------- | ------- | :------: |
| <a name="input_email"></a> [email](#input_email)    | email of user      | `string` | n/a     |   yes    |
| <a name="input_mobile"></a> [mobile](#input_mobile) | nro mobile of user | `string` | n/a     |   yes    |
| <a name="input_name"></a> [name](#input_name)       | name of user       | `string` | n/a     |   yes    |

## Outputs

| Name                                                     | Description   |
| -------------------------------------------------------- | ------------- |
| <a name="output_user"></a> [user](#output_user)          | instance user |
| <a name="output_user_id"></a> [user_id](#output_user_id) | instance user |

<!-- END_TF_DOCS -->

## Help

**Got a question?**

File a GitHub [issue](https://github.com/inetum-peru/terraform-pagerduty-user/issues).

## Contributing

### Bug Reports & Feature Requests

Please use the [issue tracker](https://github.com/inetum-peru/terraform-pagerduty-user/issues) to report any bugs or file feature requests.

### Development

In general, PRs are welcome. We follow the typical "fork-and-pull" Git workflow.

1.  **Fork** the repo on GitHub
2.  **Clone** the project to your own machine
3.  **Commit** changes to your own branch
4.  **Push** your work back up to your fork
5.  Submit a **Pull Request** so that we can review your changes

**NOTE:** Be sure to rebase the latest changes from "upstream" before making a pull request!

## Module Versioning

This Module follows the principles of [Semantic Versioning (SemVer)](https://semver.org/).

Using the given version number of `MAJOR.MINOR.PATCH`, we apply the following constructs:

1. Use the `MAJOR` version for incompatible changes.
1. Use the `MINOR` version when adding functionality in a backwards compatible manner.
1. Use the `PATCH` version when introducing backwards compatible bug fixes.

### Backwards compatibility in `0.0.z` and `0.y.z` version

- In the context of initial development, backwards compatibility in versions `0.0.z` is **not guaranteed** when `z` is increased. (Initial development)
- In the context of pre-release, backwards compatibility in versions `0.y.z` is **not guaranteed** when `y` is increased. (Pre-release)

## Copyrights

Copyright © 2018-2021 [inetum](http://www.gfiworld.com.pe)

## Trademarks

All other trademarks referenced herein are the property of their respective owners.

## License

The code and styles are licensed under the LGPL-3.0 license [See project license.](LICENSE).

## Don't forget to 🌟 Star 🌟 the repo if you like terraform-pagerduty-user

[Your feedback is appreciated](https://github.com/inetum-peru/terraform-pagerduty-user/issues)
