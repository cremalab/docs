# Development at Crema

## Table of Contents

- [Development at Crema](#development-at-crema)
  - [Table of Contents](#table-of-contents)
  - [Introduction](#introduction)
  - [Golden Rule](#golden-rule)
  - [Agile](#agile)
    - [Agile Manifesto](#agile-manifesto)
      - [Agile Values](#agile-values)
      - [Agile Principles](#agile-principles)
  - [Coding Standards](#coding-standards)
    - [Simplicity](#simplicity)
    - [Quality](#quality)
    - [Readability](#readability)
    - [Continuous Learning](#continuous-learning)
    - [Code Reviews and Collaboration](#code-reviews-and-collaboration)
  - [Development Tools 🛠️](#development-tools-️)
    - [Integrated Development Environments (IDEs) 👩‍💻](#integrated-development-environments-ides-)
    - [Linters + Formatters 🧹](#linters--formatters-)
    - [Continuous Integration/Continuous Deployment (CI/CD) Tools 🔨](#continuous-integrationcontinuous-deployment-cicd-tools-)
    - [Project Management Tools 📊](#project-management-tools-)
  - [Version Control](#version-control)
    - [Branching Strategy](#branching-strategy)
      - [GitFlow](#gitflow)
      - [Trunk Based Development](#trunk-based-development)
  - [Testing](#testing)
    - [Testing Philosophy](#testing-philosophy)
    - [Testing Tools](#testing-tools)
    - [Coverage Expectations](#coverage-expectations)
  - [Code / PR Reviews](#code--pr-reviews)
  - [Documentation](#documentation)
  - [Communication](#communication)
    - [Internal](#internal)
      - [Developers](#developers)
      - [Product Managers](#product-managers)
      - [Designers](#designers)
      - [Test Engineers](#test-engineers)
    - [External](#external)
      - [Stakeholders](#stakeholders)
  - [Workflow](#workflow)
    - [Sprint Kickoffs](#sprint-kickoffs)
    - [Demos](#demos)
    - [Retrospectives](#retrospectives)
    - [Storypointing](#storypointing)
    - [Backlog Grooming](#backlog-grooming)
  - [Continuous Integration / Continuous Deployment](#continuous-integration--continuous-deployment)
  - [Security Practices](#security-practices)
  - [Performance](#performance)
  - [Engagements](#engagements)
    - [Onboarding](#onboarding)
    - [Offboarding](#offboarding)

## Introduction

At Crema, we are committed to delivering high-quality products that meet and exceed our clients' expectations.

This document serves as a guide to our development practices. It outlines the conventions, tools, and methodologies that shape our work, providing a framework to ensure every member of our team is aligned in their approach to development.

By establishing clear norms and defaults, we aim to streamline our processes, maintain high degree of quality, facilitate effective collaboration, and create an environment of continuous learning and improvement. These practices also help us navigate complex projects with multiple hands, enabling us to efficiently coordinate our efforts and maintain consistency across our work.

Whether you are a seasoned member of the Crema team or a newcomer, this document is intended to provide a clear understanding of our development practices. We encourage everyone to familiarize themselves with these guidelines and incorporate them into their daily work. At the same time, we believe that our norms and defaults should evolve with our team and industry. Therefore, we welcome any feedback or suggestions for improvement.

Let's continue to collaborate, innovate, and create extraordinary digital products together.

## Golden Rule

Use common sense, talk to your team, find agreement. These are just guidelines.

## Agile

At Crema we practice Agile methodology. These ideas were first captured in the Agile Manifesto, which outlines four core values and twelve guiding principles.

Agile is an adaptive, people-focused approach to software development, rooted in iterative progress, flexible responses to change, and a customer-oriented mindset.

### Agile Manifesto

<details>
<summary>
Click to Expand
</summary>

#### Agile Values

1. **Individuals and interactions** over processes and tools
2. **Working software** over comprehensive documentation
3. **Customer collaboration** over contract negotiation
4. **Responding to change** over following a plan

#### Agile Principles

1. **Customer satisfaction**: Our highest priority is to satisfy the customer through early and continuous delivery of valuable software.
2. **Embrace change**: Welcome changing requirements, even late in development. Agile processes harness change for the customer's competitive advantage.
3. **Frequent delivery**: Deliver working software frequently, from a couple of weeks to a couple of months, with a preference to the shorter timescale.
4. **Collaboration**: Business people and developers must work together daily throughout the project.
5. **Supportive environments**: Build projects around motivated individuals. Give them the environment and support they need, and trust them to get the job done.
6. **Face-to-face communication**: The most efficient and effective method of conveying information to and within a development team is face-to-face conversation.
7. **Working software**: Working software is the primary measure of progress.
8. **Sustainable development**: Agile processes promote sustainable development. The sponsors, developers, and users should be able to maintain a constant pace indefinitely.
9. **Technical excellence**: Continuous attention to technical excellence and good design enhances agility.
10. **Simplicity**: Simplicity--the art of maximizing the amount of work not done--is essential.
11. **Self-organizing teams**: The best architectures, requirements, and designs emerge from self-organizing teams.
12. **Regular reflection**: At regular intervals, the team reflects on how to become more effective, then tunes and adjusts its behavior accordingly.

As we continue our work at Crema, let's always bear in mind these values and principles. They should guide our practices, shape our culture, and help us continually improve our approach to development.

</details>

## Coding Standards

Our coding standards and development practices at Crema are a rich blend of philosophies from renowned industry sources as well as our own experiences over the years.

### Simplicity

Simplicity, the heart of our coding standards. We strive to eliminate waste, which includes unnecessary code, delayed feedback, and excessive processes. By creating straightforward solutions and keeping our code and processes uncluttered, we maintain focus on delivering valuable software to our clients efficiently. We appreciate the concept of "deep" modules, simple interfaces that encapsulate complex implementations.

### Quality

We build quality into our software from the start, guided by the pricinple that we should leave the codebase better than we found it. We combat complexity, keep modules/functions/classes focused, and do our best to write code that is robust, secure, and easy to understand. The code we write is supported by automated integration tests and code analysis tools.

### Readability

Our code should be readable not only to the author but to the entire team. This readability, together with elegance and effective use of design patterns, contributes to a codebase that is easy to maintain and extend over time. We embrace the idea of being a catalyst for change, seeking to continuously improve and adapt to evolving requirements and environments.

### Continuous Learning

Our code is altruistic; it not only fulfills its purpose but also considers its impact on existing code and future developments. We adopt a continuous learning mindset, viewing every project and iteration as an opportunity to improve our practices and the codebase.

### Code Reviews and Collaboration

Code reviews, backed by these principles, are a critical part of our development process. They allow us to maintain our software design philosophy while fostering a culture of collaboration and shared learning. Reviews ensure that our code adheres to these principles and help us catch and fix issues early.

In conclusion, we strive to create software that stands the test of time, is a joy to work with, and delivers great value to our clients. We welcome feedback and discussion from all team members on how to make our code better and maintain our commitment to continuous improvement.

## Development Tools 🛠️

At Crema, we understand that the tools we use significantly impact the quality of our work and our productivity. Therefore, we are committed to constantly researching and leveraging the most advanced and suitable development tools available in the market.

### Integrated Development Environments (IDEs) 👩‍💻

We believe that a powerful IDE can dramatically enhance our productivity and code quality. We encourage our developers to use an IDE that best suits their workflow and the specific needs of each project. The choice of IDE is flexible and is based on personal preference, project requirements, and the technologies in use. That said, we commonly use [VS Code](https://code.visualstudio.com/).

### Linters + Formatters 🧹

We recognize the value of linters and formatters in helping to maintain a clean, consistent, and error-free codebase. They automatically enforce coding standards, allowing developers to focus on the logic and functionality of the code. Our linters are configured integrated into our CI/CD pipeline to ensure that every line of code we write is clear, clean, and consistent. We are big fans of ESLint and Prettier.

### Continuous Integration/Continuous Deployment (CI/CD) Tools 🔨

To facilitate continuous delivery and deployment, we make use of CI/CD tools such as GitHub Actions. These tools allow us to automate building, testing, and deploying our software, providing faster feedback, reducing manual errors, and ensuring that we can deliver value to our clients more quickly and reliably.

### Project Management Tools 📊

For effective project management and collaboration, we use tools like Jira, Slack, and Miro. These tools enable us to track tasks, collaborate, and stay organized, ensuring that we deliver high-quality products on schedule.

We are committed to staying up-to-date with the latest advancements in development tools. We continually assess our toolset to ensure we're providing the most efficient, effective, and enjoyable development experience for our team and the best possible product for our clients.

## Version Control

Version control is a critical component of our development workflow. We use Git for version control, allowing us to effectively collaborate, track changes, and manage different versions of our code. We adhere to a clear Git workflow that facilitates seamless collaboration and ensures a clean commit history.

### Branching Strategy

Defining a clear and effective branching strategy is an integral part of our version control practices. A well-structured branching strategy promotes clean, manageable version control, facilitates parallel development, and helps prevent conflicts and integration issues.

#### GitFlow

One of the branching models we frequently use is GitFlow. This model involves two main branches: 'main' and 'develop'. The 'master' branch reflects the code currently in production, while the 'develop' branch serves as an integration branch for features.

In GitFlow, feature branches are created from 'develop' and merged back into it once the feature is complete. Release branches are cut from 'develop' when it's time to prepare a new production release, and hotfix branches are used for making emergency changes directly to the 'master' branch. This model is well-suited for larger projects with multiple developers working concurrently on different features.

#### Trunk Based Development

For projects where we want to encourage frequent integrations and limit the complexity of merging, we might choose Trunk Based Development. In this model, all developers work on a single branch, 'trunk' or 'main', with short-lived feature branches used to isolate work until it's ready to be merged. Developers regularly pull from and push to the 'trunk', ensuring everyone's work is integrated frequently and conflicts are identified and resolved promptly.

Our choice of branching model depends on several factors, including the project's scale, the team's size, and the desired release cycle. By following a well-defined branching strategy, we maintain a clean, understandable commit history, promote efficient collaboration, and ensure we can quickly and reliably deliver new features and fixes to our clients.

## Testing

At Crema, we firmly believe in the value and necessity of testing. A well-tested application not only instills confidence in its reliability and performance, but also ensures that new features or modifications do not inadvertently break existing functionality. Our testing philosophy is grounded in a commitment to thoroughness, clarity, and regularity.

### Testing Philosophy

Our testing philosophy is based on the principle that every piece of functionality should be tested in some way. This doesn't necessarily translate to achieving a certain percentage of test coverage; instead, we focus on the critical parts of our applications and make sure that they behave as expected under a variety of conditions.

While we strive for comprehensive testing, we also recognize the importance of maintaining a balance. Not all code demands the same level of testing, and it's essential to allocate our testing resources where they can bring the most value.

### Testing Tools

We leverage a variety of tools to create robust and comprehensive tests. Our toolbox includes, but is not limited to:

- **Jest**: A popular JavaScript testing framework with a focus on simplicity. It allows us to write tests with an easy-to-understand syntax, and provides a wide range of features such as a full-featured expectation library, mock functions, etc.

- **Cypress**: A powerful end-to-end testing tool for web applications. With Cypress, we can create tests that interact with our applications just like a real user would, giving us confidence that our applications work correctly in real-world conditions.

### Coverage Expectations

While we don't set a specific number for test coverage, we do expect all important parts of our applications to be tested. Our goal is to make sure that all critical paths are covered, and that any code that could affect the functionality or performance of our applications is adequately tested.

We encourage proactive testing, where tests are written in tandem with the code they're testing. This not only ensures that our tests are relevant and up-to-date, but also promotes better code design, as writing tests often exposes potential improvements or simplifications in the code.

Through our commitment to comprehensive, balanced testing, we ensure that the applications we deliver to our clients are reliable, robust, and ready to handle real-world conditions.

## Code / PR Reviews

At Crema, we recognize the value of reviewing pull requests (PRs) as a crucial aspect of our development process. PR reviews allow us to maintain the high-quality code that our clients have come to expect from us. By conducting thorough reviews, we ensure that our software is not only functionally robust but also follows best practices for readability, maintainability, and performance.

Reviewing PRs in a timely manner is a shared responsibility. We understand that our colleagues are waiting for our feedback to proceed with their tasks. Quick turnarounds on PR reviews help us maintain our project momentum, avoid code conflicts, and increase overall team productivity. It is our collective commitment to review and provide feedback on PRs as promptly as possible without compromising on the quality of our reviews.

There are many ways to conduct a good code review, here's one pyramid model that has worked over the years. Focus on the base layers and aim to achieve the top of the pyramid:

1. **Correct (Base of the Pyramid)**: This is the most fundamental level, where we verify that the code is functionally correct. Does it do what it's intended to do? We test it against the requirements, consider edge cases, and confirm that it meets the acceptance criteria.

2. **Secure**: Here, we examine the code for any potential security vulnerabilities. We check that data is being handled securely and that there are no leaks or potential breaches. We consider things such as the principle of least privilege, ensuring that processes only have access to the resources they need.

3. **Readable**: At this level, we ensure that the code is clear and easy to understand. We adhere to naming conventions and formatting rules, use clear comments where necessary, and maintain consistent coding styles. Code should not only be understandable to the author but to the entire team.

4. **Elegant**: Here, we are interested in the architecture and design of the code. We aim for elegant solutions that are efficient, avoid redundancy, and show a deep understanding of the programming language and tools. The elegance of code is seen in its simplicity and the use of effective design patterns.

5. **Altruist (Top of the Pyramid)**: Lastly, we review the code from an altruistic standpoint. Does the code contribute to the overall health of the codebase? Does it leave the codebase better than it was found? Altruistic code not only fulfills its own purpose but also considers its impact on existing code, making sure to minimize technical debt.

We believe that every PR review is an opportunity for knowledge sharing and learning. It's a moment where we can constructively discuss different approaches and potential improvements. By leveraging this framework for PR reviews, we can continue delivering high-quality software while also promoting a culture of continuous learning and collaboration.

## Documentation

_Description of when and how to document code, including in-code comments and external documentation._

## Communication

_Description of expected communication practices within the development team, other craft teams, and with stakeholders._

### Internal

#### Developers

#### Product Managers

#### Designers

#### Test Engineers

### External

#### Stakeholders

## Workflow

_Description of the development workflow, including any regular meetings or ceremonies._

### Sprint Kickoffs

### Demos

### Retrospectives

### Storypointing

### Backlog Grooming

## Continuous Integration / Continuous Deployment

_Description of CI/CD practices, including any tools GitHub Actions, etc._

## Security Practices

_Description of security best practices for code development._

## Performance

_Description of performance expectations and how performance should be considered during development._

## Engagements

### Onboarding

_Description of things to consider when setting up a new product._

### Offboarding

_Description of things to consider when handing off a product._
