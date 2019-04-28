# Architecture

We suggest a semi-flexible architecture for the projects.

## Why this?

_[Issue #10: Micro-services or Monolithic, which paradigm?]_
If we pick micro-service architecture, it is because of its scalability.
We are NOT picking it because it allows us to use multiple stacks concurrently.
In fact, **we are against technology diversity**.

Instead of planning for a concrete architecture. We prefer to be a little flexible on it.

Investigating various architectures, we defined a new concept called _**Architecture Item**_. 
> Architecture items are like some _**pieces of puzzles**_ that we could layout them in different ways to meet our project needs.

Currently we find these architecture items necessary to think about:
- REST API endpoint (gRPC is still an option. But I'm not sure about its necessity!)
- Relational database
- NoSQL database
- Message Bus
- Distributed Cache
- Job
- Web Frontend
- Mobile Frontend
- Server to client messaging
- Server-side rendering
- Rule Engine
- Workflow

## Risks
Having the concept of architecture items, brings the **risk of picking the correct architecture items** for the projects. There might be a challenge for the team for picking architecture items before each project. But we think it is necessary to have such discussion before each project and it helps to create a high quality solution.
