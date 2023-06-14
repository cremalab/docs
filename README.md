# Development at Crema

## Table of Contents

- [Development at Crema](#development-at-crema)
  - [Table of Contents](#table-of-contents)
  - [Introduction](#introduction)
  - [Golden Rule](#golden-rule)
  - [Agile](#agile)
    - [Agile Values](#agile-values)
    - [Agile Principles](#agile-principles)
  - [Coding Standards](#coding-standards)
    - [Typescript](#typescript)
  - [Development Tools](#development-tools)
  - [Source Control](#source-control)
    - [Branching Strategy](#branching-strategy)
  - [Testing](#testing)
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

At Crema we practice Agile methodology, here is the core of this practice. These ideas were first captured in the Agile Manifesto, which outlines four core values and twelve guiding principles.

Agile is an adaptive, people-focused approach to software development, rooted in iterative progress, flexible responses to change, and a customer-oriented mindset.

### Agile Values

1. **Individuals and interactions** over processes and tools
2. **Working software** over comprehensive documentation
3. **Customer collaboration** over contract negotiation
4. **Responding to change** over following a plan

### Agile Principles

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

## Coding Standards

_Description of coding conventions and style guides for different languages and frameworks._

### Typescript

_Description of tools, libraries, practices that are recommended for projects using Typescript._

## Development Tools

_Description of standard development tools, IDEs, linters, etc._

## Source Control

_Description of source control practices, including how Git is used._

### Branching Strategy

_Description of the branching strategy._

## Testing

_Description of testing philosophies, tools, and coverage expectations._

## Code / PR Reviews

At Crema, we recognize the value of reviewing pull requests (PRs) as a crucial aspect of our development process. PR reviews allow us to maintain the high-quality code that our clients have come to expect from us. By conducting thorough reviews, we ensure that our software is not only functionally robust but also follows best practices for readability, maintainability, and performance.

Reviewing PRs in a timely manner is a shared responsibility. We understand that our colleagues are waiting for our feedback to proceed with their tasks. Quick turnarounds on PR reviews help us maintain our project momentum, avoid code conflicts, and increase overall team productivity. It is our collective commitment to review and provide feedback on PRs as promptly as possible without compromising on the quality of our reviews.

There are many ways to conduct a good code review, here's a suggested "pyramid" model for doing so. Focus on the base layers and aim to achieve the top of the pyramid:

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
