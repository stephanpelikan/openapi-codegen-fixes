# OpenAPI code generator fixes

This project is used to fix problems in the version 4.2.3 of the OpenAPI code generator.

## How to use it

1. check this project
2. build it using `mvn install`
3. add it as a dependency of the maven plugin:

```
	<plugin>
		<groupId>org.openapitools</groupId>
		<artifactId>openapi-generator-maven-plugin</artifactId>
		<version>4.2.3</version>
		<dependencies>
			<dependency>
				<groupId>org.openapitools</groupId>
				<artifactId>openapi-codegen-fixes</artifactId>
				<version>0.0.1-SNAPSHOT</version>
			</dependency>
		</dependencies>
	</plugin>
```
