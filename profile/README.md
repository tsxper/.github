# TSXPER - TypeScript Experiments

TypeScript Experiments is a set of open source software components, 
written to improve TypeScript/JavaScript developers daily activities 
and make overall development process more straightforward on both client and server sides.

## Goals

- Make developers more productive.
- Deliver easily extensible software components.
- Provide convenient development toolkit.
- Decrease transitive (3rd parties) dependencies.
- Apply everywhere. Adapt interfaces to make them applicable on client and server sides.

## Principles

- Easier is better.
- Less dependencies is better. Zero dependencies is the best.
- Instances are over plain objects.*
- Stability over frequent delivery.**
- IoC over implementing details.***

[ * ] PLain objects are objects created with using object literals. 

Example.

```JavaScript
const obj = {};
```

[ ** ] We are not in the fast delivery race. Always test before push.

[ *** ] Do not try to implement all the domain-specific details yourself. The problems, have been solving by engineers, are very unique. 
Engineer, that works on a specific problem, has better domain insights. Instead of trying to predict and solve all the possible problems yourself, provide tools and a space to solve the problem in the best way. Also, such details can always be placed in examples.

## Collaboration

Collaborators are welcome.
