Usage
=====

Import dependency using maven:

    <dependencyManagement>
      <dependencies>
          <dependency>
            <groupId>fr.smile.core.components</groupId>
            <artifactId>bindgen-java</artifactId>
            <version>0.2.4</version>
          </dependency>
      </dependencies>
    </dependencyManagement>

    <repositories>
        <repository>
            <id>bucket-release-repo</id>
            <url>https://apidae-sit-packages.s3.eu-west-3.amazonaws.com/release</url>
        </repository>
    </repositories>


# bindgen-java
bindgen java.* bindings and optional custom parent
