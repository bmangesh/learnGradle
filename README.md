# LearnGradle 
Learn Gradle by working  on live demo project.

# Gradle Build In Nutshell 
  We can summarize the general lifecycle of a Gradle build as follows, assuming we don't run it as a daemon:
 
+ It launches as a new JVM process
+ It parses the gradle.properties file and configures Gradle accordingly
+ Next, it creates a Settings instance for the build
+ Then, it evaluates the settings.gradle file against the Settings object
+ It creates a hierarchy of Projects, based on the configured Settings object
+ Finally, it executes each build.gradle file against its project
