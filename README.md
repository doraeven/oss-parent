# Motu OSS Parent

Last update: 20240220 released.

## Introduction

This project contains shared parent POM for projects in Motu repository.

## Usage

When starting a new project, please add configured **parent pom** to avoid replicate the same meta inf in every project:

```xml
<parent>
	<groupId>com.github.doraeven.oss</groupId>
	<artifactId>oss-parent</artifactId>
	<version>1</version>
</parent>
```

## Properties

List the info of **parent pom**.

| base          | info          | repositories  | info          | plugins       | info          |
| ------------- | ------------- | ------------- | ------------- | ------------- | ------------- |
| **charset**   | UTF-8         | **master**    | aliyun        | **core**      | maven         |
| **jdk**       | 21            | **slave**     | central       | **extend**    | proguard      |

## License

The project is released under version 2.0 of the [Apache License](https://www.apache.org/licenses/LICENSE-2.0).
