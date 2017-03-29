# AEM Archetype

* This Archetype generates an AEM maven multimodule project

* Usage:

  1. `git clone https://github.com/awadheshv/aem-archetype.git`
  2. Install locally by executing `mvn clean install`.  

  3. To generate a project run `mvn archetype:generate -DarchetypeGroupId=org.awadhesh.aem -DarchetypeArtifactId=aem-maven-archetype -DarchetypeVersion=1.0.0 -DgroupId=com.clientname -DartifactId=projectname -DprojectName="project-name" -DprojectPrettyName="The Name of The Project" -Dversion=1.0.0-SNAPSHOT -DinteractiveMode=false`.
