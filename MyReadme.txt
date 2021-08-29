use code plugin for git => add. login required

found no deployment config for openshift
    => read guide.adoc

created gaos-branch

new branch gaos-branch visible in repository github.com. Is this in branch gaos-branch? Ja!

to show where I am : git branch

guide.adoc explains the application

run locally : mvn spring-boot:run

http://localhost:8080/api/greeting?name=John  OK

mvn deploy  => NOK 
[ERROR] Failed to execute goal org.apache.maven.plugins:maven-deploy-plugin:2.8.2:deploy (default-deploy) on project rest-http: Deployment failed: repository element was not specified in the POM inside distributionManagement element or in -DaltDeploymentRepository=id::layout::url parameter -> [Help 1]
[ERROR]

mvn fabric8:deploy -Popenshift => NOK


Anderes Beispiel:
https://www.google.com/search?client=firefox-b-d&q=gitlab+openshift+deploy+sample


https://gitlab.com/gitlab-examples/openshift-deploy

