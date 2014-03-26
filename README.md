maven-demo
==========

Sample maven projects
---------------------

**pom-parent**
Parent pom for all other projects. Demostrates inheritance.

**pom-lib**
A project that contains some java classes and resources to demonstrate compilation, unit test execution, resource filtering.
Joda time is not used, it is only added to show how transitive depnendecies are handled by the maven-assembly-plugin (see pom-assembly).

**pom-assembly**
A project to show how to create a zip/tar.gz file with all the necessary dependencies. Note that transitive dependencies are also included.
Demonstrates the usage of the maven-assembly-plugin.
 
**pom-properties**
This example prints out some default properties during the validation phase.

**pom-profiles**
This one changes properties according to the active profile.

**pom-modules**
Demonstrates reactor build. All other projects are defined as modules in its pom.

