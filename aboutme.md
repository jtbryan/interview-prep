# Current job accolades

## Company: AT&T

After graduating college I joined AT&T in their technology development program in July 2021. Since then, I have worked on several teams at AT&T across multiple organizations. For example, I started out working in AT&T Cybersecurity on our customer facing SaaS product Unified Security Management Anywhere (USMA) which is a cloud based threat detection and analysis platform utilizing AWS. As a backend software engineer, I was brought into support the development our in-house identity provider (IdP) service to allow SSO for users using Java spring boot. My role was specifically focused on CRUD APIs applying OAuth authentication principles for users and assisting with migration once these changes were scheduled to go live. We Consolidated over 28,000 customer authentication records across 2,500 instances into a single, efficient authentication service. Additionally, I also assisted in the development of our in-house agent creating python flask API endpoints to interface with osquery. Specifically this is the short synopsis of what the agent is:

```
The Agent is a lightweight endpoint agent based on osquery, the leading open-source operating system (OS) instrumentation framework for Microsoft Windows, Apple macOS, and Linux. It enables endpoint detection and monitoring with central management, contributing to complete and effective threat visibility, detection, and compliance.
```

The Agent is easy to install on your host and endpoints, and has a small footprint. An installed agent provides continuous endpoint security monitoring, allowing USM Anywhere to quickly detect threats on your essential assets without the time-consuming manual configuration and setup tasks required to implement and integrate a third-party tool.

Finally, myself and the team would collaborate on a bi-weekly basis to take part in war game style end to end testing where we were each assigned different tasks to stress test different parts of the applications in a sandbox environment creating using AWS cloudformation with an s3 template. 

Following my time on this team, I then moved to another team at AT&T working on our service technician facing internal application, ORCA, as a fullstack software engineer using Angular, Java SpringBoot and Oracle SQL. On this team I assisted with creating various new API endpoints, and creating the frontend components that would interface with these endpoints. Specifically, these APIs were focused around enhancing the scheduling process for over 10,000 service technicians and automating their scheduling process, savings hours of lost time per day.

Now, I am currently working in the customer experience organization as a backend software engineer supporting a suite of various microservices. Specifically, I am supporting Terms & Conditions, Consent, and more. My tasks in this role generally have involved migrating our kafka services from on-prem to Azure cloud, specifically Azure Event Hub and also Cosmos DB to store consent metadata. I was brought onto this team to work on reducing the latency from our API requests made to our microservice by bypassing a middleware service in favor of a separate service it was calling, effectively improving our API performance by 56% across several microservices. Once we were able to do so, we also created feature flags for each API so we could seamlessly deploy these changes. Additionally, I also work with ELK to monitor API performance and logs to debug issues that may arise and also use jenkins for our CI/CD flow. 

### STAR format examples as per chatGPT

#### API Latency Reduction (Technical Problem-Solving & Collaboration)
Situation:
While working in AT&T’s Customer Experience organization, our team maintained several microservices supporting Terms & Conditions, Consent, and other features. We identified that API response times were significantly high due to requests passing through an additional middleware service before reaching a backend API that provided customer data. This led to performance degradation and impacted user experience.

Task:
Our goal was to reduce API latency and improve efficiency by directly integrating with the backend customer data API while ensuring a smooth transition without disrupting existing services.

Action:

Collaborated with the team owning the customer data APIs to understand their architecture and integration points.
Participated in architectural discussions to evaluate how our services could directly consume their APIs.
Developed a new integration layer within our microservices to bypass the middleware and interact directly with the backend API.
Implemented feature flags to enable a phased rollout, ensuring we could toggle between the old and new integrations if any issues arose.
Conducted rigorous performance testing to measure improvements and ensure no regression in functionality.
Result:

Successfully improved API performance by 56% across multiple microservices.
Reduced dependency on middleware, lowering operational complexity.
Ensured a seamless transition with zero downtime using feature flags.
Strengthened collaboration between teams, streamlining future integration efforts.

#### SME for Terms & Conditions Microservice (Ownership & Leadership)
Situation:
In my current role, I was entrusted as the Subject Matter Expert (SME) for the Terms & Conditions (T&C) microservice, which is critical for managing user consent. This meant I was responsible for designing and implementing new features, onboarding new T&Cs, and maintaining service reliability.

Task:
I needed to lead technical discussions, ensure feature requests were well-documented, and resolve defects efficiently while maintaining service stability.

Action:

Led design discussions for all new feature developments related to the T&C microservice.
Worked closely with stakeholders to define requirements and ensure compliance.
Spearheaded the onboarding of new T&Cs, ensuring proper validation and storage mechanisms.
Acted as the primary point of contact for all bug fixes and production issues related to T&C.
Maintained comprehensive documentation to support knowledge sharing and onboarding of new team members.
Result:

Ensured the smooth onboarding of multiple new T&Cs, improving compliance processes.
Maintained high service reliability by proactively resolving defects.
Became the go-to expert for the service, reducing resolution time for issues.

#### Load Balancer Onboarding & Failover (Cross-Team Collaboration & DevOps)
Situation:
Our team needed to onboard a new load balancer and execute a failover process from the East to West service regions. This required coordination with the DevOps team and careful planning to ensure uninterrupted service.

Task:
I needed to work closely with the DevOps team to ensure the new load balancer was properly configured, validate that API requests were routing correctly, and assist in a smooth failover transition.

Action:

Worked with the DevOps team to review and validate the new load balancer configurations.
Assisted in failover testing, ensuring traffic was successfully redirected without service degradation.
Conducted real-time monitoring during the transition, using ELK to track API performance and error rates.
Provided post-migration support, addressing any issues that arose during the transition.
Result:

Successfully onboarded the new load balancer with zero downtime.
Ensured a smooth failover process, maintaining service availability.
Strengthened collaboration with DevOps, improving future migration processes.

#### Handling Ambiguity in Requirements (Problem-Solving & Communication)
Situation:
Many user stories in our backlog lacked well-defined requirements, leading to uncertainty and potential delays in development.

Task:
I needed to clarify ambiguous requirements by working with senior and lead engineers to ensure proper understanding before implementation.

Action:

Proactively reached out to senior and lead engineers to gather more context on poorly defined stories.
Asked targeted questions to identify edge cases and ensure comprehensive test coverage.
Documented findings and updated the user stories with clearer acceptance criteria.
Regularly participated in sprint planning meetings to advocate for better documentation and requirement gathering.
Result:

Reduced ambiguity, leading to faster development cycles and fewer blockers.
Improved collaboration with senior engineers, gaining valuable mentorship and technical insight.
Helped the team develop better documentation practices, improving clarity for future sprints.

# Core values (Microsoft)

• Collaboration: How do you work with a team towards company-wide goals?

• Drive for Results: How do you strive for the best possible solutions?

• Adaptability: How do you handle ambiguity and changing circumstances?

• Customer Focus: How do you keep the customer’s perspective in mind?

• Influence for Impact: Can you communicate effectively and persuade others?

# Positions