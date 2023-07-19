# Home Assistant Mastodon Profile Stats Integration

[![GitHub Release][releases-shield]][releases]
[![GitHub Activity][commits-shield]][commits]
[![License][license-shield]](LICENSE)

[![hacs][hacsbadge]][hacs]

[![Community Forum][forum-shield]][forum]

_Integration to get profile stats from Mastodon instances._

**This integration will set up the following platforms.**

Platform | Description
-- | --
`sensor` | Show info from Mastodon API.

## Installation

1. Using the tool of choice open the directory (folder) for your HA configuration (where you find `configuration.yaml`).
1. If you do not have a `custom_components` directory (folder) there, you need to create it.
1. In the `custom_components` directory (folder) create a new folder called `mastodon_profile_stats`.
1. Download _all_ the files from the `custom_components/mastodon_profile_stats/` directory (folder) in this repository.
1. Place the files you downloaded in the new directory (folder) you created.
1. Restart Home Assistant
1. In the HA UI go to "Configuration" -> "Integrations" click "+" and search for "Mastodon Profile Stats"

## Configuration is done in the UI

<!---->

## Contributions are welcome!

If you want to contribute to this please read the [Contribution guidelines](CONTRIBUTING.md)

***

[mastodon_profile_stats]: https://github.com/andrew-codechimp/HA-Mastodon-Profile-Stats
[commits-shield]: https://img.shields.io/github/commit-activity/y/andrew-codechimp/HA-Mastodon-Profile-Stats.svg?style=for-the-badge
[commits]: https://github.com/andrew-codechimp/HA-Mastodon-Profile-Stats/commits/main
[hacs]: https://github.com/hacs/integration
[hacsbadge]: https://img.shields.io/badge/HACS-Custom-orange.svg?style=for-the-badge
[exampleimg]: example.png
[forum-shield]: https://img.shields.io/badge/community-forum-brightgreen.svg?style=for-the-badge
[forum]: https://community.home-assistant.io/
[license-shield]: https://img.shields.io/github/license/andrew-codechimp/HA-Mastodon-Profile-Stats.svg?style=for-the-badge
[releases-shield]: https://img.shields.io/github/release/andrew-codechimp/HA-Mastodon-Profile-Stats.svg?style=for-the-badge
[releases]: https://github.com/andrew-codechimp/HA-Mastodon-Profile-Stats/releases
