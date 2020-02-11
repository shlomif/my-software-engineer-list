<!-- omit in toc -->
# Awesome Software Engineer

This is a list of topics, theory and practical tools I find useful in my career as a Software Engineer. The list is meant to summarize the keywords with links provided.

Feel free to contribute with Pull Requests, or fork this project to create your personalized list.
- [Social Studies](#social-studies)
  - [Culture Theory](#culture-theory)
  - [Organizational Theory](#organizational-theory)
- [Management and Planning](#management-and-planning)
  - [Software Process Definitions](#software-process-definitions)
  - [Software Process Frameworks/Models](#software-process-frameworksmodels)
  - [Popular Software Process](#popular-software-process)
- [Technical Knowledge](#technical-knowledge)
  - [Discrete Math](#discrete-math)
  - [Algorithms](#algorithms)
    - [Search Algorithms](#search-algorithms)
    - [Sort Algorithms](#sort-algorithms)
  - [Software Metrics](#software-metrics)
  - [Software Quality Characteristics](#software-quality-characteristics)
  - [API Design](#api-design)
  - [SOLID Principles](#solid-principles)
  - [Object-Oriented Programming](#object-oriented-programming)
    - [Objects and Classes](#objects-and-classes)
    - [Core Principles](#core-principles)
  - [Component-Oriented Programming](#component-oriented-programming)
    - [Component Characteristics](#component-characteristics)
    - [Defining Software Components](#defining-software-components)
    - [Elements of a Software Component](#elements-of-a-software-component)
- [Development Tools, Programming Languages and Useful Software](#development-tools-programming-languages-and-useful-software)
  - [Integrated Development Environments (IDE's)](#integrated-development-environments-ides)
  - [Code Editors](#code-editors)
  - [Git Tools](#git-tools)
  - [Database Tools](#database-tools)
  - [UML Tools](#uml-tools)
  - [Programming Languages and Frameworks](#programming-languages-and-frameworks)
  - [Search Engines](#search-engines)

# Social Studies

## Culture Theory

## Organizational Theory

# Management and Planning

## Software Process Definitions
- [What is a Software Process Framework/Model](https://www.geeksforgeeks.org/software-engineering-software-process-framework/)
- [What is a Software Process?](https://en.wikipedia.org/wiki/Software_development_process)

## Software Process Frameworks/Models

- Core Frameworks
  - [Waterfall](https://en.wikipedia.org/wiki/Waterfall_model) — a linear framework with strict phases.
  - [Iterative](https://en.wikipedia.org/wiki/Iterative_design) - a framework based on a cyclic process of prototyping, testing, analyzing, and refining a product or process.
  - [Incremental](https://en.wikipedia.org/wiki/Incremental_build_model) — a framework of where a product is designed, implemented and tested incrementally (a little more is added each time) until the product is finished.
- Combined Frameworks
  - [Agile](https://www.geeksforgeeks.org/software-engineering-agile-software-development/) — an iterative and incremental approach, that is flexible and adopts well to changes.
  - [Prototyping](https://www.guru99.com/software-engineering-prototyping-model.html) — an iterative and incremental framework that puts great focus on evolutionary prototyping. 
  - [Spiral](https://en.wikipedia.org/wiki/Spiral_model) — a risk-driven combined linear-iterative framework, that adopts elements from the incremental, waterfall and evolutionaly prototyping model.
  - [Rapid application development (RAD)](https://en.wikipedia.org/wiki/Rapid_application_development) — an iterative and incremental framework that pust a larger focus on being practical rather than using valuable time on planning, design, and documentation.
  - [Unified Process](https://en.wikipedia.org/wiki/Unified_Process) — an agile software development process framework, with a heavy focus on UML.
  - [Evolutionary](https://www.geeksforgeeks.org/software-engineering-evolutionary-model/) — an iterative and incremental framework, relavant for larger projects.
  - [Component-Based Software Engineering](https://en.wikipedia.org/wiki/Component-based_software_engineering) - an iterative and incremental framework, that is adapted to Component-Based Programming.

## Popular Software Process
- [SCRUM](https://www.scrumguides.org) - an agile process that works in concentrated chunks of time (sprints), and has well-defined roles for project members. 
- [Kanban](https://www.atlassian.com/agile/kanban) - an agile process that relies heavily on the usage of a project board, and good communication.
- [Extreme Programming](http://www.extremeprogramming.org) — an agile process that emphasized pair programming and customer satisfaction.
- [Rational Unified Process](https://en.wikipedia.org/wiki/Rational_Unified_Process) - a specific implementation of the Unified Process.



# Technical Knowledge

## Discrete Math
- [Discrete Mathematics: An Open Introduction](http://discrete.openmathbooks.org/dmoi2/dmoi.html) - An online book that covers all the subjects of Discrete Mathematics


## Algorithms
- [Geeksforgeeks: Fundamentals of Algorithms](https://www.geeksforgeeks.org/fundamentals-of-algorithms/) — An online website that covers all the fundamentals of understanding algorithms.

### Search Algorithms

### Sort Algorithms

- Insertion Sort
- Merge Sort
- Quick Sort

## Software Metrics

- [ABC Software Metric](https://en.wikipedia.org/wiki/ABC_Software_Metric) — an ABC score as a triplet of values that represent the size of a set of source code statements.
- Bugs per line of code — selfexplanatory
- [Code coverage](https://en.wikipedia.org/wiki/Code_coverage) — The degree to how much source code of a program that is covered by automated tests.
- [Cohesion](https://en.wikipedia.org/wiki/Cohesion_(computer_science)) — The degree to which the elements inside a module belong together.
- Comment density — a metric decided by either line count or character count in regards comments.
- [Connascence](https://en.wikipedia.org/wiki/Connascence) — a metric on the complexity caused by dependency relationships (similar to coupling, but it is not the same).
- [Constructive Cost Model](https://en.wikipedia.org/wiki/COCOMO) — a procedural software cost estimation model.
- [Coupling](https://en.wikipedia.org/wiki/Coupling_(computer_programming)) — The degree of interdependence between software modules; a measure of how closely connected two routines or modules are; the strength of the relationships between modules.
- [Cyclomatic complexity](https://en.wikipedia.org/wiki/Cyclomatic_complexity) — a metric used to indicate the complexity of a program defined by the amounts of linearly independent paths through the program.
- Defect density — defects found in a component
- Defect potential — expected number of defects in a particular component
- [Defect removal rate](https://swtestingconcepts.wordpress.com/test-metrics/defect-removal-efficiency/) —  a measure of a development teams ability to remove defects prior to release.
- [DSQI (design structure quality index)](https://en.wikipedia.org/wiki/DSQI) —  a metric to indicate a computer program's design structure and the efficiency of its modules (a value from 0 to 1).
- [Function Points and Automated Function Points](https://en.wikipedia.org/wiki/Function_point) — a metric to express the amount of business functionality an information system provides to a user.
- [Halstead Complexity]() — metrics to identify measurable properties of software, and the relations between them.
- [Instruction path length](https://en.wikipedia.org/wiki/Instruction_path_length) — the number of machine code instructions required to execute a section of a computer program.
- [Maintainability index](https://en.wikipedia.org/wiki/Maintainability#Software_engineering) —  a measure of the ease with which a product can be maintained.
- [Number of lines of code](https://en.wikipedia.org/wiki/Source_lines_of_code) —  a metric to measure the size of a computer program.
- [Program execution time](https://en.wikipedia.org/wiki/Runtime_(program_lifecycle_phase)) — a measure of time when the CPU is executing the machine code for a given instruction/method/program.
- [Program load time](https://en.wikipedia.org/wiki/Loader_(computing)) — a measure of the time it takes to load a program.
- [Program size (binary)](https://en.wikipedia.org/wiki/Binary_file) — the size of a program in bytes.
- [Weighted Micro Function Points](https://en.wikipedia.org/wiki/Weighted_Micro_Function_Points) — a successor to the maintainability index, cyclomatic complexity, function points, Halstead complexity and the Constructive Cost Model. It is a metric that measures the overall code complexity and volume metrics in a given system.
- [CISQ automated quality characteristics](https://content.castsoftware.com/cisq-specification-for-automated-quality-characteristic-measures) — automated measurement of four Software Quality Characteristics. Reliability, Performance Efficiency, Security, and Maintainability.

## Software Quality Characteristics


## API Design

- [REpresentational State Transfer (REST)](https://restfulapi.net) — A stateless architecture for data transfer that is dependent on hypermedia.
- [gRPC](https://grpc.io) — A nimble and lightweight system for requesting data.
- [GraphQL](https://graphql.org) — An approach wherein the user defines the expected data and format of that data.
- [Webhooks](https://en.wikipedia.org/wiki/Webhook) — Data updates to be served automatically, rather than requested.

## SOLID Principles

- [Single responsibility principle](https://en.wikipedia.org/wiki/Single_responsibility_principle) — A class should only have a single responsibility, that is, only changes to one part of the software's specification should be able to affect the specification of the class.

- [Open–closed principle](https://en.wikipedia.org/wiki/Open–closed_principle) — “Software entities ... should be open for extension, but closed for modification.”

- [Liskov substitution principle](https://en.wikipedia.org/wiki/Liskov_substitution_principle) — "Objects in a program should be replaceable with instances of their subtypes without altering the correctness of that program." See also design by contract.

- [Interface segregation principle](https://en.wikipedia.org/wiki/Interface_segregation_principle) — “Many client-specific interfaces are better than one general-purpose interface.”

- [Dependency inversion principle](https://en.wikipedia.org/wiki/Dependency_inversion_principle) — One should “depend upon abstractions, not concretions.”

## Object-Oriented Programming

### Objects and Classes
- [Classes](https://en.wikipedia.org/wiki/Class_(computer_programming)) — an extensible program-code-template for creating objects.
- [Objects](https://en.wikipedia.org/wiki/Object_(computer_science)) — a particular instance of a class

### Core Principles
- [Encapsulation](https://en.wikipedia.org/wiki/Encapsulation_(computer_programming)) - bundling of data with the methods that operate on that data, or the restricting of direct access to some of an object's components.

- [Inheritance](https://en.wikipedia.org/wiki/Inheritance_(object-oriented_programming)) - a mechanism in which one class acquires the property of another class.

- [Polymorphism](https://en.wikipedia.org/wiki/Polymorphism_(computer_science)) - the provision of a single interface to entities of different types or the use of a single symbol to represent multiple different types.

## Component-Oriented Programming

### Component Characteristics

- **Part of a Whole** - Components can be composed to and decomposed from a system. Composition of an appropriate set of components should yield a complete functional system; decomposition of a complete system should yield the set of constituent components.
- **Component Ecosystem** - Components are designed to be used in a compositional way together with other components. A component is not normally designed in isolation, but as part of a collection of collaborating components. The collaborating components work in the context of a component framework governed by a component model. The collaborating components, the component framework, and the component model together form a component ecosystem.
- **Component Framework** - The component framework provides a common fabric or environment over which the components may be composed.
- **Component Model** - A component model defines what components are, how they can be constructed, how they can be composed, and how they can be deployed. The component model also defines the component framework.
- **Component Interfaces** - Each component specifies one or more interfaces through which other components can be composed with it. The interfaces adhere to the composition standards defined in the component model.
- **Provided and Required Interfaces** - One type of interface is meant for other components to compose with this component and make use of the function- ality provided by this component. This type of interface is called a provided interface. Another type of interface is meant for other components to compose with this compo- nent and provide some functionality to this component. This type of interface is called a required interface. A component’s interface specifications include both the provided and required interfaces.
- **Component Compatability** -  Two components are said to be compatible if they have complementing interfaces (i.e., the provided interface of one component should be the same as the required interface of the other).
- **Implementation Independence** - Two compatible components (which have complementing interface specifications, by definition of compatibility) can always be composed, irrespective of the manner in which their interfaces are implemented.
- **Producer-Consumer Independence** - A component may be produced and consumed by different commercial entities, as long as the producer and consumer have a common interface definition for the com- ponent in context. This property of the component is a derivative of implementation independence.
- **Active and Passive Component** - During the composition process that composes components together, some of the participating components may be actively performing the composition, whereas the others may be passively participating in the composition process. Note that this notion of active and passive components is limited to the composition process; it does not imply that the passive components will continue to play a passive functional role in the resultant composite product.

### Defining Software Components

- **Function Libraries as Software Components** - a collection of functions packaged together, to form a function library, with an API. Cannot be resolved at Runtime.
- **Object Libraries as Software Components** - a collection of objects, taht together form an object library, with an API. Can be resolved at Runtime.

### Elements of a Software Component

- **Component specifications** - documents the piece of functionality implemented by the component.
- **Component interfaces** - a set of accessible operations through one or more interfaces.
- **Component implementation(s)** - an implementation of the component specification.
- **Component model** - defines a standard socket to be implemented by the com- ponent framework, and a standard plug to be implemented by components.

# Development Tools, Programming Languages and Useful Software

## Integrated Development Environments (IDE's)

- All-In-One IDE's
  - [Eclipse](https://www.eclipse.org) - A plugin based IDE, that supports many languages.
- C# IDE's
  - [Visual Studio IDE](https://visualstudio.microsoft.com) - Microsoft own full fledged IDE, which boasts up-to-date .NET support.
  - [Jetbrans Rider](https://visualstudio.microsoft.com) - Jetbrains Rider, is Jetbrains take on a full fledged .NET IDE. Has the full power of ReSharper, which ensures easy coding and a helps ensure a good code quality.
- Java IDE's
  - [Jetbrains IntelliJ IDEA](https://www.jetbrains.com/idea/) — Capable and Ergonomic IDE for JVM.
  - [Netbeans](https://netbeans.org) - A free and open-source Java IDE.
- Python IDE's
  - [Jetbrains Pycharm](https://www.jetbrains.com/pycharm/) — The Python IDE for Professional Developers

## Code Editors
- [VSCode](https://code.visualstudio.com) - A lightweight code-editor that can become a multipurpose IDE with the use of extensions - Owned by Microsoft
- [Atom](https://atom.io) - A lightweight code-editor that can become a multipurpose IDE with the use of extensions - Owned by GitHub, that is owned by Microsoft (questionable support).

## Git Tools

- [Gitkraken](https://www.gitkraken.com) — A super useful Git Client (best on market imo)
- [Github Desktop](https://desktop.github.com) — A simple and lightweight Git Client.

## Database Tools

- [DBeaver](https://dbeaver.io) - Free multi-platform database tool for developers, database administrators, analysts and all people who need to work with databases.

## UML Tools

- [PlantUML](https://plantuml.com) — a text based UML tool.
- [Draw.io](https://about.draw.io) — an open platform where you can create and share UML diagrams.

## Programming Languages and Frameworks

- [C#](https://en.wikipedia.org/wiki/C_Sharp_(programming_language))
  - [Dotnet Core](https://docs.microsoft.com/da-dk/dotnet/core/) — an open-source, general-purpose development platform maintained by Microsoft and the .NET community.
    - [Blazor](https://dotnet.microsoft.com/apps/aspnet/web-apps/blazor) — Build client web apps with C#
- [Java](https://www.java.com/en/)
  - [JavaFX](https://openjfx.io) - an open source client application platform for desktop, mobile and embedded systems built on Java.
  - [LibGDX](https://libgdx.badlogicgames.com) — an open-source cross-platform Game Development framework.
  
- [Python](https://www.python.org)
  - [Flask](https://www.palletsprojects.com/p/flask/) — a lightweight [WSGI](https://wsgi.readthedocs.io/en/latest/) web application framework.
- [PHP](https://www.php.net)
  - [Laravel](https://laravel.com) — The PHP Framework for Web Artisans.

## Search Engines

- [Elastic Search](https://www.elastic.co) - a distributed, open source search and analytics engine for all types of data, including textual, numerical, geospatial, structured, and unstructured.