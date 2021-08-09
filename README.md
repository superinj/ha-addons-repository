# Community Hass.io Add-ons for Home Assistant

![Project Stage][project-stage-shield]
![Maintenance][maintenance-shield]
[![License][license-shield]](LICENSE.md)

[![GitLab CI][gitlabci-shield]][gitlabci]
[![Awesome][awesome-shield]][awesome]

[![Discord][discord-shield]][discord]
[![Community Forum][forum-shield]][forum]

## About

Hass.io allows anyone to create add-on repositories to share their add-ons for
Hass.io easily. This repository is one of those repositories, providing extra
Home Assistant add-ons for your Hass.io installation.

The primary goal of this project is to provide you (as a Hass.io /
Home Assistant user) with additional, high quality, add-ons that allow you to
take your automated home to the next level.

## Installation

Adding this add-ons repository to your Hass.io Home Assistant instance is
pretty easy. Follow [the official instructions][third-party-addons] on the
website of Home Assistant, and use the following URL:

```txt
https://github.com/superinj/ha-addons-repository
```

## Add-ons provided by this repository

### &#10003; [btalarm2mqtt][addon-btalarm2mqtt]

![Latest Version][btalarm2mqtt-version-shield]
![Supports armhf Architecture][btalarm2mqtt-armhf-shield]
![Supports armv7 Architecture][btalarm2mqtt-armv7-shield]
![Supports aarch64 Architecture][btalarm2mqtt-aarch64-shield]
![Supports amd64 Architecture][btalarm2mqtt-amd64-shield]
![Supports i386 Architecture][btalarm2mqtt-i386-shield]
![Docker Pulls][btalarm2mqtt-pulls-shield]

Gateway to Bticino Alarm

[:books: btalarm2mqtt add-on documentation][addon-doc-btalarm2mqtt]

### &#10003; [own2mqtt][addon-own2mqtt]

![Latest Version][own2mqtt-version-shield]
![Supports armhf Architecture][own2mqtt-armhf-shield]
![Supports armv7 Architecture][own2mqtt-armv7-shield]
![Supports aarch64 Architecture][own2mqtt-aarch64-shield]
![Supports amd64 Architecture][own2mqtt-amd64-shield]
![Supports i386 Architecture][own2mqtt-i386-shield]
![Docker Pulls][own2mqtt-pulls-shield]

Client to OpenWebNet Server

[:books: own2mqtt add-on documentation][addon-doc-own2mqtt]

## Releases

Releases are based on [Semantic Versioning][semver], and use the format
of ``MAJOR.MINOR.PATCH``. In a nutshell, the version will be incremented
based on the following:

- ``MAJOR``: Incompatible or major changes.
- ``MINOR``: Backwards-compatible new features and enhancements.
- ``PATCH``: Backwards-compatible bugfixes and package updates.

## Support

Got questions?

You have several options to get them answered:

- The Community Hass.io Add-ons [Discord Chat Server][discord]
- The Home Assistant [Community Forum][forum].
- The Home Assistant [Discord Chat Server][discord-ha].
- Join the [Reddit subreddit][reddit] in [/r/homeassistant][reddit]

You could also open an issue here on GitHub. Note, we use a separate
GitHub repository for each add-on. Please ensure you are creating the issue
on the correct GitHub repository matching the add-on.

- [Open an issue for the add-on: btalarm2mqtt][btalarm2mqtt-issue]
- [Open an issue for the add-on: own2mqtt][own2mqtt-issue]

For a general repository issue or add-on ideas [open an issue here][issue]

## Contributing

This is an active open-source project. We are always open to people who want to
use the code or contribute to it.

We have set up a separate document containing our
[contribution guidelines](CONTRIBUTING.md).

Thank you for being involved! :heart_eyes:

## Adding a new add-on

Have you created an add-on that you want to list in the Community Repository?
Contact [Franck Nijhof][frenck]:

- Drop him an email: frenck@addons.community
- Chat with him on [Discord Chat][discord]
- Message him via the forums: [frenck][forum-frenck]

He will set up a GitHub repository and all the other plumbing,
and of course, give you developer access to your contribution.

## License

MIT License

Copyright (c) 2017-2020 Franck Nijhof

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

[addon-btalarm2mqtt]: https://github.com/superinj/addon-btalarm2mqtt/tree/v0.1.3
[addon-doc-btalarm2mqtt]: https://github.com/superinj/addon-btalarm2mqtt/blob/v0.1.3/README.md
[btalarm2mqtt-issue]: https://github.com/superinj/addon-btalarm2mqtt/issues
[btalarm2mqtt-version-shield]: https://img.shields.io/badge/version-v0.1.3-blue.svg
[btalarm2mqtt-pulls-shield]: https://img.shields.io/docker/pulls/superinj/armhf-btalarm2mqtt.svg
[btalarm2mqtt-aarch64-shield]: https://img.shields.io/badge/aarch64-yes-green.svg
[btalarm2mqtt-amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg
[btalarm2mqtt-armhf-shield]: https://img.shields.io/badge/armhf-yes-green.svg
[btalarm2mqtt-armv7-shield]: https://img.shields.io/badge/armv7-yes-green.svg
[btalarm2mqtt-i386-shield]: https://img.shields.io/badge/i386-yes-green.svg
[addon-own2mqtt]: https://github.com/superinj/addon-own2mqtt/tree/v0.3.3
[addon-doc-own2mqtt]: https://github.com/superinj/addon-own2mqtt/blob/v0.3.3/README.md
[own2mqtt-issue]: https://github.com/superinj/addon-own2mqtt/issues
[own2mqtt-version-shield]: https://img.shields.io/badge/version-v0.3.3-blue.svg
[own2mqtt-pulls-shield]: https://img.shields.io/docker/pulls/superinj/armhf-own2mqtt.svg
[own2mqtt-aarch64-shield]: https://img.shields.io/badge/aarch64-yes-green.svg
[own2mqtt-amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg
[own2mqtt-armhf-shield]: https://img.shields.io/badge/armhf-yes-green.svg
[own2mqtt-armv7-shield]: https://img.shields.io/badge/armv7-yes-green.svg
[own2mqtt-i386-shield]: https://img.shields.io/badge/i386-yes-green.svg
[awesome-shield]: https://img.shields.io/badge/awesome%3F-yes-brightgreen.svg
[awesome]: https://awesome-ha.com
[discord-ha]: https://discord.gg/c5DvZ4e
[discord-shield]: https://img.shields.io/discord/478094546522079232.svg
[discord]: https://discord.me/hassioaddons
[forum-frenck]: https://community.home-assistant.io/u/frenck/?u=frenck
[forum-shield]: https://img.shields.io/badge/community-forum-brightgreen.svg
[forum]: https://community.home-assistant.io?u=frenck
[frenck]: https://github.com/frenck
[gitlabci-shield]: https://gitlab.com/superinj/ha-addons-repository/badges/master/pipeline.svg
[gitlabci]: https://gitlab.com/superinj/ha-addons-repository/pipelines
[issue]: https://github.com/superinj/ha-addons-repository/issues
[license-shield]: https://img.shields.io/github/license/superinj/ha-addons-repository.svg
[maintenance-shield]: https://img.shields.io/maintenance/yes/2020.svg
[project-stage-shield]: https://img.shields.io/badge/project%20stage-production%20ready-brightgreen.svg
[reddit]: https://reddit.com/r/homeassistant
[semver]: http://semver.org/spec/v2.0.0.html
[third-party-addons]: https://home-assistant.io/hassio/installing_third_party_addons/