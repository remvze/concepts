# Concepts

A curated collection of essential software engineering concepts and learning resources.

---

## Software Design & Architecture 🏗️

### Architectural Patterns

#### Monolithic Architecture:

> **ELI5:** A monolithic architecture is like one big block of software where everything—user interface, logic, and database—are built together in a single unit. If one part changes or breaks, you often have to rebuild or redeploy the entire application.

- `📃` [What is monolithic architecture?](https://www.ibm.com/think/topics/monolithic-architecture)
- `📃` [Monolithic Architecture - System Design](https://www.geeksforgeeks.org/system-design/monolithic-architecture-system-design/)
- `📃` [Microservices vs. monolithic architecture](https://www.atlassian.com/microservices/microservices-architecture/microservices-vs-monolith)

#### Microservices Architecture

> **ELI5:** Microservices architecture is like building a big app out of many small, independent pieces. Each piece (microservice) does one job well and can be changed or fixed without breaking the others, making the whole system faster, easier to update, and more reliable.

- `📃` [What is Microservices Architecture?](https://cloud.google.com/learn/what-is-microservices-architecture)
- `📃` [What are Microservices?](https://www.geeksforgeeks.org/system-design/microservices/)

#### Service-Oriented Architecture (SOA)

> **ELI5:** ChatGPT said:Service-Oriented Architecture (SOA) is like a toolbox where each tool (service) does one job well—such as handling payments or sending emails—and all the tools can work together easily, even if they’re made by different people or use different technologies.

- `📃` [Service-oriented architecture](https://en.wikipedia.org/wiki/Service-oriented_architecture)
- `📃` [What is SOA (Service-Oriented Architecture)?](https://aws.amazon.com/what-is/service-oriented-architecture/)
- `📃` [Service-Oriented Architecture](https://www.geeksforgeeks.org/software-engineering/service-oriented-architecture/)
- `📃` [What is service-oriented architecture (SOA)?](https://www.ibm.com/think/topics/soa)

#### Event-Driven Architecture (EDA)

> **ELI5:** Event-Driven Architecture (EDA) is like a chain reaction where things happen in response to events. When something important occurs (an “event”), it instantly triggers other parts of the system to react, helping apps stay fast, flexible, and responsive without waiting for instructions.

- `📃` [Event-driven architecture](https://en.wikipedia.org/wiki/Event-driven_architecture)
- `📃` [What is event-driven architecture?](https://www.ibm.com/think/topics/event-driven-architecture)
- `📃` [What is EDA (Event-Driven Architecture)?](https://aws.amazon.com/what-is/eda/)
- `📃` [Event-Driven Architecture - System Design](https://www.geeksforgeeks.org/system-design/event-driven-architecture-system-design/)

#### Serverless Architecture

> **ELI5:** Serverless architecture means you run code without managing servers yourself. You just upload your code, and cloud providers like AWS or Google automatically handle servers, scaling, and maintenance — you only pay when your code runs.

- `📃` [Serverless Architecture Overview](https://www.datadoghq.com/knowledge-center/serverless-architecture/)
- `📃` [Serverless Architecture](https://www.geeksforgeeks.org/system-design/serverless-architectures/)
- `📃` [What is Serverless Architecture?](https://cloud.google.com/discover/what-is-serverless-architecture)

#### Layered (N-Tier) Architecture

> **ELI5:** Layered (N-Tier) Architecture splits an application into separate layers—like presentation (UI), logic (rules), and data (storage)—so each handles a specific job. This separation makes software easier to build, update, and maintain without breaking other parts.

- `📃` [Layered (N-tier) Architecture](https://blog.longbui.net/layered-pattern)
- `📃` [Understanding N-Tier Architecture: Building Robust and Scalable Applications](https://medium.com/@segekaratas/understanding-n-tier-architecture-building-robust-and-scalable-applications-62db30a40b5)

---

## Software Development Life Cycle (SDLC) & Methodologies 🔄

### SDLC Models

#### Waterfall Model

> **ELI5:** The Waterfall Model is a step-by-step way to build software, like following a recipe. You finish one stage—planning, designing, building, testing, then delivering—before moving to the next. Once a step is done, you don’t go back, just like water only flows downward.

- `📃` [Waterfall Model - Software Engineering](https://www.geeksforgeeks.org/software-engineering/waterfall-model/)
- `📃` [Waterfall mode](https://en.wikipedia.org/wiki/Waterfall_model)

#### Agile Model

> **ELI5:** The Agile Model is a flexible way to develop software by breaking work into small, manageable parts called sprints. Teams build, test, and improve the product continuously, getting feedback often to quickly adapt to changes and deliver better results faster.

- `📃` [SDLC - Agile Model](https://www.tutorialspoint.com/sdlc/sdlc_agile_model.htm)
- `📃` [Agile Development Models - Software Engineering](https://www.geeksforgeeks.org/software-engineering/software-engineering-agile-development-models/)
- `📃` [What is Agile methodology? (A beginner’s guide)](https://asana.com/resources/agile-methodology)

#### Lean Software Development

> **ELI5:** ChatGPT said:Lean Software Development is a way to build software efficiently by focusing only on what adds value, cutting waste, improving quality, and empowering the team to make fast decisions. It emphasizes learning quickly, delivering small improvements often, and continuously improving the process.

- `📃` [Lean software development](https://en.wikipedia.org/wiki/Lean_software_development)
- `📃` [Lean Software Development (LSD)](https://www.geeksforgeeks.org/software-engineering/lean-software-development-lsd/)

#### Extreme Programming (XP)

> **ELI5:** Extreme Programming (XP) is a way to make software by working in small steps, testing often, and constantly improving. Teams write code together, share ideas, and adapt quickly to changes, aiming for high-quality software that meets users’ needs efficiently and with less risk of mistakes.

- `📃` [Extreme programming](https://en.wikipedia.org/wiki/Extreme_programming)
- `📃` [What is Extreme Programming (XP)?](https://www.geeksforgeeks.org/software-engineering/software-engineering-extreme-programming-xp/)

#### Spiral Model

> **ELI5:** The Spiral Model is a way to develop software step by step, like moving around a spiral. Each loop plans, builds, tests, and reviews, letting developers catch problems early and improve the design before starting the next loop. It’s flexible and risk-focused.

- `📃` [Spiral model](https://en.wikipedia.org/wiki/Spiral_model)
- `📃` [What is Spiral Model in Software Engineering?](https://www.geeksforgeeks.org/software-engineering/software-engineering-spiral-model/)
- `📃` [What is the spiral model and how is it used?](https://www.techtarget.com/searchsoftwarequality/definition/spiral-model)
- `📃` [SDLC - Spiral Model](https://www.tutorialspoint.com/sdlc/sdlc_spiral_model.htm)

#### V-Model (Verification and Validation Model)

> **ELI5:** The V-Model is a software development approach shaped like a “V” that links each development step with a corresponding testing step. On the left, you plan and design; at the bottom, you build; on the right, you test and validate, ensuring the product meets requirements.

- `📃` [SDLC - V-Model](https://www.tutorialspoint.com/sdlc/sdlc_v_model.htm)
- `📃` [SDLC V-Model - Software Engineering](https://www.geeksforgeeks.org/software-engineering/software-engineering-sdlc-v-model/)
