# Changes

<!-- Each version newest first -->

<!-- Template:

## Version X.Y.Z (yyyy-MM-dd)

* details

-->

## Version 1.2.0 (unreleased)

* Added basic setup documentation ([PR-13](https://github.com/jenkinsci/gitea-plugin/pull/13))
* Fixed plugin URLs from `http:` to `https` ([PR-14](https://github.com/jenkinsci/gitea-plugin/pull/14))
* Fixed display of organization website ([PR-18](https://github.com/jenkinsci/gitea-plugin/pull/18))
* Fixed repository polling with disabled issues or pull requests ([PR-17](https://github.com/jenkinsci/gitea-plugin/pull/17))
                                                                 ([JENKINS-54516](https://issues.jenkins-ci.org/browse/JENKINS-54516))
* Optimized imports, less redundant code and other cleanups ([PR-15](https://github.com/jenkinsci/gitea-plugin/pull/15))
* Added support for tag discovery ([PR-6](https://github.com/jenkinsci/gitea-plugin/pull/6))
* Updated documentation with details of how to setup ([PR-20](https://github.com/jenkinsci/gitea-plugin/pull/20))

## Version 1.1.2 (2019-05-27)

* Fix improper handling of untrusted branches ([SECURITY-1046](https://issues.jenkins-ci.org/browse/SECURITY-1046))
## Version 1.1.1 (2019-02-15)

* Allow non-admins to fetch organizational repositories ([PR-11](https://github.com/jenkinsci/gitea-plugin/pull/11))

## Version 1.1.0 (2019-01-17)

* Fix PR and branch links ([JENKINS-54517](https://issues.jenkins-ci.org/browse/JENKINS-54517)) 
* Switch to handy-uri Jenkins API plugin rather than bundle duplicate classes within plugin.


## Version 1.0.8 (2018-04-04)

* Use Jenkins configured proxy settings to connect to Gitea ([JENKINS-50565](https://issues.jenkins-ci.org/browse/JENKINS-50565))

## Version 1.0.7 (2018-03-22)

* Fix NPE during dynamic installation of the plugin ([JENKINS-50349](https://issues.jenkins-ci.org/browse/JENKINS-50349))

## Version 1.0.6 (2018-03-21)

* Fix NPE during dynamic installation of the plugin ([JENKINS-50319](https://issues.jenkins-ci.org/browse/JENKINS-50319))

## Version 1.0.5 (2018-03-14)

* Fix receipt of `pull_request` webhooks.
* Fix parsing of clone URLs when Gitea is publishes scp style clone URLs ([JENKINS-49768](https://issues.jenkins-ci.org/browse/JENKINS-49768))
* Misc fixes in Branch discovery strategies and pull request discovery traits

## Version 1.0.4 (2017-12-18)

* Added support for Webhook notification of repository creation / deletion now that Gitea 1.3 supports those events
* Verified branch deletion events sent by Gitea 1.3 are parsed correctly

## Version 1.0.3 (2017-10-24)

* Update to new Gitea logo

## Version 1.0.2 (2017-08-08)

* Fix Webhook notification of pushes to branches
* Add webhook notification and management of non-`SCMSource` based job types

## Version 1.0.1 (2017-07-28)

* Disable shallow clone when we know a merge will take place ([JENKINS-45771](https://issues.jenkins-ci.org/browse/JENKINS-45771))

## Version 1.0.0 (2017-07-18)

* Initial release
