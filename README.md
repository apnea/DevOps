# DevOps
DevOps course notes

# Definition

*Damon Edwards, John Willis*

CAMS - Culture, Automation, Measurement, and Sharing

*Jez Humble*

CALMS - CAMS + Lean

# DevOps Principles: The Three Ways

*William Edwards Demings*
[link](https://en.wikipedia.org/wiki/W._Edwards_Deming)

PDCA  (plan–do–check–act or plan–do–check–adjust)

TQM (total quality management)

## The Three Ways

1. Systems Thinking
2. Amplifying feedback loops
3. A culture of continuous experimentation and learning

Developed by *Gene Kim* and *Mike Orzen*

### Systems Thinking

Emphasizes performance of entire system

Colaboration across functional lines

Focuses on IT-enabled **value streams**

### Systems Thinking Outcomes

**Stops passing defects** downstream

Does not allow local optimisation

Always seeking to increase flow

Profound understanding of the system

### Practical Challenges

 - protect capacilty
 - pressure on delivery trumps experimentation and learning
 - leaders who balance capactity with experimentation and learning are key
 - create a culture where it is safe to take risks
 
 Note:
 
 > Chaos Engineering
 > Netflix 'Chaos Monkey'
 
 
## DevOps Principles: The Seven Principles and Seven Wastes of Lean

Papendorf/dick

1. Eliminate waste - partially done work, extra features, revisiting decisions, handoffs, delays, task switching, defects
3. Build quality in
4. Create knowledge
5. Defer commitment - one way and two way decisions
6. Deliver fast
7. Respect people
8. Optimize whole


## DevOps Principles: Improvement Kata

From Toyota production system - continuous improvement

Improvement Kata steps:

1. Understand vision and direction for project/product
2. Analyze to understand current condition
3. Establish target condition
4. Plan > Do > Check > Act (PDCA) toward target


## DevOps Principles: A3 Problem Solving Framework

A3 refers to European paper size

A3 Problem Solving = structured steps

| A3 Steps | PDCA Cycle |
| ----------- | ----------- |
| 1 Background | Plan |
| 2 Problem statement / current condition |   | 
| 3 Goal / Target condition |  |
| 4 Analysis |  |
| 5 Proposed countermeasures | Do |
| 6 Implementation Plan | Check |
| 7 Follow up actions | Act |

Note:

Step 2 is aligned with improvement kata language

Spend time on the plan phase - great planning leads to good outcomes

Countermeasures - effort vs. impact


## The Westrum Model for Improving Organizational Culture

Devops is all about culture

### Westrum model

Ron W researched human factors in org safety

1. Pathological - large amounts of fear and threat
2. Bureaucratic - rule-oriented
3. Generative - performance-oriented

Also: organizational culture predicts information flow

3 characteristics of good information:

- answers provided
- timeliness
- presented in such a way as to be effective

What does good culture look like?

- trust and collaboration across the organization
- indicated high-quality decision making


## Leadership philosophies

- honour and extract reality

### Extracting Reality

- leaders respond negatively by 'shooting the messenger'
- build trust to make team feel safe
- use 'how'instead of 'who'
- ask, 'How can I help?'

### Understand the work

- concept of **gemba** : Japanese term meaning 'the actual place'
- not micromanagement - purpose is to 'go see' not to 'go tell'
- demonstrate commitment to learning and problem-solving with the team

### Root Cause Philosophies

- human error is not a cause
- focus on learning vs finding root cause
- no single root case
- focus on learning

### Leading by example

- make sure actions work

### Leadership is accountable

- provide strategic direction, prioritization, focus and discipline
- encourage a learning environment
- provide intent, context and accountability

### Lifelong learner

- be active in the community and learn from others
- new experiences give additional knowledge and resiliance
- step outside the comfort zone and experiment

### #1 Asset - People

- Lean is all about repect for people
- foundation of all leadership philosophies
- create high trust and a generative culture


## Changing metrics: Shifting from Outputs to Outcomes

### Outputs vs. Outcomes

Output = what we deliver
Oucome = what we gain from output

Focus on the outcome

Typically, business focus on ony 2 outcomes:

1. Increasing revenue
2. Improving efficiency

### Deployment Pain metric

- measures difficulty of deployment into prod
- indicates how performant org is
- can also indicate burnout of ppl and culture

### Change failure Rate

- focus on smaller more frequent changes
- enable roll back and feature flags (to turn off new feature if buggy)

### Deployment Frequency

- high perf orgs deploy on demand
- correlated with deployment pain

### Lead time

- lemgth of time it takes identified change to be integrated and in customer's hands

### Mean Time to Restore Service (MTTR)

### Unplanned Work

- key indicator of organizational performance
- disruptions keeps from delivering

### Employee Net Promoter Score (eNPS)

- how likely would you refer someone to this team?
- or to the overall org
- culture is extremely important within a team / org

- outcome based teams - highest eNPS
- output based teams - low eNPS score


### DevOps Works for Everyone: Three Case Studies

- DevOps works regardless of methodology


# Module 2 - Working with a DevOps Mindset

## The Importance of Loosely Coupled Architecture Teams

### Loosely coupled architecture

- Components are appropriately isolated
- Can modify and test independently
- Still collaborate and communicate
- Changes can be readily implemennted
- Able to scale horizontally
- Streamlines testing
- Allows for speed and agility

- assign an individual to track dependencies
- important to reduce dependencies
- free team to dicuss higher level goals

## The Importance of Iteration and the Evolution of Roles

### Value stream mapping 101

- choose small number of pilot teams
- also: start small with feature delivery
> start small

> get immediate feedback

> learn fast

> adjust

- traditional silos

`Dev team`
`QA team`
`Ops`

- benefits of an integrated team
   - able to be proactive
   - fix code before testing
   - fast feedback loops

- rolling out organizational change
    - starting out small and running pilots saves
        - Time
        - Money
        - Effort
        - plus you learn a lot

- Product Owner Role
    - let business systems analysts take on PO role
    - PO role is most critical
    - Day to day decision maker

- Developer Role
    - change mindset to Developer/Engineer
    - i.e. accountable for development, quality, security, and non-functional requirements
    - important to help developers see the bigger picture
    
- Lines around roles are blurring
    - dev, QA, Ops
    - traditional roles too siloed
    - people taking on multiple roles
    

    
    
