# Deprecated
This repository is no longer under active development. It gave preview access to a featureset that is part of the ivy-core (9.1 and higher). This repo only exists to serve older clients. 

Thanks for all the precious feedback. It helped us to craft a smooth maven integration in Axon.ivy workspaces.
If you want to see the latest version in action: use the official download site. Starting from 9.1 mavenizer features will be available without any optional installation: https://dev.axonivy.com/download


## Legacy Mavenizer 
Work effective with maven natured IvyProjects

## Smoothly integrate IAR dependencies via Maven
Often your Axon.ivy application is built with many fine separated Axon.ivy projects that depend on each other. But most of the time you only edit on one or two of it. But the Designer forces you to import all dependencies manually into your workspace. This wastes time and triggers many build and validation cycles on projects that you are actually not editing.

And here comes this cool extension into to game. Once activated it will automatically add dependencies of your project directly into your workspace. These dependencies are resolved via Maven and imported as IAR. This make your workspace builds fast and effective.

![live demo](https://raw.githubusercontent.com/ivy-supplements/mavenizer/master/doc/resolveIarProjectsViaPomXml.gif)

### Usage
1. Install the Plugin
1. Convert your IvyProject into a Maven natured project: `Java Perspective > right click on project > configure > convert to Maven Project`
1. Add IAR dependencies to your project that are available via Maven 

### Installation
1. Open a Designer (6.0.0 or newer) > `Help > Install New Software`
1. Copy the update site URI into the "Work with" text field on top ![update site](https://raw.githubusercontent.com/ivy-supplements/mavenizer/master/doc/installMavenizerSelectP2Feature.png)
1. Presse next, accept the license and agree to install unsigned content
1. Restart the Designer as suggested when the installation process ends

### Update Sites
* <= 7.2.0: https://file.axonivy.rocks/p2/features/mavenizer/7.0/
* \>= 7.3.0 : https://file.axonivy.rocks/p2/features/mavenizer/7.3/
* nightly : https://file.axonivy.rocks/p2/features/mavenizer/nightly/
