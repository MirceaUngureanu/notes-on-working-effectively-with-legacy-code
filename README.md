### A collection of notes from reading "Working Effectively with Legacy Code" by Michael Feathers

---

Behaviour is the most important thing about software.

#### There are four reasons to change software and each can impact several things in the system.
1. Adding a feature (structure, new functionality)
2. Fixing a bug (structure, existing functionality)
3. Improving the design (structure)
4. Optimising resource usage (resource usage)

Avoiding change ultimately leads to fear and doubt in our ability. To counter this, change needs to be part of our routine.

#### Working with feedback
Changes in a system can be made in two primary ways:
- Edit and Pray (industry standard)
- Cover and Modify

Qualities of good unit tests:
1. They run fast 
2. They help us localize problems

#### The legacy code change algorithm
1. Identify change points.
2. Find test points.
3. Break dependencies
4. Write tests
5. Make change and refactor