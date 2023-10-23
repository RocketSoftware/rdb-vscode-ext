# Rocket Debug for VS Code README

**Rocket Debug for VS Code** is the first in a new generation of tools that offer a better mainframe development environment for building and testing modern applications to meet the challenges of:
* scalability in application architecture
* diversity in application technologies
* concurrency in application development across releases & geography
* agile principles & DevOps practices
* shift in technical expertise & diminishing mainframe knowledge

In its initial release, **Rocket Debug for VS Code** supports the debugging of mainframe COBOL applications running in Batch, TSO, and CICS environments. The COBOL debugger is integrated into Visual Studio Code (VS Code), offering an intuitive user interface while leveraging many open source tools available in the VS Code ecosystem. **Rocket Debug for VS Code** is designed to minimize the setup necessary for the testing and debugging of mainframe applications so developers can focus on the tasks they are good at. Speed at getting the job done with accuracy and precision is the primary design goal of Rocket Debug.

## Features

**Rocket Debug for VS Code** offers a modern and easy-to-use user interface (UI) for debugging applications on your z/OS system. Through Rocket Debug, you can:

* Start or connect to an application on z/OS in debugging mode.
* Pause at the beginning of your application to view its source code.
* Set breakpoints to allow the application to pause at various points in its execution.
* Step through the execution statement by statement.
* View the chain of calling programs when execution is paused.
* Display & update values in data variables when execution is paused.
* Handle & display information about program exceptions & ABENDs.
* Start multiple debug sessions to understand interactions between concurrent, cooperating applications.
* Edit the source code, build, and debug in short iterations.

![Stepping and Breakpoints](resources/RDB_stepnext_breakpoints.gif "Stepping and Breakpoints")

## Requirements

The following are the minimum requirements for **Rocket Debug for VS Code**:

* **Zowe Explorer VS Code Extension**: This extension provides the user interface and services required to authenticate & access resources (datasets and jobs) on the mainframe. Search for **Zowe Explorer** in Marketplace to find out more about this extension and install it.
* **Connection Profile Using zosmf**: The **Zowe Explorer** must be able to connect to the mainframe using a connection profile of the type **zosmf**. This implies a z/OSMF server must be running on the mainframe and accepting REST API requests.
* A valid user ID and credential for accessing mainframe resources & services using **Zowe Explorer** in VS Code.
* **IBM Z Open Editor**: This extension provides language-sensitive highlighting & formatting for COBOL files.
* **Rocket Debug REST Services** must be installed & operational on either z/OS or Windows. See _**Rocket Debug REST API Installation Guide**_ for instructions on installing & deploying the **Rocket Debug REST Services**.
* **Rocket Debug for z/OS 1.0.0** or a higher version must be installed in the z/OS system. See _**Rocket Debug for z/OS Installation Guide**_ for information on installing Rocket Debug for z/OS.
* The latest monthly cumulative service for **Rocket Debug for z/OS** must be applied.

## Extension Settings

There are no VS Code settings specific to **Rocket Debug for VS Code** in its current release.

## Known Issues

Be one of the first users to find a non-trivial issue and report to Rocket Debug's support team. All types of issues are welcome, from outright internal errors to future enhancement ideas. All suggestions are considered as proprietary to Rocket Software and will be acknowledged, with permission, in future release notes when adopted.

## Release Notes

### 0.6.0

* To be determined

### 0.5.0

Initial release of **Rocket Debug for VS Code**, also known as **Rocket Debug for VS Code MVP**. See **Features** section above for a list of features.

