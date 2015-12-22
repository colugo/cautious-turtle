## Capability 1: Version Control
Version control systems allow teams to colloborate on projects, manage access and modifications to team artefacts, which are stored within a centrally available repository.

Resources:
 - [infoq](http://www.infoq.com/articles/agile-version-control) 

### Level 1
 - The team all have access to, and regularly use, the repository
 - Only one branch is used for development
 - Only completed features are commited to the repository
 - Only the repository features of the version control system are used

### Level 2
 - Multiple branches are used to introudce new functionality, but take several days to merge back into main branch
 -  Configuration files and dependancies are stored within the version control system, but manual modifications to the development environment are required
 - Commits to the repository are made daily, typically at the end of the day.
 - Other features of the version control system, such as identifying differences and metrics are starting to be used


### Level 3
 - The version control system is used to authoritatively hold the projects code, dependancies and configuration. 
 - The team routinely use branches for exploritory feature development
 - The team contibutes to the repository multiple times thoughout the day
 - The team exploit all features of the version control system: triggering builds, code reviews, comments, feature requests, notifications, etc
 - The repository always contains working code, and isn't ever in a broken state
 - Important points in the project's history are tagged, and archived for future reference

[Back](https://github.com/colugo/cautious-turtle)