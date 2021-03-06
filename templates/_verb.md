# {%= name %} [![npm version][npmv-img]][npmv-url] [![github release][ghrelease-img]][ghrelease-url] [![License][license-img]][license-url]

> {%= description %}

Please consider following this project's author, [<%= author.name %>](https://github.com/<%= author.login %>), and :star: the project to show your :heart: and support.

<div id="thetop"></div>

[![Code style][codestyle-img]][codestyle-url]
[![CircleCI linux build][linuxbuild-img]][linuxbuild-url]
[![CodeCov coverage status][codecoverage-img]][codecoverage-url]
[![DavidDM dependency status][dependencies-img]][dependencies-url]
[![Renovate App Status][renovateapp-img]][renovateapp-url]
[![Time Since Last Commit][last-commit-img]][last-commit-url]
[![Make A Pull Request][prs-welcome-img]][prs-welcome-url]
<!-- [![Semantically Released][standard-release-img]][standard-release-url] -->

If you have any _how-to_ kind of questions, please read the [Contributing Guide](./CONTRIBUTING.md) and [Code of Conduct](./CODE_OF_CONDUCT.md) documents.  
For bugs reports and feature requests, [please create an issue][open-issue-url] or ping
[@tunnckoCore](https://twitter.com/tunnckoCore) at Twitter.

[![Conventional Commits][ccommits-img]][ccommits-url]
[![Minimum Required Nodejs][nodejs-img]][npmv-url]
[![NPM Downloads Monthly][downloads-monthly-img]][npmv-url]
[![NPM Downloads Total][downloads-total-img]][npmv-url]
[![Share Love Tweet][shareb]][shareu]
[![Twitter][twitter-img]][twitter-url]

Project is [semantically](https://semver.org) versioned & automatically released through [CircleCI](https://circleci.com) with [Standard Release][standard-release-url].

[![Become a Patron][patreon-img]][patreon-url]
[![Buy me a Kofi][kofi-img]][kofi-url]
[![PayPal Donation][paypal-img]][paypal-url]
[![Bitcoin Coinbase][bitcoin-img]][bitcoin-url]
[![Keybase PGP][keybase-img]][keybase-url]

<!-- 

![consulting_email][consulting_email] - _Consulting, professional support, personal or team training_  
![licensing_email][licensing_email] - _Any licensing questions, like private or commerical use of modifications_  
![ceo_email][ceo_email] - _For critical problems, security reports, partnering and sponsoring_  

-->

| Topic | Contact |
| :-- | --: |
| Any legal or licensing questions, like private or commerical use | ![tunnckocore_legal][tunnckocore_legal] |
| For any critical problems and security reports | ![tunnckocore_security][tunnckocore_security] | 
| Consulting, professional support, personal or team training | ![tunnckocore_consulting][tunnckocore_consulting] |
| For any questions about Open Source, partnerships and sponsoring | ![tunnckocore_opensource][tunnckocore_opensource] |
| Curited interesting news, announcements, articles, and thoughts | ![tunnckocore_newsletter][tunnckocore_newsletter] |

<!-- Logo when needed:

<p align="center">
  <a href="https://github.com/<%= repository %>">
    <img src="./media/logo.png" width="85%">
  </a>
</p>

-->

## Table of Contents

<!-- toc -->

## Install

This project requires [**Node.js**](https://nodejs.org) **{%= engines.node %}** _(see [Support & Release Policy](https://github.com/tunnckoCoreLabs/support-release-policy))_. Install it using
[**yarn**](https://yarnpkg.com) or [**npm**](https://npmjs.com).  
_We highly recommend to use Yarn when you think to contribute to this project._

```bash
$ yarn add {%= name %}
```

## API

<!-- docks-start -->
<!-- docks-end -->

**[back to top](#thetop)**

{% if (verb.related && verb.related.list && verb.related.list.length) { %}

## See Also

Some of these projects are used here or were inspiration for this one, others are just related. So, thanks for your existance!

{%= related(verb.related.list, { words: 10 }) %}

**[back to top](#thetop)**
{% } %}

## Contributing

### Guides and Community

Please read the [Contributing Guide](./CONTRIBUTING.md) and [Code of Conduct](./CODE_OF_CONDUCT.md) documents for advices.

For bug reports and feature requests, please join our [community][community-url] forum and open a thread there with prefixing the title of the thread with the name of the project if there's no separate channel for it.

Consider reading the [Support and Release Policy](https://github.com/tunnckoCoreLabs/support-release-policy) guide if you are interested in what are the supported Node.js versions and how we proceed. In short, we support latest two even-numbered Node.js release lines.

### Support the project

[Become a Partner or Sponsor?][patreon-url] :dollar: Check the **Partner**, **Sponsor** or **Omega-level** tiers! :tada: You can get your company logo, link & name on this file. It's also rendered on package page in [npmjs.com][npmv-url] and [yarnpkg.com](https://yarnpkg.com/en/package/{%= name %}) sites too! :rocket:

Not financial support? Okey! [Pull requests](https://github.com/tunnckoCoreLabs/contributing#opening-a-pull-request), stars and all kind of [contributions](https://opensource.guide/how-to-contribute/#what-it-means-to-contribute) are always
welcome. :sparkles:

### OPEN Open Source

This project is following [OPEN Open Source](http://openopensource.org) model

> Individuals making significant and valuable contributions are given commit-access to the project to contribute as they see fit. This project is built on collective efforts and it's not strongly guarded by its founders.

There are a few basic ground-rules for its contributors

1. Any **significant modifications** must be subject to a pull request to get feedback from other contributors.
2. [Pull requests](https://github.com/tunnckoCoreLabs/contributing#opening-a-pull-request) to get feedback are _encouraged_ for any other trivial contributions, but are not required.
3. Contributors should attempt to adhere to the prevailing code-style and development workflow.

### Wonderful Contributors

Thanks to the hard work of these wonderful people this project is alive! It follows the
[all-contributors](https://github.com/kentcdodds/all-contributors) specification.  
Don't hesitate to add yourself to that list if you have made any contribution! ;) [See how,
here](https://github.com/jfmengels/all-contributors-cli#usage).

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore -->
| [<img src="<%= author.avatar %>" width="120px;"/><br /><sub><b><%= author.name %></b></sub>](<%= author.url %>)<br />[💻](https://github.com/<%= repository %>/commits?author=<%= author.login %> "Code") [📖](https://github.com/<%= repository %>/commits?author=<%= author.login %> "Documentation") [💬](#question-<%= author.login %> "Answering Questions") [👀](#review-<%= author.login %> "Reviewed Pull Requests") [🔍](#fundingFinding-<%= author.login %> "Funding Finding") |
| :---: |

<!-- ALL-CONTRIBUTORS-LIST:END -->

Consider showing your [support](#support-the-project) to them. :sparkling_heart:

## License

Copyright (c) <%= license.year %>-present, [<%= author.name %>](<%= author.url %>) `<<%= author.email %>>` & [contributors](#wonderful-contributors).  
Released under the [<%= license.name %> License][license-url].


<!-- Heading badges -->

[npmv-url]: https://www.npmjs.com/package/{%= name %}
[npmv-img]: https://badgen.net/npm/v/{%= name %}?icon=npm

[nodejs-img]: https://badgen.net/npm/node/{%= name %}

[ghrelease-url]: https://github.com/<%= repository %>/releases/latest
[ghrelease-img]: https://badgen.net/github/release/<%= repository %>?icon=github

[license-url]: https://github.com/<%= repository %>/blob/master/LICENSE
[license-img]: https://badgen.net/npm/license/{%= name %}

<!-- Front line badges -->

[codestyle-url]: https://github.com/airbnb/javascript
[codestyle-img]: https://badgen.net/badge/code%20style/airbnb/ff5a5f?icon=airbnb

[linuxbuild-url]: https://circleci.com/gh/<%= repository %>/tree/master
[linuxbuild-img]: https://badgen.net/circleci/github/<%= repository %>/master?label=build&icon=circleci

[codecoverage-url]: https://codecov.io/gh/<%= repository %>
[codecoverage-img]: https://badgen.net/codecov/c/github/<%= repository %>?icon=codecov

[dependencies-url]: https://david-dm.org/<%= repository %>
[dependencies-img]: https://badgen.net/david/dep/<%= repository %>?label=deps

[ccommits-url]: https://conventionalcommits.org/
[ccommits-img]: https://badgen.net/badge/conventional%20commits/v1.0.0/dfb317

[standard-release-url]: https://github.com/standard-release/standard-release
[standard-release-img]: https://badgen.net/badge/semantically/released/05c5ff

[community-img]: https://badgen.net/badge/join/community/7b16ff
[community-url]: https://github.com/tunnckocorehq/community

[last-commit-img]: https://badgen.net/github/last-commit/<%= repository %>/master
[last-commit-url]: https://github.com/<%= repository %>/commits/master

[downloads-weekly-img]: https://badgen.net/npm/dw/{%= name %}?icon=npm
[downloads-monthly-img]: https://badgen.net/npm/dm/{%= name %}?icon=npm
[downloads-total-img]: https://badgen.net/npm/dt/{%= name %}?icon=npm

[renovateapp-url]: https://renovatebot.com
[renovateapp-img]: https://badgen.net/badge/renovate/enabled/green

[prs-welcome-img]: https://badgen.net/badge/PRs/welcome/green
[prs-welcome-url]: http://makeapullrequest.com

<!-- TODO: update icon -->
[paypal-url]: https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=HYJJEZNSGAPGC&source=url
[paypal-img]: https://badgen.net/badge/PayPal/donate/003087?icon=https://simpleicons.now.sh/paypal/fff

<!-- TODO: update icon -->
[kofi-url]: https://ko-fi.com/tunnckoCore
[kofi-img]: https://badgen.net/badge/Buy%20me/a%20coffee/29abe0c2?icon=https://rawcdn.githack.com/tunnckoCore/badgen-icons/f8264c6414e0bec449dd86f2241d50a9b89a1203/icons/kofi.svg

<!-- TODO: update icon -->
[bitcoin-url]: https://www.blockchain.com/btc/payment_request?address=3QNHKun1K1SUui1b4Z3KEGPPsWC1TgtnqA&message=Open+Source+Software&amount_local=10&currency=USD
[bitcoin-img]: https://badgen.net/badge/Bitcoin%20tip/3QNHKun...b4Z3KEGPPsWC1TgtnqA/yellow?icon=https://simpleicons.now.sh/bitcoin/fff

[keybase-url]: https://keybase.io/<%= author.login %>
[keybase-img]: https://badgen.net/keybase/pgp/<%= author.login %>

[twitter-url]: https://twitter.com/<%= author.login %>
[twitter-img]: https://badgen.net/twitter/follow/<%= author.login %>?icon=twitter&color=1da1f2

[patreon-url]: https://www.patreon.com/bePatron?u=5579781
[patreon-img]: https://badgen.net/badge/Become/a%20patron/F96854?icon=patreon
<!-- [patreon-img]: https://badgen.net/badge/Patreon/tunnckoCore/F96854?icon=patreon -->
[patreon-sponsor-img]: https://badgen.net/badge/become/a%20sponsor/F96854?icon=patreon

[shareu]: https://twitter.com/intent/tweet?text=https://github.com/<%= repository %>&via=<%= author.twitter %>
[shareb]: https://badgen.net/badge/twitter/share/1da1f2?icon=twitter

[open-issue-url]: https://github.com/<%= repository %>/issues/new

[tunnckocore_legal]: https://badgen.net/https/liam-badge-daknys6gadky.runkit.sh/com/legal/tunnckocore?label&color=A56016&icon=https://svgshare.com/i/Dt6.svg
[tunnckocore_consulting]: https://badgen.net/https/liam-badge-daknys6gadky.runkit.sh/com/consulting/tunnckocore?label&color=07ba96&icon=https://svgshare.com/i/Dt6.svg
[tunnckocore_security]: https://badgen.net/https/liam-badge-daknys6gadky.runkit.sh/com/security/tunnckocore?label&color=ed1848&icon=https://svgshare.com/i/Dt6.svg
[tunnckocore_opensource]: https://badgen.net/https/liam-badge-daknys6gadky.runkit.sh/com/opensource/tunnckocore?label&color=ff7a2f&icon=https://svgshare.com/i/Dt6.svg
[tunnckocore_newsletter]: https://badgen.net/https/liam-badge-daknys6gadky.runkit.sh/com/newsletter/tunnckocore?label&color=5199FF&icon=https://svgshare.com/i/Dt6.svg
