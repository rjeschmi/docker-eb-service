
EasyBuild as a Service
======================


General idea: Build a REST API that will trigger builds in other containers

How do we want to do this:

 * Using flask create a priviledged container that can create other containers.
 * limit the available objects to make the interface simpler than full-blown EB

Objects:

 * configs
 * builds
 * images? (this might just be a local registry)
 * 
