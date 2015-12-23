## Capability: Back end development

Development converts ideas, assumptions, and user stories into a running, functioning, system.


```
“If debugging is the process of removing bugs,
then programming must be the process of putting them in.”

 -- Edsger Dijkstra
```


Resources:
 - [S.O.L.I.D](https://scotch.io/bar-talk/s-o-l-i-d-the-first-five-principles-of-object-oriented-design)
 - [Big Ball of Mud](http://www.laputan.org/mud/)

### Level 1
 - Big ball of mud
 - Code is needlessly complex, difficult to read and poorly formatted
 - Language specific conventions aren't being followed ( java => getters/setters, c# => properties, ruby => attr_accessor, etc.. )
 - Common methods and behaviour are duplicated throughout the code base
 - Objects exhibit inappropriate intimacy and indecent exposure:
 ```return window().getForm().getElements().getElementById('name').getLength();```
 - The team don't feel proud of the code; it's difficult to work with and very brittle, resulting in stagnation, degradation and abandonment.
 - The team's velocity is very low and haphazard.
 - Programming is a stressful experience.

### Level 2
 - Code is clean and appropriately documented which makes it easier for others to read and maintain
 - Technical debt is continually measured, and given high priority during sprint planning
 - Classes have a single responsibility


### Level 3
 - Single responsibility 
 - Methods are small, single purpose, and don't create side effects
 - It is rare for 
 - Code is continually refactored to be simpler, cleaner, easier to understand and work with
 - The team are proud of their code; it's a joy to work on and improve. Introducing new features is quick, simple.
 - The team's velocity is high and consistent.
 - Programming is fun again.


[Back](https://github.com/colugo/cautious-turtle)
