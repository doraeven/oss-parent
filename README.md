# Motu OSS Parent

Motu OSS Parent.

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

### Base info
| propertie     | info          |
| ------------- | ------------- |
| charset       | UTF-8         |
| jdk version   | 21            |

### Repositories info
| propertie     | info          |
| ------------- | ------------- |
| master        | aliyun        |
| slave         | central       |

### Plugins info
| propertie     | info          |
| ------------- | ------------- |
| core          | maven         |
| extend        | proguard      |

## License

The project is released under version 2.0 of the [Apache License](https://www.apache.org/licenses/LICENSE-2.0).
