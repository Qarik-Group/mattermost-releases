# Mattermost Releases

[Mattermost](https://about.mattermost.com/) is an open source, private cloud [Slack](https://slack.com/)-alternative. Stark & Wayne maintains the [BOSH release for Mattermost](https://github.com/cloudfoundry-community/mattermost-boshrelease) and the [CI pipeline](https://ci.starkandwayne.com/teams/main/pipelines/mattermost-boshrelease) to build and test it.

Unfortunately for our CI pipeline, at this time the [Mattermost downloads](https://about.mattermost.com/download/) are not easily consumable by a Concourse resource. So, this project will host the various releases as Github releases - something that is easily consumable by our Concourse CI pipeline.

See the `ci` directory for the Concourse pipeline description.
