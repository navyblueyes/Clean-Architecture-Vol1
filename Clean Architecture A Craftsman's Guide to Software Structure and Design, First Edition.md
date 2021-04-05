# Clean Architecture: A Craftsman's Guide to Software Structure and Design, First Edition

### PART I Introduction

<details>
<summary>Expand</summary>

#### Chapter 1 What Is Design and Architecture?

<details>
<summary>Expand</summary>

1. Intro
    1. What is the difference between Architecture and Design
        1. “architecture” is often used in the context of something at a high level
        1. “design” more often seems to imply structures and decisions at a lower level
1. The Goal?
    1. Basic Definition
        1. goal of **software architecture** is to minimize the human resources required to build and maintain the required system.
    1. Measure of design quality
        1. measure of effort required to meet needs of customer
1. Case Study
    1. Company explodes in engineering staff
        1. More code per employee
1. Signature of a Mess
    1. More code--- more time updating and fixing mess
        1. TDD means less cleaning to do later

</details>

#### Chapter 2 A Tale of Two Values

<details>
<summary>Expand</summary>

1. Intro
    1. Two Measurements
        1. Behavior
        1. Structure
1. Behavior
    1. We expect software to react
        1. if not..
            1. debug and refactor until then
1. Architecture
    1. makes it difficult to change
1. Eisenhower’s Matrix
    1. Behavior
        1. urgent; not always important
    1. Architecture
        1. important; not always urgent
1. Fight for the Architecture
    1. Architecture is important

</details>

</details>

### PART II Starting with the Bricks: Programming Paradigms

<details>
<summary>Expand</summary>

#### Chapter 3 Paradigm Overview

<details>
<summary>Expand</summary>

1. Structured Programming
    1. 1968
    1. First Programming structure by Edsger Dijkstra
    1. `if/then/else` and `do/while/until`
1. Object-Oriented Programming
    1. 1966
    1. Dahl and Nygaard
    1. organize into class
1. Functional Programming
    1. 1958 with Alonzo Church
1. Conclusion
    1. Use polymorphism
        1. to cross architectural boundaries
    1. functional programming
        1. to impose discipline on ...
            1. the location of data
            1. the access to data
    1. structured programming
        1. to implement algorithmic solution

</details>

#### Chapter 4 Structured Programming

<details>
<summary>Expand</summary>
1. Proof
    1. Wrote a proof replacing `goto` with `if/else`
1. Tests
    1. tests prove the presence not absence of bugs
        1. can never be proven correct 

</details>

#### Chapter 5 Object-Oriented Programming

<details>
<summary>Expand</summary>

        Encapsulation?
        Inheritance?
        Polymorphism?
        Conclusion

</details>

#### Chapter 6 Functional Programming

<details>
<summary>Expand</summary>

        Squares of Integers
        Immutability and Architecture
        Segregation of Mutability
        Event Sourcing
        Conclusion

</details>


</details>

### PART III Design Principles

<details>
<summary>Expand</summary>


#### Chapter 7 SRP: The Single Responsibility Principle

<details>
<summary>Expand</summary>

        Symptom 1: Accidental Duplication
        Symptom 2: Merges
        Solutions
        Conclusion

</details>

#### Chapter 8 OCP: The Open-Closed Principle

<details>
<summary>Expand</summary>

        A Thought Experiment
        Directional Control
        Information Hiding
        Conclusion

</details>

#### Chapter 9 LSP: The Liskov Substitution Principle

<details>
<summary>Expand</summary>

        Guiding the Use of Inheritance
        The Square/Rectangle Problem
        LSP and Architecture
        Example LSP Violation
        Conclusion

</details>

#### Chapter 10 ISP: The Interface Segregation Principle

<details>
<summary>Expand</summary>

        ISP and Language
        ISP and Architecture
        Conclusion

</details>

#### Chapter 11 DIP: The Dependency Inversion Principle

<details>
<summary>Expand</summary>

        Stable Abstractions
        Factories
        Concrete Components
        Conclusion

</details>

</details>

### PART IV Component Principles

<details>
<summary>Expand</summary>


#### Chapter 12 Components

<details>
<summary>Expand</summary>
        A Brief History of Components
        Relocatability
        Linkers
        Conclusion


</details>

#### Chapter 13 Component Cohesion

<details>
<summary>Expand</summary>
        The Reuse/Release Equivalence Principle
        The Common Closure Principle
        The Common Reuse Principle
        The Tension Diagram for Component Cohesion
        Conclusion

</details>

#### Chapter 14 Component Coupling

<details>
<summary>Expand</summary>
        The Acyclic Dependencies Principle
        Top-Down Design
        The Stable Dependencies Principle
        The Stable Abstractions Principle
        Conclusion

