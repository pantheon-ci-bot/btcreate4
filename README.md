# btcreate4

[![CircleCI](https://circleci.com/gh/pantheon-systems/example-drops-8-composer.svg?style=svg)](https://circleci.com/gh/pantheon-ci-bot/btcreate4) [![Pantheon btcreate4](https://img.shields.io/badge/pantheon-btcreate4-yellow.svg)](https://dashboard.pantheon.io/sites/e9a25efa-767c-4227-8b1f-e16eff665e92#dev/code) [![Dev Site btcreate4](https://img.shields.io/badge/site-btcreate4-blue.svg)](http://dev-btcreate4.pantheonsite.io/)

## IMPORTANT NOTE

At the time of creation, the Pantheon site being used for testing did not have multidev capability. The test suites were therefore configured to run all tests against the dev environment. If the test site is later given multidev capabilities, you must [visit the CircleCI environment variable configuration page](https://circleci.com/gh/pantheon-ci-bot/btcreate4) and delete the environment variable `TERMINUS_ENV`. If you do this, then the test suite will create a new multidev environment for every pull request that is tested.