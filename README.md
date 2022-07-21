# jenkins-tutorial

1. Source Code Management Tab : optional SCM, such as CVS or Subversion where your source code resides.
2. Build Triggers : Optional triggers to control when Jenkins will perform builds.
3. Build Environment: Some sort of build script that performs the build 
(ant, maven, shell script, batch file, etc.) where the real work happens
4. Build : Optional steps to collect information out of the build, 
such as archiving the artifacts and/or recording javadoc and test results.
5. Post-build Actions : Optional steps to notify other people/systems 
with the build result, such as sending e-mails, IMs, updating issue tracker, etc.