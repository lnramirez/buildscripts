buildscripts
============

buildscripts is a collection of gradle and bash scripts to make your development easier. 

***

How do I use it?
----------------

on your build.gradle you can add
    
    apply from: 'https://raw.github.com/lnramirez/buildscripts/master/mvnfit.gradle'

then you can use it 

    gradle createDirSources

***

mvnfit.gradle tasks
-------------------

1. copyPomFiles - Copies POM files to project root directory, this is helpful to leverage IDEs that have Maven integration but lack a gradle one
2. createDirSources - Create conventional web application directory sources if they do not exist

