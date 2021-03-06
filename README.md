# mattermost-plugins

Mattermost is an open source, self-hosted Slack-alternative https://mattermost.org.

It's written in Golang and React and runs as a single Linux binary with MySQL or Postgres. Every month on the 16th [a new compiled version is released under an MIT license](https://about.mattermost.com/download/).

This project hosts plugins built by Mattermost staff and community. They are categorized as follows:

 - **Production**: Certified by the Mattermost team, and tested prior to each Mattermost server release.
 - **Unofficial**: Non-production plugins built by Mattermost staff and community.

### Add your plugin

To add your plugin as an unofficial plugin:

1. Fork this repository and create a branch in your fork.
2. On your branch run:
  ```bash
  git submodule add <repo-link> Unofficial/<repo-name>
  ```
  For example,
  ```bash
  git submodule add https://github.com/mattermost/mattermost-plugin-profanity-filter.git Unofficial/mattermost-plugin-profanity-filter
  ```
3. Commit the changes and push your branch.
4. Submit a pull request to this repository with your branch.


The process to get your plugin to production level is not yet determined.

Please see the respective plugin repository for details on each specific plugin. To learn more about how to build plugins, see the [Mattermost developer documentation](https://developers.mattermost.com/extend/plugins/). Got ideas for plugins? Let us know in the [feature idea forums](https://mattermost.uservoice.com/forums/306457-general?category_id=202591).
