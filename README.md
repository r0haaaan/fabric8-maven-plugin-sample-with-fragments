# Simple Spring Boot Application using Fabric8 Maven Plugin

## How to run
Just run
```
  mvn clean install fabric8:build fabric8:resource fabric8:deploy -Dfabric8.openshift.trimImageInContainerSpec=true -Dfabric8.openshift.enableAutomaticTrigger=false
```
