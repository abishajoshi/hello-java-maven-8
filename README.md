🚀** Hello Java Maven - Jenkins Build Demo**

This repository contains a simple Java HelloWorld application built with Maven, designed to demonstrate how to set up and run a Jenkins build job.
It is your first step into CI/CD with Jenkins.

📂 Project Structure

**The project contains:
**
A src/main/java/HelloWorld.java file with a simple HelloWorld program.

A pom.xml file with basic Maven build configuration.

**🛠 Tools Required
**
Make sure you have the following installed (all free):

Jenkins (installed locally or via Docker)

Java JDK 8 or 11

Maven (example: Maven 3.8.6)

Git (optional, can also run from local folder)

🧭 Step-by-Step Guide
1. Start Jenkins

Run Jenkins (for example using Docker) and access it in your browser at http://localhost:8080.

2. Configure Maven in Jenkins

In Jenkins, go to Manage Jenkins → Global Tool Configuration and add Maven (for example, Maven 3.8.6).

3. Create a Jenkins Freestyle Job

**Create a new item and select Freestyle project.**

In Source Code Management, point to this repository or select "None" if running locally.

In the Build section, choose Invoke top-level Maven targets and set the goal to clean package.

Save the job and run the build.

**4. Verify Build**

Open the console output after running the job.
You should see the message confirming that the build was successful.
