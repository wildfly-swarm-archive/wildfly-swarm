# WildFly Swarm

[![Build Status](https://projectodd.ci.cloudbees.com/buildStatus/icon?job=wildfly-swarm)](https://projectodd.ci.cloudbees.com/job/wildfly-swarm)

This repository includes:

 * BOM - All project artifacts with their respective versions. Main use is for dependency management import into user applications
 * fraction-list - Generates all fractions with their dependencies, and provides a way to read it programmatically
 * plugin - Maven plugin for packaging, and starting/stopping the container for running tests
 * swarmtool - Command line tool for building a WildFly Swarm uber jar
