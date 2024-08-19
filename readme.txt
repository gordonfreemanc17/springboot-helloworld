Maven - Sonarqube Integration:
plugin in pom.yml
           <plugin>
                <groupId>org.sonarsource.scanner.maven</groupId>
                <artifactId>sonar-maven-plugin</artifactId>
                <version>4.0.0.4121</version>
            </plugin>

Version: https://mvnrepository.com/artifact/org.sonarsource.scanner.maven/sonar-maven-plugin


Token: Sonarqube Administrator - Generate token

Aufruf:
mvn sonar:sonar -Dsonar.host.url=http://0.0.0.0:59000 -Dsonar.token=squ_506f6357c2552deac58d3c625e39288b84494278




Maven - Nexus Integration:
- settings.xml: add Nexus server credentials
- pom.xml: add deployment management section (Nexus URLs)

