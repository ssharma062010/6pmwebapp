# maven commands
##1.create maven project(web projects)
''''
mvn archetype:generate -DgroupId=in.javahome -DartifactId=6pmwebapp -DarchetypeArtifactId=maven-archetype-webapp -DarchetypeVersion=1.4 -DinteractiveMode=false

build maven project

##cd to project folder
cd 6pmwebapp
mvn package
