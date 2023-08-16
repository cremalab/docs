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
    - [Code comments](#code-comments)
    - [Markdown README files](#markdown-readme-files)
      - [Diagrams with Mermaid](#diagrams-with-mermaid)
    - [Architechtural decision records](#architechtural-decision-records)
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
  - [Continuous Integration / Continuous Deployment (CI/CD)](#continuous-integration--continuous-deployment-cicd)
  - [Security Practices](#security-practices)
    - [Encrypting Data in Transit](#encrypting-data-in-transit)
    - [OWASP Top 10](#owasp-top-10)
    - [Basic Security Checklist](#basic-security-checklist)
  - [Performance Practices](#performance-practices)
    - [Building for Performance](#building-for-performance)
    - [Performance Improvements](#performance-improvements)
  - [Engagements](#engagements)
    - [Onboarding: Welcoming New Clients](#onboarding-welcoming-new-clients)
    - [Offboarding: Seamless Handoffs to Clients](#offboarding-seamless-handoffs-to-clients)

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

- **[Jest](https://jestjs.io/)**: A popular JavaScript testing framework with a focus on simplicity. It allows us to write tests with an easy-to-understand syntax, and provides a wide range of features such as a full-featured expectation library, mock functions, etc.

- **[Cypress](https://www.cypress.io/)**: A powerful end-to-end testing tool for web applications. With Cypress, we can create tests that interact with our applications just like a real user would, giving us confidence that our applications work correctly in real-world conditions.

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

At Crema, we deeply understand the value of good documentation. We view it not only as a tool to facilitate the current development process, but as a crucial component in making our code understandable for future readers. This includes new team members, developers from other teams, or even our future selves. Our approach to documentation is centered around the principles of clarity, comprehensiveness, and relevance, as we aim to create a written record that enhances our code and benefits all who interact with it.

Documentation is as crucial as code itself, promoting understanding, maintenance, and extensibility. It's pivotal for successful onboarding and effective codebase iteration. We advocate for self-explanatory code through clear names and structures. When needed, comments provide context or explain less obvious decisions. Documentation should be created concurrently with coding to capture the writer's insights accurately and immediately. The focus of good documentation extends beyond what the code does to why it does it. It explains decision-making, rejected alternatives, and broader context, assisting future comprehension.

Here are some options we have utilized for documentation before:

### Code comments

These are written directly in the source code, usually on the line above the code they're describing. They provide immediate, focused insight into what the code is doing or why certain decisions were made. They're particularly useful for complex or non-obvious pieces of code.

### Markdown README files

A readme file provides an overview of the module (component, project, etc). It usually includes information about the module's purpose, how to use it, and other helpful resources. Markdown syntax places the content in a readable way and integrates nicely with GitHub.

#### Diagrams with Mermaid

Mermaid is a tool that generates diagrams and flowcharts using text and script. It's a useful tool for visualizing, maintaining and explaining complex processes or structures within your application. Diagrams can be particularly helpful in illustrating relationships between components, data flow, and architectural design. Mermaid diagrams are rendered as pictures inside markdown files on GitHub. Win win.

### Architechtural decision records

ADRs are documents that capture important architectural decisions, along with their context and consequences. They're an effective way of documenting why certain decisions were made, making it easier for future team members to understand the reasoning behind specific design and architectural choices. This aids in maintaining architectural consistency and quality as a project evolves over time.

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

At Crema, we have adopted Scrum as our default methodology, but also recognize that each team is unique. As such, we have crafted our own flavor of Scrum—tailored to our culture, our clients, and our quest for continuous improvement. Our Scrum approach includes several key ceremonies designed to maximize communication, collaboration, and productivity.

### Sprint Kickoffs

Our sprints start with a Kickoff meeting. During this session, the team reviews the planned work for the sprint, discussing the goals, priorities, and potential challenges. This ensures that everyone begins the sprint with a clear understanding of what needs to be accomplished and how we plan to get there.

### Demos

We regularly showcase our progress to stakeholders, demonstrating new features and updates. This allows us to gather immediate feedback and ensure that we're on the right track, delivering value with every increment.

### Retrospectives

Retrospectives are held at the end of every sprint. In these meetings, the team reflects on the past sprint, discussing what went well, what could be improved, and how to implement these improvements in the next sprint. This iterative process is a key part of our commitment to continuous improvement.

### Storypointing

Storypointing is an essential part of our planning process. We assign points to user stories based on their size, complexity, risk, and effort required. This helps us gauge the amount of work needed for a sprint and assists in effectively managing our resources.

### Backlog Grooming

Regular backlog grooming sessions ensure our backlog remains organized, relevant, and up-to-date. During these meetings, we review and reprioritize user stories, break down larger stories into manageable tasks, and ensure that the backlog aligns with the project's goals and priorities.

## Continuous Integration / Continuous Deployment (CI/CD)

We try to leverage automation as much as possible in our development process at Crema. It enhances efficiency, reduces errors, and enables us to deliver value to our clients more quickly and reliably. This is where Continuous Integration and Continuous Deployment (CI/CD) come into play. CI/CD pipelines automate tasks like building, testing, and deploying our applications, ensuring a smoother, faster, and more reliable delivery process.

We primarily leverage GitHub Actions for our CI/CD needs. This tool allows us to create customized workflows directly in our repositories. It integrates with the GitHub interface we're already familiar with, providing automation capabilities that streamline our workflow and support consistent releases.

Different clients we work with might already have their pipelines defined, in which case, we're happy to utilize and support throughout an engagement.

## Security Practices

At Crema, the security of our software is not just an afterthought—it's integral to the development process. Protecting our clients' data and ensuring the robustness of our digital solutions are of highest importance. Adhering to best security practices is not just about protecting against threats; it's about building trust and credibility.

### Encrypting Data in Transit

We ensure that all data in transit is encrypted using modern encryption standards. This ensures that even if the data is intercepted, it remains unreadable and secure.

### OWASP Top 10

One of our guiding reference points in software security is the OWASP Top 10—a standard list of the most critical web application vulnerabilities. Our developers are well-acquainted with these vulnerabilities, and we actively test our software against them. By doing so, we preemptively address potential threats, ensuring our applications are resilient against the most common and impactful security risks.

Through these measures, among others, we consistently work to ensure that every piece of software we deliver is not only functional but securely fortified against potential threats.

### Basic Security Checklist

- [x] Application only uses encrypted communication (e.g. HTTPS)
- [x] A strict CSP header has been applied to the HTML document on the web server
- [x] User input has been escaped for XSS (React does it by default)
- [x] No access keys have been stored on the codebase (if so, remove them from repo and generate new keys)

## Performance Practices

Performance is a vital aspect of user experience, and at Crema, it's embedded in our development practices. But, while we are always committed to delivering well-performing solutions, we are equally pragmatic about how we approach performance optimizations.

### Building for Performance

From the onset of development, we prioritize clean, efficient code to provide our users with responsive, seamless experiences. This means selecting the right tools, frameworks, and architectures that are known for their performance advantages.

### Performance Improvements

Performance optimization, while essential, can consume significant resources. We firmly believe in the saying, "Don't optimize what you can't measure." Before diving into performance improvements, we always set clear, measurable benchmarks. This ensures we can quantify the impact of our optimizations, providing real, tangible value rather than chasing after arbitrary speed gains.

In doing so, we strike the right balance—ensuring our solutions are both robust in performance and efficient in development. By always having a measurable goal in sight, we channel our efforts effectively and ensure that every optimization has a meaningful impact on the overall user experience.

## Engagements

Engaging with our clients is a dynamic journey. At Crema, we've established onboarding and offboarding processes to ensure smooth transitions at both the start and conclusion of our engagements. These processes are not just about procedures; they're about cultivating understanding, setting expectations, and ensuring the continued success of the projects we've nurtured.

### Onboarding: Welcoming New Clients

The onboarding process is pivotal. It sets the tone for our entire engagement and paves the way for a successful collaboration.

- **Sales Brief**: This document outlines all the conversations that happened prior to the contracts being signed. It holds context about the sales cycle, expected outcomes, pain points, etc. It's a great place for the production team to start wrapping their heads around the work ahead of them.
- **Product Lab**: This initial workshop introduces the teams, identifies problem statements, ideate on the possible solutions, sets project expectations, and establishes primary communication channels.
- **Existing Client Documentation**: Any relevant documentation, like business logic, legacy code, design files, API docs, is shared to ensure we have all the information we need.

### Offboarding: Seamless Handoffs to Clients

Concluding our engagement does not signify the end of a project's life. Instead, it's about empowering our clients to take the reins with confidence.

- **Project Handover**: We provide a comprehensive package that includes all developed code, assets, designs, and documentation, organized and annotated for clarity.
<!-- - **Training Sessions**: Custom training sessions are conducted to familiarize the client's team with the delivered systems, ensuring they can operate and manage them efficiently.
- **Feedback Loop**: We hold sessions to gather feedback, learning from the engagement and improving for the future.
- **Post-Engagement Support**: While the main engagement might be over, we're always available for any follow-up questions or support, ensuring a smooth transition for all involved. -->

With these ceremonies and deliverables, we aim to provide our clients with not just a product but a holistic experience, ensuring that every stage of the journey is marked by clarity, understanding, and collaboration.
