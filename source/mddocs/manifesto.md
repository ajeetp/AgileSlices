# Agile Manifesto

!!! note ""
    Pre-requisites: [Agile Definition](../definition), [Agile Principles](../principles)

In this section we will dive deeper into each statement from the [The Agile Manifesto](https://agilemanifesto.org/).

Agile Manifesto: We value

- **Individuals and interactions** over processes and tools
- **Working software** over comprehensive documentation
- **Customer collaboration** over contract negotiation
- **Responding to change** over following a plan

!!! caution "One of the anti-patterns in Agile adoption is to focus heavily on the left hand side of the 4 statements, which leads to imbalanced implementation and reduced benefits. The items on the right are part of Agile approach and must be factored in the adoption phase to realize maximum benefits."

---

???+ example "Example Scenario: Transition to Agile"
    *To understand these statements better, let's construct a hypothetical scenario*: Executives at ACME Inc. have asked one of their software development teams to pilot Agile. The team currently consists of a PM, four developers, a tester and an analyst. This team is new to Agile methodology.

    !!! info "Note: This example is intended to show how the 4 statements in the Agile manifesto relate to an Agile team's activities. It is - not - a roadmap for Agile transition and is simplified for brevity. The examples depict events in sequence and should be read in order."

## Individuals and interactions over processes and tools

Agile approach values individuals and implies providing the necessary support needed for the individuals to perform their best. Efficient and frequent interaction is valued. The supporting processes and tools should enhance transparency and trust.

??? example "Example: ACME team"
    > *Day 1*: The team meets to discuss agile transition. They agree on the following

    > - Every team member will attend Agile methodology training
    > - Any decision that impacts the team will be taken together by the team
    > - Experimentation is encouraged.

    We value **individuals**: Awareness of team member needs, Building trust, Creating a safe environment for learning.

    > *Next sync meeting*: All team members have completed training. The team meets to discuss next steps.

    > - To be a cross functional team, the team will work together and learn from each other.
    > - The team will adopt 4 week long cycle/iteration
    > - The team will use a wall and sticky notes for tracking work
    > - The team will meet daily at a set time and talk about what they are working on and if they need help
    > - The team will pick a small project and familiar technology stack

    We value **interactions**: Frequent interaction, helping each other.
    We value **individuals**: Not overload the team at an early stage so the team has time to learn, acclimate and adapt.
    Start with just enough *process* and *tools* that add value.

    > *Next sync meeting*: The team is cross-functional, each team member has their area of expertise and are comfortable with performing activities in other areas. The team meets to discuss next steps.

    > - The team will hold planning meeting at the start of a cycle and review meeting at the end of the cycle.
    > - The team will work together on building a backlog with just enough details for two cycles
    > - The team will estimate work items in the backlog using familiar technique

    We value **interactions**: More face-to-face communication.
    Introduce changes in increments rather than all at once, Just enough preparation so the team is not blocked

## Working software over comprehensive documentation

Delivering value frequently by doing just enough work and adapting to change is the Agile way. This implies doing work in increments and just enough documentation that is needed for that increment.

??? example "Example ACME team"
    > *Next review meeting*: The team reviews completed work which at this time is the backlog.

    When a team has to start with building a backlog and everyone is pitching in there may not be code written in that initial cycle. This was not a **coding** cycle for this team. A backlog with next 2 cycles of work - is a deliverable of the iteration for this team. Some teams may start building a dev environment or procurring assets, if the agile team is doing this work then it is valid to include this in the review.

    Q) This seems like traditional approach where requirements document is created first, isn't it?

    A) Remember that the backlog is an artifact that has several levels and only the most important (highest value) requirements are broken down from the highest level to the lowest level (A unit of work that can be done in a cycle). The backlog will have just enough work items that the team can address in the next cycle or two (some teams encourage having 3 cycles worth of work items). This is different from traditional approach where all requirements need to elaborated before any work begins.

    **Working software** can be built only if the requirements are known and understood.

    Involving the entire team in the backlog building excercise was a great idea for this team, because the team could understand how its done and also provide feedback on what kind of details are needed at the work item level for the team to have clarity.

    > *Next planning meeting*: The team selects work items for the cycle. The team members provide their inputs on how much work the team can accomplish so just enough work is added to the cycle. The work is not assigned but is chosen by the team members.

    > After the planning meeting the team members create tasks for the work items and estimate the tasks in hours. After this the team commits to work that can be finished. At this time there are some items that get moved to the next cycle.

    To have predictable delivery the work must be estimated by those who will actually do it. **Working software** will be delivered if the team members understand exactly what is involved in delivering it and what "done" means.

    > *Next review meeting*: The team is able to deliver on most of the commitments but a couple of work items were not completed. There is no UI at this time and the code demo involves a quick view of the code and running unit tests. Stakeholder feedback is recorded.

    > After the review, the PM sends out a report to executives on what was done.

    **Working software** is the true measure of progress. Reporting on commitments and accomplishments when done in an easy way (for example : a brief summay and link to tool that shows the completed items) promotes transparency and builds trust. It is also a great way to recognize the team for the work done.

    Whereas in traditional approach there is significant time invested in comprehensive documentation such as requirements document, this means that if there were changes then all that effort was spent needlessly. In Agile methodology the requirements are evaluated for value and the highest value items are broken down in increments, if changes to requirements that have not been broken down are required then there is zero wasted effort. In addition since the changes can be incorporated so easily the value delivered to the customer will be higher and customer satisfaction improves.

