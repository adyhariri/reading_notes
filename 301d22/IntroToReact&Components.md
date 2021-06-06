## What is a Component?

A component is a modular, portable, replaceable, and reusable set of well-defined functionality that encapsulates its implementation and exporting it as a higher-level interface.

### Characteristics of Components


**Reusability**  − Components are usually designed to be reused in different situations in different applications.

However, some components may be designed for a specific task.

**Replaceable** − Components may be freely substituted with other similar components.

**Not context specific** − Components are designed to operate in different environments and contexts.

**Extensible** − A component can be extended from existing components to provide new behavior.

**Encapsulated** −  A component depicts the interfaces, which allow the caller to use its functionality, and do not expose details of the internal processes or any internal variables or state.

**Independent** − Components are designed to have minimal dependencies on other components.

### Advantages

> Ease of deployment − As new compatible versions become available, it is easier to replace existing versions with no impact on the other components or the system as a whole.

> Reduced cost − The use of third-party components allows you to spread the cost of development and maintenance.

> Ease of development − Components implement well-known interfaces to provide defined functionality, allowing development without impacting other parts of the system.

>Reusable − The use of reusable components means that they can be used to spread the development and maintenance cost across several applications or systems.

> Modification of technical complexity − A component modifies the complexity through the use of a component container and its services.

> Reliability − The overall system reliability increases since the reliability of each individual component enhances the reliability of the whole system via reuse.

> System maintenance and evolution − Easy to change and update the implementation without affecting the rest of the system.

> Independent − Independency and flexible connectivity of components. Independent development of components by different group in parallel. Productivity for the software development and future software development.


#### What is Props short for ?

***“Props”*** is a special keyword in React, which stands for properties and is being used for passing data from one component to another.

#### Using Props in React
1. Firstly, define an attribute and its value(data)

2. Then pass it to child component(s) by using Props

3. Finally, render the Props Data

#### What is the flow of props?

data with props are being passed in a uni-directional flow. (one way from parent to child)


### What Is React?

React is a declarative, efficient, and flexible JavaScript library for building user interfaces. 

It lets you compose complex UIs from small and isolated pieces of code called ***“components”***.

Updating the Rendered Element 
React elements are immutable.

Once you create an element, you can’t change its children or attributes. 

An element is like a single frame in a movie: it represents the UI at a certain point in time.

### Components and Props

Components let you split the UI into independent, reusable pieces, and think about each piece in isolation.

### Props are Read-Only
Whether we declare a component as a function or a class, it must never modify its own props.