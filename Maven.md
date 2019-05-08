
# 1. What is Apache Maven?

# 1.1. The Apache Maven build system



Apache Maven is an advanced build tool to support the developer at the whole process of a software project. Typical tasks of a build tool are the compilation of source code, running the tests and packaging the result into JAR_ files. In additional to these typical build capabilities, Maven can also perform related activities, e.g., create web sites, upload build results or generate reports.

Maven allows the developer to automate the process of the creation of the initial folder structure for the Java application, performing the compilation, testing, packaging and deployment of the final product. It is implemented in Java which makes it platform-independent. Java is also the best work environment for Maven.

# 1.2. Key features of Maven

Apache Maven can be used in environments where common build tools like GNU Make or Apache Ant were used. The key features of Maven are:

    Convention over configuration: Maven tries to avoid as much configuration as possible, by choosing real world default values and supplying project templates (archtypes).

    Dependency management: It is possible to define dependencies to other projects. During the build, the Maven build system resolves the dependencies and it also builds the dependent projects if needed.

    Repository: Project dependencies can be loaded from the local file system, from the Internet or public repositories. The company behind the Maven project also provides a central repository called Maven Central.

    Extensible via plug-ins: The Maven build system is extensible via plug-ins, which allows to keep the Maven core small. The Maven core does for example not know how to compile Java source code, this is handled by the compiler plug-in.

# 1.3. Maven Central

Maven Central is an open repository provided by the company Sonatype. This repository hosts libraries which can be used in your build. By default, a Maven build uses Maven Central to search for required libraries.