## Customer collaboration over contract negotiation

Customer satisfaction is the highest goal in Agile. It goes beyond contractual obligations and towards customer delight. Being customer obsessed means starting with the customer, collaborating with the customer throughout the project to understand their goals and adapt to deliver the best value.

??? example "Example: ACME team"
    > *Retrospective*: The team has identified an improvement area. Team members realize they need to improve customer collaboration, the team is developing an internal tool and has been reaching out to the teams that will use this tool (internal customers). A team member volunteers to be the product owner and work with the other teams closely to understand their needs. The team also decides to extend invitation to key members from other teams for their planning and review meetings.

    **Customer collaboration** is possible in many ways, some teams invite external customers to their agile meetings. Other teams have a product owner who works with external customers and acts as the customer representative in the team.

    > *Next planning meeting*: The meeting includes internal customers and the team shares the cycle goals with them. The team gets feedback that a particular feature is needed by a set date.

    > After the meeting, the product owner follows up with the team and they discuss if the feature can be delivered by the date given. The team does a breakdown plus estimation and lets the product owner know that if they drop everything and work on it, it still would not be compeleted by the date but can be delivered 2 weeks later than the date.

    > The product owner then reaches out to the requestor(s) of the feature and drills down to figure out what pieces of it are must-haves and should-haves. It turns out that the detailed breakdown revealed some assumptions by the team and not everything listed was needed. Armed with this knowledge, the product owner gets back to the team and they redo the estimation.

    > This time keeping only the must-haves, the team feels that the must-haves can be delivered in the timeframe. The product owner then communicates to the internal customers that the feature can be completed in time with the specifics on which pieces will be delivered ( must-haves ).

    > The team also learns that identifyng must-have items should ideally be done before estimation.

    Working with the customer to satisfy their needs requires a change in attitude for teams transitioning to Agile, close partnership is a good thing and clarity of what are must-haves is important. The team should always be thinking about reducing work, **do just enough work to meet customer needs**.

## Responding to change over following a plan

Planning is part of Agile, it is done in increments. The plan drives the team to deliver value and when the team learns of a change in requirements they can adopt the plan easily and cheaply. The ability to respond to change is the reason why Agile methodology results in higher customer satisfaction and faster time to market.

??? example "Example: ACME team"
    > *Re-planning*: The team learned that there is a high value feature that needs to be delivered by a set date and negotiated with the customer on the must-haves. In this case, the team agrees that this is important to the customer and decides to do the planning again for the cycle.

    Responding to a request from the customer and replanning work will help the team to deliver value on time. This builds trust and credibility with the customer. Investing in improving the relationship/partnership with the customer requires listening to the customer and constantly thinking about what would be valuable for the customer.

    The team should take care and make an informed decision to change work within a cycle, this should not become the norm. Ofcourse this should be customized to the team, if a team also handles production bugs and must fix them as soon as possible then part of the cycle time can be set aside for bug fixing (if the team knows of the bugs in advance then it should be planned work).
