# WebUI 3.0 KE
## Process Planning (SDLC)

### Software development process
In software engineering, a software development process is the process of dividing software development work into distinct phases to improve design, product management, and project management. It is also known as a software development life cycle.

Software development activities
1. Requirements analysis resulting in a software requirements specification
2. Software design
3. Implementation
4. Testing
5. Integration, if there are multiple subsystems
6. Deployment (or Installation)
7. Maintenance

### Basics of SDLC models
The systems development life cycle (SDLC) is a conceptual model used in project management that describes the stages involved in an information system development project, from an initial feasibility study through maintenance of the completed application.

There are following six phases in every Software development life cycle model:
1. Requirement gathering and analysis.
2. Design.
3. Implementation or coding.
4. Testing.
5. Deployment.
6. Maintenance.

The software development life cycle (SDLC) is a framework defining tasks performed at each step in the software development process. SDLC is a structure followed by a development team within the software organization. It consists of a detailed plan describing how to develop, maintain and replace specific software.

What are the different types of SDLC?
* Waterfall Model.
* V-Shaped Model.
* Evolutionary Prototyping Model.
* Spiral Method (SDM)
* Iterative and Incremental Method.
* Agile development.

The two basic, most popular methodologies are: Waterfall: (ugh, terrible name!), which might be more properly called the “traditional” approach, and. Agile: a specific type of Rapid Application Development and newer than Waterfall, but not that new, which is often implemented using Scrum.

Agile SDLC model is a combination of iterative and incremental process models with focus on process adaptability and customer satisfaction by rapid delivery of working software product. Agile Methods break the product into small incremental builds. These builds are provided in iterations.

#### Waterfall

Much like construction and manufacturing workflows, waterfall methodology is a sequential design process. This means that as each of the eight stages (conception, initiation, analysis, design, construction, testing, implementation, and maintenance) are completed, the developers move on to the next step.
In software development, it tends to be among the less iterative and flexible approaches, as progress flows in largely one direction ("downwards" like a waterfall) through the phases of conception, initiation, analysis, design, construction, testing, deployment and maintenance.

#### Agile

Agile Software Development is an umbrella term for a set of methods and practices based on the values and principles expressed in the Agile Manifesto. Solutions evolve through collaboration between self-organizing, cross-functional teams utilizing the appropriate practices for their context.

* Individuals and Interactions over processes and tools
* Working Software over comprehensive documentation
* Customer Collaboration over contract negotiation
* Responding to Change over following a plan

----
* Tools and processes are important, but it is more important to have competent people working together effectively.
* Good documentation is useful in helping people to understand how the software is built and how to use it, but the main point of development is to create software, not documentation.
* A contract is important but is no substitute for working closely with customers to discover what they need.
* A project plan is important, but it must not be too rigid to accommodate changes in technology or the environment, stakeholders' priorities, and people's understanding of the problem and its solution.

----
Agile software development principles:

* Customer satisfaction by early and continuous delivery of valuable software
* Welcome changing requirements, even in late development
* Working software is delivered frequently (weeks rather than months)
* Close, daily cooperation between business people and developers
* Projects are built around motivated individuals, who should be trusted
* Face-to-face conversation is the best form of communication (co-location)
* Working software is the primary measure of progress
* Sustainable development, able to maintain a constant pace
* Continuous attention to technical excellence and good design
* Simplicity—the art of maximizing the amount of work not done—is essential
* Best architectures, requirements, and designs emerge from self-organizing teams
* Regularly, the team reflects on how to become more effective, and adjusts accordingly

### Scrum

Scrum is a subset of Agile. It is a lightweight process framework for agile development, and the most widely-used one. A “process framework” is a particular set of practices that must be followed in order for a process to be consistent with the framework.

#### Scrum values:
* commitment
* courage
* focus
* openness
* respect

