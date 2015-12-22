## Capability 2: Quality
Testing ensures that:
 -  the users needs are met
 - the system operates as expected
 - bugs that are fixed don't come back

```
“If debugging is the process of removing bugs,
then programming must be the process of putting them in.”


"Program testing can be a very effective way to show the presence of bugs,
but is hopelessly inadequate for showing their absence."

 -- Edsger Dijkstra
```

### Level 1
  - Automation products are used to record / describe the tests, which can be run on demand
  -  Users report more bugs then the testing process

### Level 2
 - The project is built following TDD, and tests are run religiously throughout the developemnt process
 - There are several hard-coded integration tests, which rely on precise configurations of databases or responses from services.
 - Techniques such as MVC /  MVVM are used to decouple the business logic behind views from the presentation of views, allowing the logic to be 'headless' tested.

### Level 3

 - Code analysis tools are used to identify code coverage, which is 100% for the majority the code base
 - Automated integration and accepance testing tools are used to ensure that the overarching system works as expected
  -  Dependancy injection and mocking frameworks are used to isolate the components under-test from the rest of the system, allowing the components to be tested for a variety of circumstances independantly of the dependancies, such as a database.

[Back](https://github.com/colugo/cautious-turtle)