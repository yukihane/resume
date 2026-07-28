# Resume

As of July 28, 2026

## Profile

| Item | Details |
| --- | --- |
| Name | Kazuyuki Dewa (出羽 和之) |
| Education | Master's degree in Information Engineering, Osaka Prefecture University, March 2003 |
| Employment status | Independent contractor since August 2010 |

## Professional Summary

I specialize in backend implementation and database design with Kotlin and Spring Boot. I have worked across requirements definition, design, implementation, and testing, including API, database, class, and processing design as well as performance improvement. I have used Spring Boot in production since 2018 and Kotlin since 2022.

From April 2003 to September 2009, I worked in the financial systems division of a systems integration company, developing, maintaining, and rebuilding an equity trading system for a securities firm. I was responsible for architecture design and data modeling, and also served as subproject leader for an eight-member development team.

Since becoming an independent contractor in August 2010, I have focused on web application development with Java EE and Spring. For new Spring Boot applications and migrations from WildFly, I have conducted technical research, selected design and implementation approaches and libraries, and established development standards. More recently, while maintaining a backend focus, I have expanded into React/Next.js frontend work, AWS and container runtime platforms, CI/CD, and new languages and technologies.

## Core Capabilities

The project numbers in “Key projects” correspond to the numbered entries in “Professional Experience” below.

| Area | Experience and capabilities | Key projects |
| --- | --- | --- |
| Requirements analysis and application design | In project 07, interviewed client system teams and securities traders, negotiated requirements, and translated them into feasible specifications based on existing system constraints. As an independent contractor, have designed APIs, databases, class structures, processing approaches, and test strategies from requirements prepared within the team, then carried the work through review, implementation, and release. | 01, 03–07 |
| Backend and external service integration | Design and implementation of web features, REST APIs, and BFFs with Java/Kotlin and Spring. Also experienced with OpenID Connect using Spring Security and with investigating external payment API specifications and error conditions. | 01–06 |
| Database design and performance optimization | Design databases from UML-based object-oriented models, balancing business requirements with the characteristics and constraints of persistence libraries including JPA/Hibernate, Exposed, and MyBatis. Diagnose slow screens through measurement, logs, and execution plans, then improve response performance by resolving SQL and indexing issues. | 01, 03–07 |
| Technology migration and legacy enhancement | Implemented migrations from Java to Kotlin, WildFly to Spring Boot, and legacy server-rendered screens to Next.js/TypeScript. In Java-to-Kotlin migration, used immutability and null safety as defaults while defining implementation rules that allow `var`, nullable types, and regular classes when required by Hibernate. | 03, 05 |
| Cloud, development platforms, and performance validation | Built Jenkins pipelines, deployed and operated an internal GitLab instance, and evaluated migration to OpenShift. On AWS, automated load testing and helped determine an instance configuration that met latency targets. | 04–06 |
| Frontend development | Experience with React/Next.js, TypeScript, and GWT. Can implement new features and screens within an established architecture and component system; also designed screens and navigation for a new service when no designer was assigned. | 01–06 |
| Team leadership and knowledge sharing | Led task assignment, progress tracking, design reviews, and code reviews for an eight-member client application team. Documented environment setup, test data preparation, and system architecture in Confluence and Notion to help new members become productive independently. | 03–07 |
| AI-assisted development | Collaborate with Claude Code across requirements consistency checks, design, implementation, code review, and testing. Account for possible context gaps in AI reviews by directing follow-up investigation of relevant specifications and code, then checking for inconsistencies and policy violations. | 01 |

## Certifications

- Network Specialist Examination, December 2009
- Application Systems Engineer Examination, December 2006
- OMG Certified UML Professional, Intermediate, September 2006
- Software Design & Development Engineer Examination, June 2003
- Class II Information Technology Engineer Examination, June 2000
- Systems Administrator Examination, December 1998

## Online Profiles

