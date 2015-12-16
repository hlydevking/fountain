# How to contribute
Please contribute to this repository if any of the following is true:
* You have expertise in community development, communication, or education
* You want open source communities to be more collaborative and inclusive
* You want to help lower the burden to first time contributors

### Issues
Before you submit your issue search the archive, maybe your question was already answered.

Because we create a generator you should be specific as possible in your requests. Providing the following information will increase the chances of your issue being dealt with quickly:
* Any sample code **SHOULD BE** included in [code blocks](https://help.github.com/articles/github-flavored-markdown/#fenced-code-blocks)
* **.yo-rc.json** - A copy of your `.yo-rc.json` is highly appreciated.
* **Generator Version** - is it a regression?
* **Overview of the Issue** - if an error is being thrown a non-minified stack trace helps
* **Motivation for or Use Case** - explain why this is a bug for you
* **Browsers and Operating System** - is this a problem with all browsers or only IE8?
* **Reproduce the Error** - provide a GitHub repo of a non (or slightly) modified generated project or an unambiguous set of steps.
* **Related Issues** - has a similar issue been reported before?
* **Suggest a Fix** - if you can't fix the bug yourself, perhaps you can point to what might be
  causing the problem (line of code or commit)

### Build from sources
If you're willing to work on a Pull Request, you'll have to install the generator locally. As the generator is based on the composition of a lot of small generators, this can be not necessarily obvious.

More informations in [DESIGN.md](DESIGN.md).

The main principle is to use the [npm link](https://docs.npmjs.com/cli/link) which allows you to install globally your source version of a module and to link a specific dependency from a module to your source in place of a local copy.

To work on fountain generators, you have to clone the projects and publish them locally with `npm link`. You'll also need no link each others with `npm link <dep>`. This is a bit tedious but has to be done only once.

### Pull Requests
Before you submit your pull request consider the following guidelines:

**Test**  
Test environment is not ready yet. We hope it will be ready soon.

**Style Guide**  
Please brief yourself on [Idiomatic.js](https://github.com/rwldrn/idiomatic.js) style guide with two space indent. Also, ESLint is configured in each project, please submit code which doesn't raise any warning.

**Documentation**  
Add documentation for every new feature, directory structure change. Feel free to send corrections or better docs!

**Branch**  
Must be one of the following:

* feat: A new feature
* fix: A bug fix
* docs: Documentation only changes
* style: Changes that do not affect the meaning of the code (white-space, formatting, missing semi-colons, etc)
* refactor: A code change that neither fixes a bug or adds a feature
* perf: A code change that improves performance
* test: Adding missing tests
* chore: Changes to the build process or auxiliary tools and libraries such as documentation generation

### Donations

If you like this project, if you want a faster development, if you feel generous, donation is a great way to motivate us more. Be noticed that all donations will be spread amongst core contributors.

However please note that no donations will influence an issue resolution or a design choice.

[![Gratipay](http://img.shields.io/gratipay/Swiip.svg?style=flat)](https://gratipay.com/Swiip/)
[![Paypal](http://img.shields.io/badge/paypal-donate-yellow.svg?style=flat)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=FWGV3KKGH2D4S)
