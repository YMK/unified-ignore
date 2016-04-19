# unified-ignore
This is an attempt at creating a standard way of having your ignore files unified

gitignore, jshintignore, dockerignore, npmignore. These are just a few ignore files that you may well have in your project. You may have a lot of these. We got fed up of this, and decided to try and create a standard that people can start using to unify these ignore files, so that we just end up with 1. One ignore file to rule them all, One ignore file to find them, One ignore file to bring them all, and in the darkness bind them.

Listed here are possibilities for which I think a unified "ignore" file would work. This is a WIP, and any feedback would be useful. 

* .ignorefile

This file tries to be backwards compatible with the syntax of existing ignore files, so that they can just be copied into this file with as little editing as possible. Obviously, there would need to be a way to seperate sections, so it wouldn't be entirely backwards compatible, but it would be less work for people using the ignore files to migrate.

* .ignore.yml

This is currently my favourite. It would not be backwards compatible with any ignore files, but would be the simplest to integrate with for existing systems.
