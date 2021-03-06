# Required Jenkins plugins
Plugin name                                                                                       | Description
------------------------------------------------------------------------------------------------- | ----------------------------------------------
[Build timeout plugin](http://wiki.jenkins-ci.org/display/JENKINS/Build-timeout+Plugin)           | Allows you to set a time, if the job runs longer it will get automatically cancelled.
[Build With Parameters](https://wiki.jenkins-ci.org/display/JENKINS/Build+With+Parameters+Plugin) | For having a build with parameters
[Build name setter](http://wiki.jenkins-ci.org/display/JENKINS/Build+Name+Setter+Plugin)          | Allows you to adjust the build's name during a build
[Build User Vars](https://wiki.jenkins-ci.org/display/JENKINS/Build+User+Vars+Plugin)             | Allows you to retrieve the information Jenkins has about which user kicked-off the build
**(1)**[Cloudbees Pipeline](http://release-notes.cloudbees.com/product/CloudBees+Workflow)        | Allows the usage of enterprise level **Pipeline** components such as *checkpoint*
[Conditional Buildstep](https://wiki.jenkins-ci.org/display/JENKINS/Conditional+BuildStep+Plugin) | Allows you to filter buildstep executions depending on the context of the job execution
[Copy Artifact](http://wiki.jenkins-ci.org/display/JENKINS/Copy+Artifact+Plugin)                  | For being able to copy artifacts between jobs, useful when external jobs have some result that the Workflow needs
[Credentials Binding](http://wiki.jenkins-ci.org/display/JENKINS/Credentials+Binding+Plugin)      | For allowing credentials to be bound in Jenkins Workflow scripts (see example 4)
[Credentials](http://wiki.jenkins-ci.org/display/JENKINS/Credentials+Plugin)                      | For managing credentials for other servers or uses in a safe way
[Description setter](http://wiki.jenkins-ci.org/display/JENKINS/Description+Setter+Plugin)        | Allows you to set the build's description during a build
[Folders](https://wiki.jenkins-ci.org/display/JENKINS/CloudBees+Folders+Plugin)                   | Required for Folder Plus / Multi-Branch
[Folders Plus](http://release-notes.cloudbees.com/product/Folders+Plus+Plugin)                    | Allows you to set environment variables for the Multi-Branch jobs
[GIT](http://wiki.jenkins-ci.org/display/JENKINS/Git+Plugin)                                      | For checking out GIT repositories
[Hidden parameters](http://wiki.jenkins-ci.org/display/JENKINS/Hidden+Parameter+Plugin)           | As the workflow jobs require a lot of pre-set parameters, this plugin will hide them from the build execution page
[Mask Passwords](http://wiki.jenkins-ci.org/display/JENKINS/Mask+Passwords+Plugin)                | For masking passwords in log files
[NodeLabel Parameter](https://wiki.jenkins-ci.org/display/JENKINS/NodeLabel+Parameter+Plugin)     | For allowing you to restrict the node a job builds in via a parameter. Either by node label or node name
[Parameterized Trigger](http://wiki.jenkins-ci.org/display/JENKINS/Parameterized+Trigger+Plugin)  | For triggering parameterized builds with parameters
**(2)**[Pipeline](https://wiki.jenkins-ci.org/display/JENKINS/Pipeline+Plugin)                    | For being able to execute Jenkins Pipeline jobs
[Pipeline Multi-Branch](https://wiki.jenkins-ci.org/display/JENKINS/Pipeline+Plugin)              | For being able to execute Jenkins Pipeline jobs via Multi-Branch (seperate install from Jenkins Pipeline, although the same URL)
[Show Build Parameters](https://wiki.jenkins-ci.org/display/JENKINS/Show+Build+Parameters+Plugin) | Show the parameters used for a build on the main build page
[SonarQube](http://redirect.sonarsource.com/plugins/jenkins.html)                                 | For executing sonarqube analysis (also requires a SonarQube Runner agent on buildslaves)
[Sonatype CLM](http://links.sonatype.com/products/clm/ci/home)                                   | For showing Nexus CLM (also known as IQ) results in Jenkins overview
[Stash Notifier](http://wiki.jenkins-ci.org/display/JENKINS/StashNotifier+Plugin)                 | Allows you to easily notify stash for build status updates
[Stash Pullrequest](https://wiki.jenkins-ci.org/display/JENKINS/Stash+pullrequest+builder+plugin) | Allows you to have the job check for pull requests in Stash/BitBucket (for PR's they do not send notifications to Jenkins)
[Timestamper](http://wiki.jenkins-ci.org/display/JENKINS/Timestamper)                             | For adding timestamps to your log

** (1)(2): these plugins are actually a group of plugins, the entire group of each is required **
