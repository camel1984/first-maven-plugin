maven property demo

# command
mvn help:describe -Dplugin=assembly
mvn help:describe -Dplugin=assembly -Ddetail=true
mvn -DdescriptorId=project assembly:single
mvn archetype:generate
mvn install
mvn -Pproduction install

mvn site:run