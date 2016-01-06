## Capability: Version Control

Developing digital products creates files. Lots of files.
Each of these files specifies something about the solution: how it works, how it looks, what it's called.
The collective set of files *is* the solution.

Version control systems protect these files from accidents, like deletions, by keeping track of every change that you, and your team, make.



```
To support collective ownership, use a concurrent model of version control.
Support time travel by storing tools, libraries, documentation, and
everything else related to the project in version control. (On-site customers
files, too.) Keep the entire project in a single repository.

Keep your repository clean: never check in broken code. All versions should
build and pass all tests. "Iteration" versions are ready for stakeholders;
"release" versions are production-ready.

  -- http://www.jamesshore.com/Agile-Book/version_control.html
```



Resources:
 - [InfoQ](http://www.infoq.com/articles/agile-version-control) 
 - [The Art of Agile](http://www.jamesshore.com/Agile-Book/version_control.html)
 - [How to Write a Git Commit Message](http://chris.beams.io/posts/git-commit/)
 - [A Simple Git Branching Model](https://gist.github.com/aussielunix/59957626d6eace17be64)
 - [Atomic Commits](http://www.freshconsulting.com/atomic-commits/)

### Level 1
 - The team all have access to, and regularly use, the repository
 - Only one branch is used for development
 - Only the repository features of the version control system are used
 - The repository's log is full of unhelpful and inconsistent commit messages, and it is impossible to recreate what, how, and why things were done
 - The changes introduced in single commits is haphazard, and typically contains whatever has been changed on the local machine

### Level 2
 - Multiple branches are used to introudce new functionality, but take several days to merge back into main branch
 -  Configuration files and dependancies are stored within the version control system, but manual modifications to the development environment are required
 - Commits to the repository are made daily, typically at the end of the day.
 - In fear of breaking the build, only completed features are committed. 
 - Other features of the version control system, such as identifying differences and metrics are starting to be used

### Level 3
 - The version control system is used to authoritatively hold the projects code, dependancies and configuration. 
 - The team routinely use branches for exploritory feature development
 - The team contibutes to the repository multiple times thoughout the day
 - The team exploit all features of the version control system: triggering builds, code reviews, comments, feature requests, notifications, etc
 - The master branch always contains working code, and isn't ever in a broken state. Feature branches always compile, but are in varying stages of completion
 - Commits to the repository are small, contained and atomic
 - Important points in the project's history are tagged, and archived for future reference
 - The repository's log communicates the context about why changes were made, and actions taken.

[Back](https://github.com/colugo/cautious-turtle)
