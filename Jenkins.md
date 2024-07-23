
![](Aspose.Words.a489d5ae-a5b3-410c-bd96-83b9824d4794.001.png)

Jenkins :is an open source automation server. It helps automate the parts of software development related to building, testing, and deploying, facilitating continuous integration, and continuous delivery. It is a server-based system that runs in servlet containers such as Apache Tomcat. 

**Pipeline**

- A series of steps executed in a sequential and logical manner. 
- Example
  - Developer pushes their code in a central repository
  - That code should be fetched automatically by a server
  - Once the code has been fetched, then a build should be created from the fetched code, if needed. 
  - Once the build is successful, it will generate an output of file(s) which is considered as an artifact
  - Then a testing script can be attached on the artifact using tools Appium, JUnit, etc to create a test report, if needed, to be sent to developers. 
  - Once the code has been approved, meaning it is good for deployment (staging or production), it is sent to the deployment platform
  - The deployment platform can be different based on the requirement (Physical Server, VM, Container Environment, or m a managed Kubernetes environment)

**Continuous Integration (CI)**

**Continuous Delivery (CD)**

**Continuous Deployment (CD)**


**Code → Build → Test → Release → Deploy → Ops → Monitor** 

**QA Pipeline**

Fetch Code From Repo → Create a build → Attach the testing script → Deploy to a testing environment →  Generate Report → Share report with developers → Developer pushes a new version to repo

**Code → Build → Test → Release → Manual Approval (Release Gate)→ Deploy (Staging/Testing/Production)**

**Code → Build → Test → Release → Automated Deployment (Staging/Testing/Production)**


Jenkins Project 

Create Private repo on git 

![](Aspose.Words.a489d5ae-a5b3-410c-bd96-83b9824d4794.002.png)

In that repo push script.sh 

![](Aspose.Words.a489d5ae-a5b3-410c-bd96-83b9824d4794.003.png)






Git repo url paste

![](Aspose.Words.a489d5ae-a5b3-410c-bd96-83b9824d4794.004.png)add credentials

![](Aspose.Words.a489d5ae-a5b3-410c-bd96-83b9824d4794.005.png)



Build steps EXECUTE SHELL


Project 2

Paste link of repo 

![](Aspose.Words.a489d5ae-a5b3-410c-bd96-83b9824d4794.006.png)


![](Aspose.Words.a489d5ae-a5b3-410c-bd96-83b9824d4794.007.png)

![](Aspose.Words.a489d5ae-a5b3-410c-bd96-83b9824d4794.008.png)

Follow steps as above

![](Aspose.Words.a489d5ae-a5b3-410c-bd96-83b9824d4794.009.png)

Project 3



![](Aspose.Words.a489d5ae-a5b3-410c-bd96-83b9824d4794.010.png)






Project 3

Download Plugins of Build pipeline 

![](Aspose.Words.a489d5ae-a5b3-410c-bd96-83b9824d4794.011.png)

![](Aspose.Words.a489d5ae-a5b3-410c-bd96-83b9824d4794.012.png)

CLick on + icon of jenkins dashboard

Create a new view

![](Aspose.Words.a489d5ae-a5b3-410c-bd96-83b9824d4794.013.png)





![](Aspose.Words.a489d5ae-a5b3-410c-bd96-83b9824d4794.014.png)

Configure according to your need.

![](Aspose.Words.a489d5ae-a5b3-410c-bd96-83b9824d4794.015.png)

Select Apply and save

![](Aspose.Words.a489d5ae-a5b3-410c-bd96-83b9824d4794.016.png)

