## e-commerce-site-automation-project
java,maven,selenium,testng,bdd cucumber,manual testing
- if java --version, mvn --version output do not provide the Expected results then go for below Steps.

## set up steps
- **VS Code installation** 
- **java jdk installation**

**Vs code extensions**
-  	Language Support for Java(TM) by Red Hat- Provides Java code completion, linting, formatting, and project support
- 	Maven for Java: Helps manage Maven projects directly in VS Code.
- 	Extension Pack for Java: Bundles essential Java tools, including debugging and testing.
-	 Cucumber (Gherkin) Full Support: Adds BDD and Gherkin syntax support for Cucumber 
**Maven Installation**
-	Maven is a build automation tool for Java projects. You need to install Maven and add it to your system PATH so you can run Maven commands from PowerShell	
**GitHub Repository** 
-	You should create a GitHub repository to store your project code and track changes
**Project Initialization**: After installing the above, you’ll initialize a Maven project in your repo, which will be the foundation for your automation framework.
 	
## Maven set Up:
-	Download the latest Maven zip from: https://maven.apache.org/download.cgi and Dont forget to Extract_it:) and Place in some drive 
-	Add maven path in system variables :  Name: MAVEN_HOME ,Value: apache-maven-3.9.11
-  Add maven Bin path to the path Set Name: PATH ,Value: apache-maven-3.9.11\bin
  
**Steps for java maven Project creation**
**click->create java project -> click maven** 
- select maven-archetype-quickstart:) whyyy??
- For a project structure: maven-archetype-quickstart instantly creates the standard folders (src/main/java, src/test/java), eliminating manual setup and potential errors
- For a ready-to-run template: This archetype generates a functional pom.xml with essential configurations and dependencies, giving you a solid starting point for your project
- You can simply use it and then customize the generated pom.xml by adding your specific automation dependencies (like Selenium and TestNG).
- DgroupId=com.Autm 
- DartifactId=e-commerce-automation-framework 
- DarchetypeArtifactId=maven-archetype-quickstart
- Press Enter if it asks inputs while creating and Building your project in vs code terminal