#### Scrum roles:
* The Product Owner: 
Is responsible for maximizing the value of the product and the work of the development team. How product owners accomplish this may vary across Scrum Teams and individuals. The product owner is the sole person responsible in managing the Product Backlog. The product owner is one person, not a committee. For the Product Owner to succeed, organization must respect his or her decisions.  

* The Development Team: 
The developers work on delivering a potentially releasable "Done" product at the end of each Sprint. Development teams are empowered by organizations to manage their own work. The development team is small enough to remain nimble and large enough to complete significant work. It is not preferable to have fewer than tree and more than nine team members.  

* The Scrum Master:
Is responsible for ensuring Scrum is understood and enacted. They do this by ensuring that the Scrum Team adheres to Scrum theory, practices, and rules. The Scrum Master is a servant-leader for the Scrum Team. Scrum master helps those outside the Scrum team to understand which of their interactions with the scrum team are helpful and which are not. 

#### Scrum’s artifacts
represent work or value in various ways that are useful in providing transparency and opportunities for inspection and adaptation. Artifacts defined by Scrum are specifically designed to maximize transparency of key information needed to ensure Scrum Teams are successful in delivering a “Done” Increment.[23]

* Product Backlog: 
The Product Backlog is an ordered list of everything that might be needed in the product and is the single source of requirements for any changes to be made to the product. The Product Backlog is never complete, it only lays out the known and best understood requirements. Product Backlog is dynamic, it consistently changes to identify what the product needs to be useful. 

* The Product Backlog lists all features, functions, requirements, enhancements, and fixes that constitute the changes to be made to the product in the future releases. As product is used and gains value, feedback is provided and the Backlog becomes larger. Requirements never stop changing. Changes in business requirements, market conditions, or technology may cause changes in the Product Backlog.

* Monitoring Progress Toward a Goal:
At any time, the total work remaining to reach the goal can be summed. Various projection practices have been used to forecast progress, but whats will happen is unknown. Only what has happened can be use for forward-looking decision-making. 

* Sprint Backlog:
The Sprint Backlog is the set of Product Backlog items selected for the Sprint plus a plan for delivering the product Increment and realizing the Sprint Goal. The Sprint Backlog is a forecast by the Development Team about what functionality will be in the next Increment and the work needed to deliver that functionality. The Sprint Backlog defines the work the Development Team will perform to turn Product Backlog items into a “Done” Increment. The Sprint Backlog makes visible all of the work that the Development Team identifies as necessary to meet the Sprint Goal.

* Monitoring Sprint Progress:
Development team tracks total work remaining at least for every Daily Scrum. Development team tracks these sums daily and projects likelihood of achieving the Sprint Goals. 

* Increment:
The Increment is the sum of all the Product Backlog items completed during a Sprint and all previous Sprints. At the end of a Sprint, the new Increment must be “Done,” which means it must be in usable condition and meet the Scrum Team’s Definition of “Done.” It must be in usable condition regardless of whether the Product Owner decides to actually release it.

#### Scrum events
* Sprint Planning
* Daily Scrum
* Sprint Review
* Sprint Retrospective

#### Estimation 
* Story Points
* Velocity
* Sprint Burndown Chart
* Feature Burnup Chart


#### Шаблоны - Patterns

Порождающие
Удобное и безопасное создание обьектов
* Фабричный метод - Factory method
* Абстрактная фабрика - Abstract factory
* Строитель - Builder
* Прототип - Prototype
* Одиночка - Singleton

Структурные
создают и поддерживают иерархические связи
* Адаптер - Adapter
* Мост - Bridge
* Компоновщик - Composite
* Декоратор - Decorator
* Фасад - Facade
* Легковес - Flyweight
* Заместитель - Proxy

Поведенческие
эффективное и безопасное взаимодействие
* Цепочка обязанностей - Chain of responsibility
* Команда - Command
* Итератор - Iterator
* Посредник - Mediator
* Снимок - Memento
* Наблюдатель - Observer
* Состояние - State
* Стратегия - Strategy
* Шаблонный метод - Template method
* Посетитель - Visitor