</details>

</details>

### PART V Architecture

<details>
<summary>Expand</summary>

#### Chapter 15 What Is Architecture?

<details>
<summary>Expand</summary>

        Development
        Deployment
        Operation
        Maintenance
        Keeping Options Open
        Device Independence
        Junk Mail
        Physical Addressing
        Conclusion

</details>

#### Chapter 16 Independence

<details>
<summary>Expand</summary>


        Use Cases
        Operation
        Development
        Deployment
        Leaving Options Open
        Decoupling Layers
        Decoupling Use Cases
        Decoupling Mode
        Independent Develop-ability
        Independent Deployability
        Duplication
        Decoupling Modes (Again)
        Conclusion

</details>

#### Chapter 17 Boundaries: Drawing Lines

<details>
<summary>Expand</summary>

        A Couple of Sad Stories
        FitNesse
        Which Lines Do You Draw, and When Do You Draw Them?
        What About Input and Output?
        Plugin Architecture
        The Plugin Argument
        Conclusion

</details>

#### Chapter 18 Boundary Anatomy

<details>
<summary>Expand</summary>

        Boundary Crossing
        The Dreaded Monolith
        Deployment Components
        Threads
        Local Processes
        Services
        Conclusion

</details>

#### Chapter 19 Policy and Level

<details>
<summary>Expand</summary>

        Level
        Conclusion

</details>

#### Chapter 20 Business Rules

<details>
<summary>Expand</summary>

        Entities
        Use Cases
        Request and Response Models
        Conclusion

</details>

#### Chapter 21 Screaming Architecture

<details>
<summary>Expand</summary>

        The Theme of an Architecture
        The Purpose of an Architecture
        But What About the Web?
        Frameworks Are Tools, Not Ways of Life
        Testable Architectures
        Conclusion

</details>

#### Chapter 22 The Clean Architecture

<details>
<summary>Expand</summary>

        The Dependency Rule
        A Typical Scenario
        Conclusion

</details>

#### Chapter 23 Presenters and Humble Objects

<details>
<summary>Expand</summary>

        The Humble Object Pattern
        Presenters and Views
        Testing and Architecture
        Database Gateways
        Data Mappers
        Service Listeners
        Conclusion

</details>

#### Chapter 24 Partial Boundaries

<details>
<summary>Expand</summary>

        Skip the Last Step
        One-Dimensional Boundaries
        Facades
        Conclusion

</details>

#### Chapter 25 Layers and Boundaries

<details>
<summary>Expand</summary>

        Hunt the Wumpus
        Clean Architecture?
        Crossing the Streams
        Splitting the Streams
        Conclusion

</details>

#### Chapter 26 The Main Component

<details>
<summary>Expand</summary>

        The Ultimate Detail
        Conclusion

</details>

#### Chapter 27 Services: Great and Small

<details>
<summary>Expand</summary>

        Service Architecture?
        Service Benefits?
        The Kitty Problem
        Objects to the Rescue
        Component-Based Services
        Cross-Cutting Concerns
        Conclusion

</details>

#### Chapter 28 The Test Boundary

<details>
<summary>Expand</summary>

        Tests as System Components
        Design for Testability
        The Testing API
        Conclusion

</details>

#### Chapter 29 Clean Embedded Architecture

<details>
<summary>Expand</summary>

        App-titude Test
        The Target-Hardware Bottleneck
        Conclusion


</details>

</details>

### PART VI Details

<details>
<summary>Expand</summary>

#### Chapter 30 The Database Is a Detail

<details>
<summary>Expand</summary>

        Relational Databases
        Why Are Database Systems So Prevalent?
        What If There Were No Disk?
        Details
        But What about Performance?
        Anecdote
        Conclusion

</details>

#### Chapter 31 The Web Is a Detail

<details>
<summary>Expand</summary>

        The Endless Pendulum
        The Upshot
        Conclusion

</details>

#### Chapter 32 Frameworks Are Details

<details>
<summary>Expand</summary>

        Framework Authors
        Asymmetric Marriage
        The Risks
        The Solution
        I Now Pronounce You …
        Conclusion

</details>

#### Chapter 33 Case Study: Video Sales

<details>
<summary>Expand</summary>

        The Product
        Use Case Analysis
        Component Architecture
        Dependency Management
        Conclusion

</details>

#### Chapter 34 The Missing Chapter

<details>
<summary>Expand</summary>

        Package by Layer
        Package by Feature
        Ports and Adapters
        Package by Component
        The Devil Is in the Implementation Details
        Organization versus Encapsulation
        Other Decoupling Modes
        Conclusion: The Missing Advice

</details>

</details>
