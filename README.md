[![New Relic Experimental header](https://github.com/newrelic/opensource-website/raw/master/src/images/categories/Experimental.png)](https://opensource.newrelic.com/oss-category/#new-relic-experimental)

# New Relic Instruqt

This repository houses the artifacts and source code behind the tracks found in the [New Relic team](https://play.instruqt.com/newrelic#tracks) on the [Instruqt](https://instruqt.com/) training platform.

**Nomenclature:**
* `Track` = Workshop
* A track consist of multiple `challenges`
  
## Getting started
* Create an account at [Instruqt](https://instruqt.com/)
* Install the [Instruqt CLI](https://docs.instruqt.com/getting-started/software-development-kit-sdk)
* Use the Instruqt web interface to [create a track](https://docs.instruqt.com/creating-content/tutorials/building-your-first-track#step-01-create-new-track)
* [Pull your track locally with the CLI](https://docs.instruqt.com/creating-content/tutorials/building-your-first-track#step-03-pull-your-track)

## Organize your track
* In this repository, create a new folder under `tracks/` for your workshop
* Re-usable assets are located under the top folder `assets/`
* If you need a custom screenshot, icon, yaml,... create an `assets/` folder in your track. For example `nerd-days-1-0-k8s/assets/`
* You can reference assets in your Markdown by using a GitHub link, for example: `![Kubernetes maturity model](https://github.com/newrelic-experimental/newrelic-instruqt/blob/master/tracks/nerd-days-k8s/assets/png/maturity-model.png?raw=true)`

## Tips
* Use a [setup script](https://docs.instruqt.com/configuration/challenge-lifecycle-scripts/setup) to prepare your environment. For example you can download a file, install a package, etc.
* Use a [check script](https://docs.instruqt.com/configuration/challenge-lifecycle-scripts/check) to validate if a user did the correct steps.
* Use three backticks (including a newline after the first three) for pre-formatted code, so that the quick copy-paste icon gets shown on the block
* Get familiar with the Instruqt web interface first, then use the [Instruqt CLI](https://docs.instruqt.com/getting-started/software-development-kit-sdk) to sync your Instruqt track on your machine and contribute it to this repository.
* Use multiple notes, particularly when challenge setup takes some time. Use the notes to explain what is being set up, and what is going to happen in the challenge.
* Use images to call out important detail, Instruqt supports [GitHub flavored markdown](https://github.github.com/gfm/)

## Support

New Relic has open-sourced this project. This project is provided AS-IS WITHOUT WARRANTY OR DEDICATED SUPPORT. Issues and contributions should be reported to the project here on GitHub.

## Privacy
At New Relic we take your privacy and the security of your information seriously, and are committed to protecting your information. We must emphasize the importance of not sharing personal data in public forums, and ask all users to scrub logs and diagnostic information for sensitive information, whether personal, proprietary, or otherwise.

We define “Personal Data” as any information relating to an identified or identifiable individual, including, for example, your name, phone number, post code or zip code, Device ID, IP address, and email address.

For more information, review [New Relic’s General Data Privacy Notice](https://newrelic.com/termsandconditions/privacy).

## Contribute

We encourage your contributions to improve New Relic Instruqt! Keep in mind that when you submit your pull request, you'll need to sign the CLA via the click-through using CLA-Assistant. You only have to sign the CLA one time per project.

If you have any questions, or to execute our corporate CLA (which is required if your contribution is on behalf of a company), drop us an email at opensource@newrelic.com.

**A note about vulnerabilities**

As noted in our [security policy](../../security/policy), New Relic is committed to the privacy and security of our customers and their data. We believe that providing coordinated disclosure by security researchers and engaging with the security community are important means to achieve our security goals.

If you believe you have found a security vulnerability in this project or any of New Relic's products or websites, we welcome and greatly appreciate you reporting it to New Relic through [HackerOne](https://hackerone.com/newrelic).

If you would like to contribute to this project, review [these guidelines](./CONTRIBUTING.md).

To [all contributors](https://github.com/newrelic-experimental/newrelic-instruqt/graphs/contributors), we thank you!  Without your contribution, this project would not be what it is today.

## License
New Relic Instruqt is licensed under the [Apache 2.0](http://apache.org/licenses/LICENSE-2.0.txt) License.
>[If applicable: [Project Name] also uses source code from third-party libraries. You can find full details on which libraries are used and the terms under which they are licensed in the third-party notices document.]