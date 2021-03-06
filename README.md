# ch.ethz.idsc.amod <a href="https://travis-ci.org/idsc-frazzoli/amod"><img src="https://travis-ci.org/idsc-frazzoli/amod.svg?branch=master" alt="Build Status"></a>

This repository allows to run an autonomous mobility-on-demand scenario using the amodeus library (https://github.com/idsc-frazzoli/amodeus).

Try it, orchestrate your own fleet of amod-taxis! Watch a [visualization](https://www.youtube.com/watch?v=QkFtIQQSHto) of a traffic simulation in San Francisco generated using this repository.

<table><tr>
<td>

![p1t1](https://user-images.githubusercontent.com/4012178/38852194-23c0b602-4219-11e8-90af-ce5c589ddf47.png)

<td>

![p1t4](https://user-images.githubusercontent.com/4012178/38852209-30616834-4219-11e8-81db-41fe71f7599e.png)

<td>

![p1t3](https://user-images.githubusercontent.com/4012178/38852252-4f4d178e-4219-11e8-9634-434200922ed0.png)

<td>

![p1t2](https://user-images.githubusercontent.com/4012178/38852212-3200c8d8-4219-11e8-9dad-eb0aa33e1357.png)

</tr></table>

## Getting Started

The code format of the `amod` repository is specified in the `amodeus` profile that you can import from `amodeus-code-style.xml` in the the `amodeus` repository.

- You may work on a Linux, Mac or Windows OS with a set of different possible IDEs. The combination Ubuntu, Eclipse has worked well. 
- Install Java SE Development Kit X (preferably most recent) 
- Install Apache Maven
- Install IDE (ideally Eclipse)
- Install GLPK and GLPK for Java (Ensure you install compatible versions, e.g. [here](http://glpk-java.sourceforge.net/gettingStarted.html))
	- Prerequisites are: GCC, Libtool, Swig and Subversion
- Install Git and connect to GitHub with [SSH](https://help.github.com/articles/connecting-to-github-with-ssh/)


## Installation guidelines for amod repository

1. Clone amod
2. Import to eclipse as existing maven project using the pom.xml in the top folder.
3. Set up Run Configurations for: (ScenarioPreparer; ScenarioServer; ScenarioViewer), chose the Working Directory to be the top Simulation Folder directory. You can get a sample simulation scenario at http://www.idsc.ethz.ch/research-frazzoli/amodeus.html
4. Add JAVA VM arguments if necessary, e.g., -Xmx10000m to run with 10 GB of RAM. 
5. Run the ScenarioPreparer main Function
6. Run the ScenarioServer main Function, the simulation should run.
7. Run the ScenarioViewer main Function, a viewer should open that allows visualization of the scenario.


## Gallery

<table><tr>
<td>

![usecase_amodeus](https://user-images.githubusercontent.com/4012178/35968174-668b6e54-0cc3-11e8-9c1b-a3e011fa0600.png)

Zurich

<td>

![p1t5](https://user-images.githubusercontent.com/4012178/38852351-ce176dc6-4219-11e8-93a5-7ad58247e82b.png)

San Francisco

<td>

![San Francisco](https://user-images.githubusercontent.com/4012178/37365948-4ab45794-26ff-11e8-8e2d-ceb1b526e962.png)

San Francisco

</tr></table>
