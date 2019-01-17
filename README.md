# Mavenizer 
Work effective with maven natured IvyProjects

## Smoothly integrate IAR dependencies via Maven
Often your Axon.ivy application is built with many fine separated Axon.ivy projects that depend on each other. But most of the time you only edit on one or two of it. But the Designer forces you to import all dependencies manually into your workspace. This wastes time and triggers many build and validation cycles on projects that you are actually not editing.

And here comes this cool extension into to game. Once activated it will automatically add dependencies of your project directly into your workspace. These dependencies are resolved via Maven and imported as IAR. This make your workspace builds fast and effective.

![live demo](https://raw.githubusercontent.com/ivy-supplements/mavenizer/master/doc/resolveIarProjectsViaPomXml.gif)

## Usage
1. Install the Plugin
1. Convert your IvyProject into a Maven natured project: `Java Perspective > right click on project > configure > convert to Maven Project`
1. Add IAR dependencies to your project that are available via Maven 

## Installation
1. Open a Designer (6.0.0 or newer) > `Help > Install New Software`
1. Copy the update site URI https://ivy-supplements.github.io/mavenizer/ into the "Work with" text field on top ![update site](https://raw.githubusercontent.com/ivy-supplements/mavenizer/master/doc/installMavenizerSelectP2Feature.png)
1. Presse next, accept the license and agree to install unsigned content
1. Restart the Designer as suggested when the installation process ends

## Update Sites
* <= 7.2.0 https://ivy-supplements.github.io/mavenizer/
* Nighly & Sprint releases: https://file.axonivy.rocks/p2/nightly/
