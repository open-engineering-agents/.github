Open Engineering Agents

Open Engineering Agents is the agent layer of the Open Engineering ecosystem.

We explore how AI agents can become first-class engineering elements: defined, composed, orchestrated, executed, observed, and continuously improved as part of an open engineering system.

Agents are not chatbots. Agents are engineering elements.

⸻

What we build

Open Engineering Agents provides the foundations for engineering with autonomous and collaborative agents.

An agent can:

* Observe — understand systems, repositories, products, environments, and events
* Investigate — reason about evidence and discover what is happening
* Plan — turn observations and goals into executable work
* Execute — perform actions through tools, APIs, repositories, and runtimes
* Collaborate — communicate with people and other agents
* Remember — retain relevant context, decisions, evidence, and outcomes
* Report — make its reasoning, actions, and results understandable
* Compose — work together with other agents and engineering elements
* Learn — improve through feedback and accumulated experience

The goal is not to create one universal agent.

The goal is to create an open engineering fabric in which many specialized agents can work together.

⸻

From AI assistants to engineering agents

Traditional AI assistants primarily respond to prompts.

Open Engineering Agents takes a different approach:

Prompt
  │
  ▼
Assistant
  │
  ▼
Answer

becomes:

Engineering Goal
       │
       ▼
     Agent
       │
 ┌─────┼─────────┐
 ▼     ▼         ▼
Observe Investigate Execute
 │       │         │
 └───────┼─────────┘
         ▼
      Evidence
         │
         ▼
       Result
         │
         ▼
      Feedback
         │
         └──────────► Agent

An engineering agent is therefore part of a continuous engineering process, rather than a standalone conversational interface.

⸻

The Open Engineering Agent Model

An agent combines several fundamental elements:

                 ┌─────────────────────┐
                 │       AGENT         │
                 │                     │
                 │  Identity           │
                 │  Purpose            │
                 │  Capabilities       │
                 │  Context            │
                 │  Policies           │
                 │  Memory             │
                 │  Tools              │
                 │  Workflow           │
                 │  Evidence           │
                 └──────────┬──────────┘
                            │
              ┌─────────────┼─────────────┐
              ▼             ▼             ▼
          Observe       Investigate     Execute
              │             │             │
              └─────────────┼─────────────┘
                            ▼
                         Report

This model allows agents to be described and engineered independently from the particular AI model that powers them.

⸻

Agent specializations

Open Engineering explores specialized agents for different engineering responsibilities.

Examples include:

Agent	Responsibility
Executive Agent	Goals, priorities, decisions, and organizational direction
Product Agent	Product discovery, requirements, journeys, and product decisions
Architect Agent	Architecture, boundaries, trade-offs, and system design
Engineering Agent	Implementation, refactoring, testing, and delivery
Detective Agent	Investigation, diagnosis, evidence, and root-cause analysis
Documentation Agent	Technical knowledge, documentation, and communication
Release Agent	Release preparation, verification, and deployment
Character Agent	Intelligent characters, behavior, personality, and interaction

These are not necessarily separate products.

They are specializations of the same underlying agent model.

⸻

Agents within Open Engineering

Open Engineering Agents is designed to work with the other layers of the Open Engineering ecosystem.

                 OPEN ENGINEERING
                        │
        ┌───────────────┼────────────────┐
        │               │                │
     Ontology       Product Model    Systems of Record
        │               │                │
        └───────────────┼────────────────┘
                        │
                     Agents
                        │
              ┌─────────┼─────────┐
              │         │         │
          Operating   Capsules  Applications
           Systems
              │         │         │
              └─────────┼─────────┘
                        │
                     Runtime

Agents can therefore operate across the entire engineering landscape rather than being trapped inside a single application.

⸻

Agent + Capsule

Open Engineering distinguishes between agents and capabilities.

An agent provides purpose, identity, orchestration, decision-making, and execution.

A capsule provides reusable capability.

Examples:

* Vision Capsule
* Voice Capsule
* Memory Capsule
* AI Capsule
* Identity Capsule
* Documentation Capsule
* Simulation Capsule
* Robotics Capsule
* Story Capsule
* Character Capsule
* Systems Thinking Capsule

This creates a compositional model:

Agent
 ├── Identity
 ├── Purpose
 ├── Memory
 ├── Workflow
 ├── Policies
 │
 └── Capabilities
      ├── Vision Capsule
      ├── Memory Capsule
      ├── AI Capsule
      ├── Documentation Capsule
      └── ...

Agents can therefore be assembled from reusable engineering capabilities instead of repeatedly rebuilding the same functionality.

⸻

Agent fabrics

Individual agents become considerably more powerful when they can collaborate.

