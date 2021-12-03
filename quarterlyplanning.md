# Quarterly Planning: Draft

This document suggests how we might choose to run Quarterly Planning at Element, including the key components that would aid the Product team in delivering the outcomes desired by the business. 

| **Status:** WIP | **Last updated:** Nov 24, 2021 |
| --------------- | ------------------------------ |

#### **What is Quarterly Planning?**

- Setting objectives for the company and teams in 3 month chunks.

- Breaks Annual Goals into manageable chunks of work for product teams across the business.

- An opportunity to re-evaluate annual goals, team resourcing and direction. 

#### **Why is Quarterly Planning important?**

- Ensure teams have clear goals, expectations and alignment.

- Regular check-in on progress against deliverables and metrics.

- Review priorities across company and teams.

## **Overview of the process**

1. Prepare Epics to be discussed, prioritised, and resourced at the Planning meeting.
2. Prepare Company goals with target metrics for product.
3. Hold the Planning meeting.
4. Outcomes of the Planning meeting:
   1. Prioritised Epics (using Company goals and target metrics)
   2. Resourced Epics across teams 
   3. Alignment on the Roadmap

## **Preparation**

### **Epics**

**Epics are projects or features that are proposed for inclusion in the product.**

- Epics may be classified as Tech Debt, Feature work, or Target driven (such as any user growth projects).

**Epics may be proposed by any member of the team.** 

- For example: Sales may propose a new feature as an Epic that is a request from a customer/s. Engineering may propose an Epic that refactors a part of the product. Leadership may propose an Epic that is a table stakes feature, etc.

- All team members may work with Product Managers to ensure Epics have all the required information ahead of the Planning meeting.

**Epics are outcome focussed, not output focussed.**

- Epics should be focussed on solving a user/customer problem.

- Epics are areas of focus, externally they may also be known as “initiatives”.

- This ensures that we are not defining ‘how’ something should be done, but rather what we aim to achieve. This is more motivating for teams as it allows space for creativity in solutions.

- Focussing on outcomes also allows us to group smaller issues that have a common theme[*](https://docs.google.com/document/d/1n2NOXObM4L_SsvHMJ5_Pmun46m_jZza2xU_-g5RBGrI/edit#heading=h.bbvuk5fw6la6).

**Epics should be discussed and researched before the Planning meeting.** 

- Each Epic being proposed for discussion at the Planning meeting is at the concept stage and should meet the Definition of Ready as this simplifies Prioritisation during the Planning meeting.

#### **Epic: Definition of Ready**

**Epics must have:**

- A user/customer problem
- A Definition of Done
- A Definition of Success (ideally this relates to the company goals and is measurable)
- A brief description of any known, or unknown, work (including MSC requests)A brief overview of the resourcing needs to deliver
- An ROI calculation:
  - A sizing estimate
    - XS = 1 sprint, S = 2 sprints, M = 4 sprints, L = 6 sprints (1 quarter)
    - XL = More than 1 quarter of work

- A return estimate
  - A measurable impact 
    - Developer velocity in days, New users, Retention, Daily usage increases, etc.

**Epics may also have:**

- A issue in Github
- Any artefacts, wireframes or POCs that add extra colour to the epic

#### **Epic: An Example**

| **Lorem ipsum...**                                   |
| ---------------------------------------------------- |
| This Epic gives leadership:<br />- Sit dolor amet... |

### **Company Goals**

**Company Goals should be outcome oriented.** 

- They detail the outcome goals that are required of the product, where applicable they may include the actions required for success.

**Company Goals help teams prioritise work.**

- This prioritisation occurs at a quarterly level (product) and also at a Sprint Planning (team) and daily level (individual).

**Company Goals define work that will, and won’t, be completed during the quarter.**

- We receive a lot of requests for work, we don’t have the resources to support all these requests and Product Managers are responsible for prioritising work that achieves the Company and Quarterly goals as we go through the quarter.

#### **Company Goals: An Example**

| **#1 Compete effectively with mass-market apps on usability, fulfilling the expectations of users by elevating the quality of apps in usability & performance. Driving a 5% increase to D2 retention and delivering Threads.** |
| ------------------------------------------------------------ |
| This goal gives teams: <br />- An area of focus (compete on usability and meet user expectations). <br />- A measurable goal by which we can prioritise Epics and Issues (5% increase to D2 retention). <br />- A required action (deliver Threads). |

## **The Planning Meeting**

The Planning Meeting itself brings together all the pre-work and is designed to facilitate a prioritisation discussion. 

- Clear goals and agreed epics with clear owners
- An understanding of resourcing across teams
- An updated [roadmap](https://github.com/vector-im/roadmap/projects/1) & [pipeline](https://github.com/vector-im/element-meta/projects/1)
- Time division across the 3 categories of work

### **Output of the Planning Meeting**

- **Prioritised Epics (using Company goals and target metrics)**
  - A company-wide list of Epics, prioritised by impact will help us defend our roadmap, resources, and time during each quarter.

- **Resourced Epics across teams** 
  - Understanding where our resources are assigned...

- **Alignment on the Roadmap**
  - In order to...

### **Prioritisation process**

Company Goals and Epics can be combined to create a strategically prioritised list of projects for teams to work on.

- Company Goals represent the strategy for the year or quarter and should be used to identify Epics that should be worked on. 

- Epics, and their ROIs, can then be ordered into a prioritised list and assigned resources accordingly.

Exceptions to this process are Defects and Next-Gen work for which there should always be resources or time set aside to work on.

### **Risks**

**“It’s not an Epic”**

There are likely to be issues or requests that are not “Epic” size. If an issue does not fall into the Tech Debt or Bug category of work, it should be absorbed into an appropriate Epic. 

By focussing Epics and their deliverables on outcomes not outputs we should drastically reduce the number of issues that fall through the prioritisation cracks.

### **Time & Resourcing**

It’s hard to prioritise the dull items, the tech debt, and the hard to measure epics. There are several potential solutions to overcome this. I propose:

- Splitting Engineering time each quarter (or Sprint) into 3; Feature work, tech debt, and bugs.
  - Each quarter engineering leads can define the % of time spent on each bucket, this ensures that bugs are always handled and tech debt is not left untouched.

## **In an ideal world**

These things will likely come with time as the process matures:

- We would have **annual goals** that help define the quarterly goals and targets

- We would have a detailed **product vision** that would help prioritise epics
