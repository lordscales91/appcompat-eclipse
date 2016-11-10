AppCompat Test on Eclipse
===
This repository shows how to configure the latest appcompat-v7 support library (25.0.0 as of time of writing) on Eclipse using Maven.

Requisites
---
Requires the m2e-android connector. The project uses the classic ADT layout so it's compatible with the ADT tools. Which means that you will have code assistance for the XML and Java files.

You will also need to set up the required library projects. Otherwise Eclipse will complain of missing resources and classes. You can set up the projects from [appcompat-v7](https://github.com/dandar3/android-support-v7-appcompat/tree/25.0.0) and [support-design](https://github.com/dandar3/android-support-design/tree/25.0.0) repositories.

Installation
---
Once you clone the repository and have it visible in the Git Repositories view, right-click on it and select "Import projects..." from the contextual menu. Then, choose use the New project wizard and select Android Application Project.

Locate the project root in the assistant and proceed. Now you should be able to run it. Launch an emulator and run the verify maven goal.