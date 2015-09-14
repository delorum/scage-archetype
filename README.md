# scage-archetype
This is a maven archetype to quickly create a simple project based on Scage.

You can use the scage archetype to create a new scage project stub:

    $ mvn archetype:generate -DarchetypeGroupId=scage -DarchetypeArtifactId=project-archetype -DarchetypeVersion=10.8 -DarchetypeRepository=https://raw.github.com/dunnololda/mvn-repo/master

This utilize the maven's "archetype" feature - create a simple example project with all needed stuff. Answer some questions about its name and version and you are done.

For example:
groupId: mygroup
artifactId: myartifact
version: 0.1
package mygroup.myartifact

(these all names are not really important, you can choose anything)

In the end type Y, hit 'enter' and the folder "myartifact" will be created. Inside will be a small application, ready to compile, run and deploy - simple Light Cycles game based on the Tron movie.
