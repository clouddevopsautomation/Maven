
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


# 2.What is a Build Tool?

A build tool is a tool that automates everything related to building the software project. Building a software project typically includes one or more of these activities:

    Generating source code (if auto-generated code is used in the project).
    
    Generating documentation from the source code.
    
    Compiling source code.
    
    Packaging compiled code into JAR files or ZIP files.
    
    Installing the packaged code on a server, in a repository or somewhere else.

Any given software project may have more activities than these needed to build the finished software. Such activities can normally be plugged into a build tool, so these activities can be automated too.

The advantage of automating the build process is that you minimize the risk of humans making errors while building the software manually. Additionally, an automated build tool is typically faster than a human performing the same steps manually.

# 2.1 Installing Maven

To install Maven on your own system (computer), go to the Maven download page and follow the instructions there. In summary, what you need to do is:

    Set the JAVA_HOME environment variable to point to a valid Java SDK (e.g. Java 8).
    
    Download and unzip Maven.
    
    Set the M2_HOME environment variable to point to the directory you unzipped Maven to.
    
    Set the M2 environment variable to point to M2_HOME/bin (%M2_HOME%\bin on Windows, $M2_HOME/bin on unix).
    
    Add M2 to the PATH environment variable (%M2% on Windows, $M2 on unix).
    
    Open a command prompt and type 'mvn -version' (without quotes) and press enter.

After typing in the mvn -version command you should be able to see Maven execute, and the version number of Maven written out to the command prompt. 


# 3. Maven Settings File

http://maven.apache.org/settings.html 

# 4. Maven Build cycle

http://maven.apache.org/guides/getting-started/index.html#How_do_I_setup_Maven

# 5. How do I run life cycle in Maven.

http://maven.apache.org/guides/getting-started/index.html#How_do_I_setup_Maven

# 6. The POM.xml

http://maven.apache.org/guides/introduction/introduction-to-the-pom.html

# 7. Maven Quick reference

http://maven.apache.org/guides/getting-started/maven-in-five-minutes.html 
