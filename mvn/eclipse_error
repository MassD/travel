when create a new mvn project in Elipse kepler

The following problems accur


1. Description	Resource	Path	Location	Type
CoreException: Could not calculate build plan: Plugin org.apache.maven.plugins:maven-compiler-plugin:2.3.2 or one of its 
dependencies could not be resolved: Failed to read artifact descriptor for org.apache.maven.plugins:maven-compiler-plugin:jar:2.3.2:
ArtifactResolutionException: Failure to transfer org.apache.maven.plugins:maven-compiler-plugin:pom:2.3.2 
from http://repo.maven.apache.org/maven2 was cached in the local repository, resolution will not be reattempted 
until the update interval of central has elapsed or updates are forced. Original error: Could not transfer 
artifact org.apache.maven.plugins:maven-compiler-plugin:pom:2.3.2 from/to central (http://repo.maven.apache.org/maven2):
Connection refused: no further information to http://repo.maven.apache.org/maven2/org/apache/maven/plugins/maven-compiler-plugin/
2.3.2/maven-compiler-plugin-2.3.2.pom	pom.xml	/sparqlimport	line 1	Maven Project Build Lifecycle Mapping Problem

2.Description	Resource	Path	Location	Type
Failure to transfer org.apache.maven.plugins:maven-resources-plugin:pom:2.5 from http://repo.maven.apache.org/maven2 was 
cached in the local repository, resolution will not be reattempted until the update interval of central has elapsed or 
updates are forced. Original error: Could not transfer artifact org.apache.maven.plugins:maven-resources-plugin:pom:2.5 
from/to central (http://repo.maven.apache.org/maven2): Connection refused: no further information to http://repo.maven.apache.
org/maven2/org/apache/maven/plugins/maven-resources-plugin/2.5/maven-resources-plugin-2.5.pom	pom.xml	/sparqlimport	line 1
Maven Configuration Problem

3.Description	Resource	Path	Location	Type
Plugin execution not covered by lifecycle configuration: org.apache.maven.plugins:maven-compiler-plugin:2.3.2:compile 
(execution: default-compile, phase: compile)	pom.xml	/sparqlimport	line 1	Maven Project Build Lifecycle Mapping Problem

4. Description	Resource	Path	Location	Type
Plugin execution not covered by lifecycle configuration: org.apache.maven.plugins:maven-compiler-plugin:2.3.2:testCompile 
(execution: default-testCompile, phase: test-compile)	pom.xml	/sparqlimport	line 1	Maven Project Build Lifecycle Mapping Problem


#### Solution 1

1. add dependency to pom.xml

<dependency>
    <groupId>org.apache.maven.plugins</groupId>
    <artifactId>maven-resources-plugin</artifactId>
    <version>2.4.3</version>
</dependency>
2. run mvn install from Eclipse or from command line

3. refresh the project in eclipse (F5)

4. run Maven > Update Project Configuration... on project (right click)
