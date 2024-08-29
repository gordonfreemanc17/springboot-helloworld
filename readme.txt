Maven - Sonarqube Integration:
plugin in pom.yml
           <plugin>
                <groupId>org.sonarsource.scanner.maven</groupId>
                <artifactId>sonar-maven-plugin</artifactId>
                <version>4.0.0.4121</version>
            </plugin>

Version: https://mvnrepository.com/artifact/org.sonarsource.scanner.maven/sonar-maven-plugin


Sonarqube (Docker):

Aufruf:
mvn sonar:sonar -Dsonar.host.url=http://192.168.122.91:59000 -Dsonar.token=squ_aa86a08216a762e9ae9cf80fd4430220d160d21c

Token: Sonarqube, Admin, My Account, Security, generate token




Maven - Nexus Integration:
- settings.xml: add Nexus server credentials
- pom.xml: add deployment management section (Nexus URLs)

