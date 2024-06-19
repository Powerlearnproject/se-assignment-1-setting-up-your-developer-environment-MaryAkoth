[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15287771&assignment_repo_type=AssignmentRepo)
# Dev_Setup
Setup Development Environment

#Assignment: Setting Up Your Developer Environment

#Objective:
This assignment aims to familiarize you with the tools and configurations necessary to set up an efficient developer environment for software engineering projects. Completing this assignment will give you the skills required to set up a robust and productive workspace conducive to coding, debugging, version control, and collaboration.

#Tasks:

1. Select Your Operating System (OS):
   Choose an operating system that best suits your preferences and project requirements. Download and Install Windows 11. https://www.microsoft.com/software-download/windows11
d0ne
2. Install a Text Editor or Integrated Development Environment (IDE):
   Select and install a text editor or IDE suitable for your programming languages and workflow. Download and Install Visual Studio Code. https://code.visualstudio.com/Download
   done
3. Set Up Version Control System:
   Install Git and configure it on your local machine. Create a GitHub account for hosting your repositories. Initialize a Git repository for your project and make your first commit. https://github.com
   done

4. Install Necessary Programming Languages and Runtimes:
  Instal Python from http://wwww.python.org programming language required for your project and install their respective compilers, interpreters, or runtimes. Ensure you have the necessary tools to build and execute your code.
  done

5. Install Package Managers:
   If applicable, install package managers like pip (Python).

6. Configure a Database (MySQL):
   Download and install MySQL database. https://dev.mysql.com/downloads/windows/installer/5.7.html
   done

7. Set Up Development Environments and Virtualization (Optional):
   Consider using virtualization tools like Docker or virtual machines to isolate project dependencies and ensure consistent environments across different machines.

8. Explore Extensions and Plugins:
   Explore available extensions, plugins, and add-ons for your chosen text editor or IDE to enhance functionality, such as syntax highlighting, linting, code formatting, and version control integration.

9. Document Your Setup:
    Create a comprehensive document outlining the steps you've taken to set up your developer environment. Include any configurations, customizations, or troubleshooting steps encountered during the process. 
    To set up a developer environment, you'll need to follow these steps. 
1. Define Your Development Stack
   - Identify the programming languages and frameworks you will be using (e.g., JavaScript/Node.js, Python/Django, Java/Spring).
 2. Install an Operating System
   - Choose an OS suitable for development (e.g., Windows, macOS, Linux).
   - Install or update the OS to the latest version.
3. Install Essential Software
Text Editor or IDE: Install a code editor like Visual Studio Code, Atom, Sublime Text, or an Integrated Development Environment (IDE) like IntelliJ IDEA, PyCharm, or Eclipse.
   - Version Control System: Install Git and configure it.
   - Package Managers: Install package managers relevant to your language (e.g., npm for Node.js, pip for Python, Maven/Gradle for Java).
 4. Install Language Runtimes and Compilers
   - JavaScript/Node.js: Install Node.js and npm.
   - Python: Install Python and pip.
   - Java: Install JDK (Java Development Kit).
5. Set Up Version Control
   - Git: Install Git and set up a GitHub, GitLab, or Bitbucket account.
   - Configure global Git settings (username, email).
6. Install Databases
   - SQL Databases: Install MySQL, PostgreSQL, SQLite, etc.
   7. Install Frameworks and Libraries
   - JavaScript: Install frameworks like React, Angular, or Vue.
   - Python: Install Django, Flask.
   - Java: Install Spring Boot.
8. Configure Your Environment
   -Environment Variables: Set environment variables as needed (e.g., PATH, JAVA_HOME).
   - Project Dependencies: Install project dependencies using your package manager (e.g., npm install, pip install -r requirements.txt).
9. Set Up Containers and Virtual Machines (Optional)
   - Docker:Install Docker for containerization.
   - Virtual Machines: Set up virtual machines using tools like VirtualBox or Vagrant.
10. Install Additional Tools
   - Build Tools: Install build tools like Webpack, Gulp, Gradle.
   - Debugging Tools: Set up debugging tools and extensions for your IDE or text editor.
   - API Clients: Install tools like Postman or Insomnia for API testing.
11. Set Up Continuous Integration/Continuous Deployment (CI/CD)
   -CI/CD Tools: Configure CI/CD pipelines using services like Jenkins, Travis CI, CircleCI, GitHub Actions.
12. Documentation and Collaboration
   -Documentation Tools: Set up tools for documentation (e.g., JSDoc, Sphinx).
   - Communication Tools: Use Slack, Microsoft Teams, or other collaboration tools.
13. Testing
   - Testing Frameworks: Install testing frameworks like Jest for JavaScript, PyTest for Python, JUnit for Java.
   - Set Up Tests: Write and run test cases for your projects.
14. Backup and Sync
   - Version Control: Regularly commit your code to a remote repository.
   - Backup Tools: Set up automated backups if necessary.
Example: Setting Up a Node.js Environment
1. Install OS: Ensure you have a recent OS version.
2. Install Node.js: Download and install Node.js from the official website.
3. Set Up Git: Install Git and configure it.
4. Set Up IDE: Install Visual Studio Code and relevant extensions (e.g., ESLint, Prettier).
5. Create Project Directory: mkdir my-node-app && cd my-node-app.
6. Initialize npm: npm init -y.
7. Install Dependencies: npm install express.
8. Set Up Version Control:
   - git init
   - git add .
   - git commit -m "Initial commit"
9. Create Basic Server:
   javascript
   // index.js
   const express = require('express');
   const app = express();
   app.get('/', (req, res) => res.send('Hello World!'));
   app.listen(3000, () => console.log('Server running on port 3000'));
   10. Run the Server: node index.js.




#Deliverables:
- Document detailing the setup process with step-by-step instructions and screenshots where necessary.
- A GitHub repository containing a sample project initialized with Git and any necessary configuration files (e.g., .gitignore).
- A reflection on the challenges faced during setup and strategies employed to overcome them.
network issues ,,fixing and having a stable network

#Submission:
Submit your document and GitHub repository link through the designated platform or email to the instructor by the specified deadline.

#Evaluation Criteria:**
- Completeness and accuracy of setup documentation.
- Effectiveness of version control implementation.
- Appropriateness of tools selected for the project requirements.
- Clarity of reflection on challenges and solutions encountered.
- Adherence to submission guidelines and deadlines.

Note: Feel free to reach out for clarification or assistance with any aspect of the assignment.
