apply from: 'https://raw.github.com/lnramirez/buildscripts/master/mvnfit.gradle'

$ gradle createDirSources
:createDirSources
mkdirs /home/lrmonterosa/NetBeansProjects/mailtester/src/main/java
mkdirs /home/lrmonterosa/NetBeansProjects/mailtester/src/main/resources
mkdirs /home/lrmonterosa/NetBeansProjects/mailtester/src/main/webapp
mkdirs /home/lrmonterosa/NetBeansProjects/mailtester/src/test/java
mkdirs /home/lrmonterosa/NetBeansProjects/mailtester/src/test/resources

BUILD SUCCESSFUL

Total time: 3.132 secs

$ gradle copyPomFiles
Dynamic properties are deprecated: http://gradle.org/docs/current/dsl/org.gradle.api.plugins.ExtraPropertiesExtension.html
Deprecated dynamic property: "optionalDeps" on "root project 'mailtester'", value: "[]".
Deprecated dynamic property: "providedDeps" on "root project 'mailtester'", value: "[]".
Deprecated dynamic property: "optional" on "root project 'mailtester'", value: "mvnfit_1244kf3iqrc0kv1...".
Deprecated dynamic property: "provided" on "root project 'mailtester'", value: "mvnfit_1244kf3iqrc0kv1...".
The 'urls' property of the RepositoryHandler.mavenRepo() method is deprecated and will be removed in a future version of Gradle. You should use the 'url' property to define the core maven repository & the 'artifactUrls' property to define any additional artifact locations.
:compileJava UP-TO-DATE
:processResources UP-TO-DATE
:classes UP-TO-DATE
:war
:install
:copyPomFiles
copying build/poms/pom-default.xml to pom.xml
copied

BUILD SUCCESSFUL

Total time: 5.164 secs
