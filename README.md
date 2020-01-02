maven customer plugin demo

# command

mvn archetype:generate with number 1459
mvn install
mvn org.sonatype.mavenbook.plugins:first-maven-plugin:1.0-SNAPSHOT:echo
mvn org.sonatype.mavenbook.plugins:first-maven-plugin:1.0-SNAPSHOT:echo -Decho.message="The Eagle has Landed"


add this to your ~/.m2/setting.xml:

<pluginGroups>
        <pluginGroup>org.sonatype.mavenbook.plugins</pluginGroup>
</pluginGroups>

then:

mvn first:echo

mvn myPlugin:zip-fork
mvn first:zip-fork
