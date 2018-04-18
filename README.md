# Oracle Forms Standalone Start with WPF Webbrowser Component

Sometimes a startup with fixed parameters or a Windows User Credential check is required before calling Oracle Forms. This could be done with a WPF Application to hide information and handle safer routines for the Oracle Forms start. You can also handle the ON-CLOSE event in this WPF application to back up application logoff.

>**Attention:**
>The IE11 plugin Java Web component is not forward-looking technology, but it can be helpful for rapid prototyping and deployments on Windows 10 clients.

## Getting Started

There is the description for project building of the application.

### Prerequisites

- Windows 10
- Latest Java 1.8 plugin on IE11
- Micrososft Visusal Studio 2017 
- Micrososft Visusal Studio 2015 
- Using the 'Materialized Forms' Demo from the online forms Server

### Installing

- Install the latest IE11 
  - Check & upgrade the Java IE11 plugin [Java Plugin 1.8](https://www.java.com/verify)
- Downloading the project ZIP file and unzip it
- In MS Visual Studio *Open Project* and pick up the project file *WpfAppIExx.csproj*
- Build and run it
- Start in *project\bin\Debug\WpfAppIExx.exe*
- Accept the Forms Server inputs and start the Demo.

## Running the tests

The WPF application embeds the *Materialized Forms Demo* (Demo0017) from Oracle Forms Demo server: https://forms-demo.com/plsql/cd_forms12demo?sg=0&anw=1 


<img src="http://www.fmatz.com/FormsWPFstart3.gif"/>

.