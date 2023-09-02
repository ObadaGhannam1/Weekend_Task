# Weekend_Task
Doing The Weekend Assignment SOLO . 
# Welcome to My - Repository

Hey there , in this repo we'll explain some basic information about the Docker technology , a technology which has impacted the world web development 

#  What Is Docker ?

Docker is a tool that helps developers create and manage containers. Containers are like packaged applications that include everything they need to run, making it easier to move and run software in different places.

Containers make it easier to build and deliver apps in cloud and hybrid environments. Docker, a popular tool, speeds up and simplifies containerization. Currently, Docker has more than **13 million users**.

Docker streamlines the development lifecycle by allowing developers to work in standardized environments using local containers which provide your applications and services. Containers are great for continuous integration and continuous delivery (CI/CD) workflows.

image description here](https://images.crunchbase.com/image/upload/c_lpad,f_auto,q_auto:eco,dpr_1/ywjqppks5ffcnbfjuttq)
## What Problem Does Docker Solve ?!
Docker solves the problem of inconsistent development and deployment environments in web development.


## Here's a story to help you understand 

Once upon a time, a web developer named Alice struggled with the problem of her web projects behaving differently on different computers. Then, she discovered Docker, a magical tool that transformed her projects into portable containers. These containers ensured that her web applications worked consistently, no matter where she placed them, and made collaboration with other developers a breeze. With Docker's help, Alice's web development adventures became smoother and more enjoyable, and the days of It works on my machine were gone forever.

## How Do I Download It  ?

Before we get to explain how does it work , let us download it .
If you work on **Windows** OS then follow this little tutorial : To download docker on your **Windows PC** , please follow this guide to download it by simplilearn : 

1. Go to the website https://docs.docker.com/docker-for-windows/install/ and download the docker file.

  

Note: A 64-bit processor and 4GB system RAM are the hardware prerequisites required to successfully run Docker on Windows 10.

  

2. Then, double-click on the Docker Desktop Installer.exe to run the installer.

  

Note: Suppose the installer (Docker Desktop Installer.exe) is not downloaded; you can get it from Docker Hub and run it whenever required.

  

3. Once you start the installation process, always enable Hyper-V Windows Feature on the Configuration page.

  

4. Then, follow the installation process to allow the installer and wait till the process is done.

  

5. After completion of the installation process, click Close and restart.

  
For **Mac OS**, follow this guide provided by appsdeveloperblog : 
1-Go to the Docker website: https://www.docker.com/products/docker-desktop

2-Click the “Download for Mac” button to download the latest version of Docker Desktop for Mac.

3-Once the download is complete, double-click the Docker.dmg file to open the installer.

4-Drag the Docker icon to the Applications folder to install Docker Desktop.

5-Open Docker Desktop from the Applications folder


# How About Using It ? 


The Docker workflow includes different steps, such as coding the application, making a Dockerfile, generating the Docker image, and firing up the containers.

In order to properly understand the Docker work cycle, go through the below provided practical steps.

Step 1: **Make a Program File**

  

First, make a simple HTML file named “index.html” and copy the following code into the file:

Step 2: **Make a Dockerfile**

A Dockerfile is like a set of instructions for turning your app into a Docker image. For a basic HTML program, create a file named Dockerfile and copy the provided instructions into it.

Step 3: **Generate the Docker Image**

  

Next, execute the “docker build” command to create a new Docker image from the newly created Dockerfile.

Step 4: **Launch the Containers**

  

To run your containerized program, use this command. It runs the container in the background (-d) and assigns an exposed port (-p).

  

The Docker workflow involves several steps: coding and creating your app, using a Dockerfile to turn it into a container image, generating that image, and running it to create and start containers. This explanation outlines the fundamental Docker workflow.

## Why Should We Should Use It , And Why We Shouldn't  Use It ? 

**Here are the advantages of Docker broken down into shorter and simplified points:**

  

1. **Speed**: Docker allows applications to start quickly in a software-defined environment without the lengthy boot-up process of traditional virtualization.

  

2. **Documentation**: Docker's documentation is thorough and regularly updated, making it easy for users to stay informed about new features and version-specific information.

  

3. **Public Registries**: Docker Hub offers a vast repository of container images, making it simple for users to access and install software with a single command. This approach expands beyond code and works across different platforms.

**Cons of Docker**

 
**Here are some drawbacks and concerns regarding Docker, presented in a more concise and understandable format:**

  

1. **Complex Storage**: Docker's storage options can be challenging. Docker Data Volumes require significant provisioning and manual configuration, making storage management less user-friendly and efficient.

  

2. **Limited Monitoring**: Docker's built-in monitoring primarily relies on the stats command, offering only basic container information. For more advanced monitoring, users must turn to third-party tools like CAdvisor, leaving room for improvement in Docker's native monitoring capabilities.

  

3. **Platform Dependency**: While Docker claims support for Windows and macOS, it relies on virtual machines to run on non-Linux platforms. This means Docker is still primarily Linux-based, which may limit true platform independence. Enhanced cross-platform compatibility would be beneficial.

## 

You can save any file of the workspace to **Google Drive**, **Dropbox** or **GitHub** by opening the **Synchronize** sub-menu and clicking **Save on**. Even if a file in the workspace is already synced, you can save it to another location. StackEdit can sync one file with multiple locations and accounts.

