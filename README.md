# Story Writing


This repo serves to provide resources and clarity on the story writing process.

In this Repo:

1. Writing User Stories
2. Story Pointing
3. Story Splitting

## User Stories

### Why User Stories?

User stories provide an excellent way to define your product with clarity. A set of well-defined, properly prioritized user stories can help articulate the functionality of your product using simple English that anyone can understand _with no technicalities or implementation details._

The user story approach can lead to meaningful product discussions, both within the product development team and with external stakeholders.

- User stories help to achieve **cross-team clarity** on what to build, for whom, why, and when. 
- User stories encourage participation by both technical and **non-technical members.** 
- User stories help in **defining the entire product** — as a set of solid, properly prioritized stories. 

---

## Story Pointing

Story pointing is a useful metric in estimating the difficulty in implementing a given user story. It is an abstract measurement

### Invest Criteria 

Before pointing a story, it’s important to make sure that the story meets INVEST criteria. 

In order to work a story it out be at least +5 INVEST Points and at least +1 for being VALUABLE.  If it is not at least 1 for value, it is not worth doing. If it is LESS than 5, you don’t work the story. It is either tossed, refined, broken down, changed, etc.

A story does not need to perfectly meet the INVEST criteria, but how do we know when it’s good enough?

- [ ] User Story is **INDEPENDENT**:
 Does not depend on another unfinished User Story to be finished first (order independent)
- [ ] User Story is **NEGOTIABLE**:
 Does not define how to implement, design or solve the Goal; only the Who, What, Why
- [ ] User Story is **VALUABLE**:
 Has valid Role part (refer to User Story Title below)
 Has valid Goal part (refer to User Story Title below)
 Has valid Benefit part (refer to User Story Title below)
- [ ] User Story is **ESTIMABLE**:
 Is sized: ___ Story Points (refer to Relative Estimation below, -2 without size)
- [ ] User Story is **SMALL**: 
 Can be finished within a couple of working days
 Size is not larger than 2 Story Points
- [ ] User Story is **TESTABLE**: Is specific enough to write User Acceptance Criteria
 User Acceptance Criteria are specific (e.g. specific user input and expected output values) 

| Rating | Description | 
| :---: | :---: | 
| -2 | Definitely not | 
| -1 | Not 100% sure | 
|  0 | Maybe | 
|  1 | Looks like/Kind of |
|  2 | Definitely | 


___ INVEST Points (sum of above INVEST Points)

You move forward with/point a story that scores at least +5 INVEST points *total* and at least +1 for being valuable. 

### Story Pointing/Estimating Chart

| Estimate/Points | Complex | Unknowns | Tests |
| :---: | :---: | :---: | :---: |
|0 (Very rare) | No | No | No |
|2 (Min for Chore & Spike) | No | No | Yes|
|5 (Complex OR unknowns)| Yes | OR Yes | Yes |
|8 (Complex AND unknown (DON’T DO IT!))| YES | AND YES | Yes |

---

## Story Splitting

There are many techniques for splitting stories. Here are some of the most useful ones. There are more below if you need more ideas on splitting, but for a lot of cases these three patterns can get you started!

- **Split by user roles**

Teachers interact with instructional software differently from students. Administrators interact with a system differently from normal users. By defining the different roles in your system, you can split features and stories to address the unique needs of each role.

- **Split by user personas**

Even in the same role, different people interact with software in different ways. A power user may want lots of keyboard shortcuts. A casual user may want a lot of intuitive, hand-holdy forms of guidance. Handicapped/disabled users may need very different ways of interacting with the system, even though they are doing the same tasks as other users.

### Split Conditions

When a story has multiple items listed in the 'what' category, consider making each a separate story. When you see words like "and" or "or" ask yourself, are all these necessary right now?

> Example:
> 
> User Story: As a customer I want to create an order and pay for the order using a credit card so I can get something to eat.
> 
> 1. As a customer I want to create an order
> 2. As a customer I want to pay for my order using a credit card


