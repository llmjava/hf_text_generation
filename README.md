# HF Text Generation

[![build](https://github.com/llmjava/hf_text_generation/actions/workflows/main.yml/badge.svg)](https://github.com/llmjava/hf_text_generation/actions/workflows/main.yml) [![Jitpack](https://jitpack.io/v/llmjava/hf_text_generation.svg)](https://jitpack.io/#llmjava/hf_text_generation) [![Javadoc](https://img.shields.io/badge/JavaDoc-Online-green)](https://llmjava.github.io/hf_text_generation/javadoc/) [![License](https://img.shields.io/badge/License-Apache_2.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)

</b>

**hf_text_generation** is an [Hugging Face Text Generation API](https://github.com/huggingface/text-generation-inference) client for Java 11 or later. It is generated from the [Hugging Face Text Generation API OpenAPI spec](https://huggingface.github.io/text-generation-inference/openapi.json) using the excellent [OpenAPI Generator](https://github.com/OpenAPITools/openapi-generator).

It can be used in Android or any Java and Kotlin Project.

## Add Dependency

### Gradle

To use library in your gradle project follow the steps below:

1. Add this in your root `build.gradle` at the end of repositories:
    ```groovy
    allprojects {
        repositories {
            ...
            maven { url 'https://jitpack.io' }
        }
    }
    ```
2. Add the dependency
   ```groovy
   dependencies {
       def HF_TEXT_GENERATION_VERSION = "..."
       implementation "com.github.llmjava:llm4j:$HF_TEXT_GENERATION_VERSION"
   }
   ```

### Maven

To use the library in your Maven project, follow the steps below:

1. Add the JitPack repository to your build file:
    ```xml
    <repositories>
        <repository>
            <id>jitpack.io</id>
            <url>https://jitpack.io</url>
        </repository>
    </repositories>
    ```
2. Add the dependency
    ```xml
    <dependency>
        <groupId>llmjava</groupId>
        <artifactId>hf_text_generation</artifactId>
        <version>${HF_TEXT_GENERATION_VERSION}</version>
    </dependency>
    ```


## Usage

TODO

## Build Project

Clone the repository and import as Maven project in IntelliJ IDEA or Eclipse

Before building the project, make sure you have the following things installed.

- Maven
- Java 11

To install the library to your local Maven repository, simply execute:

```shell
mvn install
```

To build the library using Gradle, execute the following command

```shell
./gradlew build
```

Refer to the [official documentation](https://maven.apache.org/plugins/maven-deploy-plugin/usage.html) for more information.