Open Engineering Agents therefore explores agent fabrics:

                 ┌────────────────┐
                 │ Executive Agent│
                 └───────┬────────┘
                         │
             ┌───────────┼───────────┐
             ▼           ▼           ▼
        Product       Architect   Detective
         Agent          Agent       Agent
             │           │           │
             └─────┬─────┴─────┬─────┘
                   ▼           ▼
              Engineering   Documentation
                 Agent          Agent
                   │             │
                   └──────┬──────┘
                          ▼
                     Release Agent

The fabric becomes an engineering system in which specialized agents can delegate, collaborate, challenge, verify, and hand work to one another.

⸻

Model independence

Agents should not be permanently coupled to a single AI provider.

The Open Engineering approach is therefore intentionally model-agnostic.

An agent may use:

* local models
* hosted models
* specialized reasoning models
* coding models
* multimodal models
* speech models
* vision models
* multiple models simultaneously

The agent definition remains an engineering artifact, while the underlying model can evolve independently.

⸻

Tools and systems

Agents become useful when they can interact with the engineering world.

Open Engineering Agents is designed to connect agents with systems such as:

* GitHub
* Backstage
* Kubernetes
* Crossplane
* CI/CD systems
* source repositories
* product-management systems
* documentation systems
* observability platforms
* MCP servers
* APIs
* databases
* engineering tools
* physical devices

The principle is simple:

An agent should be able to act on the same systems that engineers act on.

⸻

Evidence-first engineering

Autonomous action without evidence is difficult to trust.

Open Engineering Agents therefore treats evidence as a first-class engineering element.

Agent activities can produce:

Observation
     │
     ▼
Evidence
     │
     ▼
Investigation
     │
     ▼
Finding
     │
     ▼
Decision
     │
     ▼
Action
     │
     ▼
Outcome

This makes agent activity inspectable and supports human review, automated verification, and reproducibility.

⸻

Human + Agent engineering

Open Engineering is not about replacing engineers with agents.

It is about creating a workforce in which:

humans and agents work together.

Humans can provide:

* intent
* creativity
* judgment
* responsibility
* context
* approval

Agents can provide:

* scale
* persistence
* analysis
* automation
* investigation
* execution
* continuous observation

The resulting engineering system is a collaboration between human and machine intelligence.

⸻

Open Engineering Agent Lifecycle

Agents can evolve through a continuous lifecycle:

Define
  ↓
Compose
  ↓
Test
  ↓
Deploy
  ↓
Observe
  ↓
Evaluate
  ↓
Improve
  └──────────────►

Agent definitions, workflows, prompts, capabilities, policies, evidence, and outcomes can all become part of the engineering knowledge base.

⸻

Repository structure

The Open Engineering Agents organization can contain projects for:

* agent definitions
* agent runtimes
* agent fabrics
* agent protocols
* agent capabilities
* agent memories
* agent identities
* agent workflows
* agent evaluation
* agent registries
* agent integrations
* agent applications

Each repository should ideally remain focused on a clearly defined engineering element.

⸻

Open Engineering principles

1. Open

Prefer open standards, interoperable interfaces, and replaceable implementations.

2. Composable

Build agents from reusable elements rather than monolithic systems.

3. Observable

Agents should make their activities and outcomes understandable.

4. Evidence-driven

Important decisions and actions should be grounded in evidence.

5. Model-independent

The agent should not be defined by the particular AI model behind it.

6. Human-compatible

Agents should augment engineering teams rather than obscure or replace human responsibility.

7. Reusable

Knowledge, capabilities, workflows, and patterns should be reusable across projects.

8. Continuously evolving

An agent system should improve as engineering experience accumulates.

⸻

Part of Open Engineering

Open Engineering Agents is one element of the wider Open Engineering ecosystem.

Together, the ecosystem explores a new way of engineering complex systems:

                     Open Engineering
                            │
       ┌────────────────────┼────────────────────┐
       │                    │                    │
   Knowledge             Agents              Systems
       │                    │                    │
   Ontology             Agent Fabrics       Systems of Record
   Product Model        Capsules            Runtime
   Stories              Assistants          Operating Systems
       │                    │                    │
       └────────────────────┼────────────────────┘
                            │
                     Engineering Work

The objective is a world where engineering knowledge, systems, software, people, and AI agents can participate in one coherent engineering environment.

⸻

Contributing

Open Engineering Agents is an open engineering experiment.

Ideas, implementations, experiments, patterns, agent definitions, integrations, and critical feedback are welcome.

If you are building something that makes agents more open, composable, observable, interoperable, or useful for engineering, it belongs in the conversation.

⸻

Explore

Open Engineering

open-engineering.io

Open Engineering Agents

github.com/open-engineering-agents

⸻

Build agents as engineering elements.
Compose them into engineering systems.
Let human and machine intelligence engineer together.