- [Stack Overflow in Japanese](https://ja.stackoverflow.com/users/2808/): Technical knowledge sharing through Q&A; ranked 13th and in the top 0.4% as of April 2025
- [Stack Overflow](https://stackoverflow.com/users/4506703/): Technical knowledge sharing through Q&A; ranked 135,335th and in the top 12% as of April 2025

## Professional Experience

### 01. Organization Diagnostics and Analytics Platform (August 2025–Present)

| Item | Details |
| --- | --- |
| Project | Development of a web service that conducts recurring employee surveys, analyzes responses, and uses AI to recommend follow-up actions. |
| Role and team | Developer. Team of six, including five developers. |
| Phases | System design, detailed design, implementation and unit testing, and integration testing. |
| Responsibilities | For new features, implemented frontend interfaces from Figma designs with Next.js/TypeScript, backend services with Kotlin/Spring Boot, and database design. Also extended existing Python/pandas batch jobs for aggregating and analyzing user responses, and implemented new aggregation jobs based on similar existing jobs. |
| Contributions | For the initial user rollout, used Claude Code across requirements review, design, implementation, and code review to deliver requested features within a short timeframe. Identified inconsistencies between requirements and existing specifications or code before implementation to prevent rework, and improved the efficiency of existing-code investigation. |
| Technologies | Kotlin, Spring Boot, Exposed ORM, TypeScript, Next.js, Python, pandas, PostgreSQL, Ubuntu. |

### 02. Employee Management for a Maritime Operations System (October 2024–April 2025)

| Item | Details |
| --- | --- |
| Project | Development of new employee search and editing features as part of a replacement for a system originally built by another vendor. |
| Role and team | Developer. Team of eight, including four developers; overall project team of twelve. |
| Phases | Detailed design, implementation and unit testing, and integration testing. |
| Responsibilities | Designed and implemented a Kotlin/Spring Boot backend and Thymeleaf/jQuery screens. Designed and implemented SQL and JPQL queries against an existing database schema. |
| Contributions | As the plain JavaScript codebase grew, maintaining consistency and understanding code inherited from other developers became difficult. Established module boundaries with ES Modules and a VS Code development approach using type information, improving code consistency and maintainability. |
| Technologies | Kotlin, JavaScript, SQL, HTML, Spring Boot, Hibernate, Thymeleaf, jQuery, Redis, MySQL on Cloud SQL, GKE, Ubuntu. |

### 03. News Distribution Web Service—New Features and Enhancements (January 2022–September 2024)

| Item | Details |
| --- | --- |
| Project | New development and enhancement of recurring columnist content and subscription billing features, plus maintenance of advertising delivery features. |
| Role and team | Developer. Team of eleven, including eight developers; overall project team of fifteen. |
| Phases | System design, detailed design, implementation and unit testing, integration testing, system testing, and maintenance. |
| Responsibilities | Added features and database design to Java/Kotlin services, investigated and verified an external payment API, replaced existing screens with Next.js/TypeScript, and extended or implemented Python/pandas aggregation batch jobs based on existing patterns. |
| Contributions | Investigated and verified a different integration pattern for an existing payment provider. During the incremental Java-to-Kotlin migration, defined rules for using `var`, nullable types, and regular classes where required by Hibernate while maintaining immutability and null safety where possible. Migrated Thymeleaf/CoffeeScript screens to Next.js, Apollo, and GraphQL. Improved response performance by using SQL execution plans to identify full table scans and index usage, then revising index definitions. |
| Technologies | Kotlin, Java, TypeScript, CoffeeScript, Python, SQL, HTML, Spring Framework, Hibernate, Next.js, React, Apollo, GraphQL, pandas, Redis, MySQL on Amazon RDS, Amazon ECS, Ubuntu. |

### 04. Mobile Carrier Mini-App and Web Service Development (July 2020–September 2021)

| Item | Details |
| --- | --- |
| Project | Development of web services on AWS, including mini-apps running within an existing smartphone application. |
| Role and team | Developer and Spring Boot implementation standards lead. Team of ten, including eight developers. |
| Phases | Requirements, system design, detailed design, implementation and unit testing, integration testing, and system testing. |
| Responsibilities | Standardized and documented the development environment; designed databases; developed a BFF with OpenID Connect authentication using Spring Security; implemented mini-app frontends with React; and reviewed and evaluated the AWS runtime design. Created Apache JMeter performance and load-test scenarios and scripts to automate test execution and result collection. |
| Contributions | As the only Spring Boot-experienced member, standardized implementation approaches and selected libraries based on experience from the prior project. As the first service to connect to the existing authentication platform from Spring Boot, investigated its differences from the OpenID Connect standard and whether Spring Security customization was needed, then designed and implemented the authentication flow. Stored shared HTTP sessions for the multi-instance environment in Redis via Spring Session. Automated performance and load testing, contributing to an AWS instance configuration that met latency targets. |
| Technologies | Java, TypeScript, SQL, HTML, Spring Boot, Spring Security, Spring Session, Hibernate, React, Redux, Apache JMeter, Redis, MySQL on Amazon RDS, Amazon ECS, Amazon EC2, CodeDeploy, Ubuntu. |

### 05. ISP Web Service Backend Development (February 2018–March 2020)

| Item | Details |
| --- | --- |
| Project | Improvement of a Java EE application development platform, construction of an internal CI/CD environment, application migration to Spring Boot, and validation of an on-premises system's cloud migration. |
| Role and team | Developer and Spring Boot technical research and standards lead on a five-member team. |
| Phases | Requirements, system design, detailed design, implementation and unit testing, and integration testing. |
| Responsibilities | Documented the Java EE development environment and standards; built Jenkins runtime and build/deployment jobs; designed databases; developed REST APIs with Spring Boot/MyBatis; and containerized, deployed, and verified a batch-processing service on OpenShift. |
| Contributions | Led technical research in a team without Spring Boot or React experience. For the backend, selected and standardized design and implementation approaches and libraries based on official documentation, then advanced the migration from Java EE/WildFly to Spring Boot. Validated migration of an on-premises batch service to OpenShift as a pilot and established that it was technically feasible. Built Jenkins infrastructure to automate previously manual builds and deployments. Improved response performance by revising index definitions from SQL execution plans, and also contributed to React/TypeScript frontend development. |
| Technologies | Java, TypeScript, HTML, Java EE, WildFly, Spring Boot, Hibernate, MyBatis, React, Docker, Jenkins, Ansible, Kubernetes, OpenShift, OAuth 2.0, Sybase ASE, RHEL. |

### 06. Trading Company and Banking Systems Development (August 2010–June 2017)

| Item | Details |
| --- | --- |
| Project | Primarily developed and maintained a transaction management system for a trading company. During an interruption, worked separately on development and maintenance of a bank risk-calculation system. |
| Role and team | Developer. Team of seventeen, including twelve developers. |
| Phases | Requirements, system design, detailed design, implementation and unit testing, integration testing, system testing, and maintenance. |
| Responsibilities | Java EE backend development, GWT client development, data modeling, and performance improvement. Built a GitLab server and designed and documented a development workflow including branches, merge requests, and code reviews. |
| Contributions | Took responsibility from installing the server OS through GitLab installation and configuration. Introduced GitLab into a development environment that used SVN and lacked clear branching practices, then defined the operating model and supported its adoption by the team. |
| Technologies | Java, SQL, Java EE 7, JBoss AS, WildFly, Hibernate, GWT, GitLab, PostgreSQL, SQL Server. |

### 07. Securities Trading System Maintenance and Development (April 2003–September 2009)

| Item | Details |
| --- | --- |
| Project | Maintenance and development of an equity trading system for a securities firm, including a rebuild associated with a Tokyo Stock Exchange system renewal. The system had stringent performance and scalability requirements. |
| Role and team | Employee of NS Solutions Corporation. Subproject leader and developer for an eight-member client application development team within a team of thirty, including twenty-five developers; overall project team of fifty. |
| Phases | Requirements, system design, detailed design, implementation and unit testing, integration testing, system testing, maintenance, and incident response. |
| Responsibilities | Client requirements coordination; architecture, data-model, and database design; GUI application development in Java/Swing and C; and design and code reviews. Designed mechanisms for retaining and searching large volumes of client-side in-memory data to enable fast screen response. |
| Contributions | Designed data-eviction and search mechanisms for in-memory data, as well as a mechanism for asynchronously querying the server and updating in-memory data while maintaining consistency with retrieved data. As subproject leader, managed task assignment and progress while also handling design, implementation, reviews, and incident response. |
| Technologies | Java 6, C, VB6, C#.NET, Swing, Hibernate, SourcePro, MFC, Sybase ASE, Oracle Coherence, Solaris, Windows. |
