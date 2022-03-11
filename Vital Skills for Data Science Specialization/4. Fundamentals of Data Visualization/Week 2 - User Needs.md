## Week 2 User Needs 
## Visualization Tasks

### What are tasks? 
**Task:** The reason why the vis tool is being used Highest-level tasks-why is the user using the visualization (purpose) Middle level-what the user is doing (navigation) Low level-what the user is looking for (data attributes)
Tasks let us separate what we want to do with data from its domain

### Task Elicitation

- How do we characterize the tasks a visualization tool needs to support?
- Typically interview with domain experts or survey of past analyses in the field (or both)

### Key Questions

- Why is a task pursued? (goal) 
- How is a task conducted? (means) 
- What does a task seek to learn about the data? (characteristics) 
- Where does the task operate? (target data) 
- When is the task performed? (workflow)
-  Who is executing the task? (roles)

### Purpose

Why is a task performed? What are the user's goals?

- **Explore:** Consume existing information in order to produce new information

- Closely related to **confirm**-validate prior knowledge

- **Present:** Succinct communication of information

- Closely related to **enjoy**-casual encounters with a visualization

### Means

How are tasks conducted? How are users interacting with the data?
- **Navigation:** Move through the data
- **Organizing:** Change how the data is presented
- **Relation:** Build connections in the data

### Data Characteristics

What does a task seek to learn about the data? 
- Think traditional patterns and statistics
- Low-level characteristics consider individual points (e.g., estimate or compare specific values)
-High-level characteristics consider patterns across multiple points (e.g., trends or averages)

### Target Data

Where does the task operate? (target data)
- **Absolute reference frame:** The data is compared against some common, established standard (e.g., time, space)
- **Relative reference frame:** The data is compared against other data (e.g., comparing two sequences or texts)

## Design Studies Methodology

### Levels of Prototyping

- **Low Fidelity Prototypes:** Simple, low-tech concept designs that let you ideate and gather early feedback

- **High Fidelity Prototypes:** Refined, functional elements that closely resemble the finished product that let you get final feedback

Sketching allows us to rapidly create both high and low fidelity prototypes!

### Design Studies

a project that analyzes a real-world problem in order to design a visualization system that contains a validated design where designers reflect about lessons learned


### When to use design studies

Design studies are used to solve wicked problems: "class of social system problems which are ill formulated, where the information is confusing, where there are many clients and decision makers with conflicting values, and where the ramifications in the whole system are thoroughly confusing" -determinacy versus indeterminacy

- **Linear model:** determinate problems have definite conditions - designer should identify conditions and design solution

- **Wicked model:** indeterminate problems have no definitive conditions or limits - designer must discover or invent a particular subject out of the problem


### Design Studies Methodology
![image](https://user-images.githubusercontent.com/92245436/157853865-579f46dd-969b-4c0a-84bb-1a769fa85459.png)


### Design Studies: Precondition

- **Learn:** Explore the literature Read about genomic analysis & talk to geneticists

- **Winnow:** Find strong collaborators Find geneticists who you can build rapport with

- **Cast:** Identify collaborator roles Who will be your guru? Your critic? Your codesigner?


### Design Studies: Core

- **Discover:** Characterize the problem in the domain & in the abstract What tasks are you trying to achieve? What data do you have?
- **Design:** Create your representations & interactions Mock up some preliminary solutions using FDS, co-design, etc.
- **Implement:** Build a prototype or system Create a high-fidelity genomics dashboard VO with real data
- **Deploy:** Give it to people and get feedback Give it to your critic(s) & gurus and see what they see (or what they want to see next)
Generally, a rinse and repeat cycle here!

## Perception in Visualisation
### Why do we care about perception?
- Tells us about mechanisms by which people interpret data Create visualizations to let people see what we need them to
- Allows us to make predictive rather than prescriptive guidelines Describe how design choices will effect interpretation
- Models systematically characterize how visualizations work for tasks & designs
- Quant for simple tasks/designs & conceptual for complex

### Visualizations at a Glance

**The Gist:** Featural and semantic information that can be gathered at a glance

1) **The Spatial Envelope:** The overall structure of the visual scene

2) **Ensemble codes:** Statistical properties of the visual features of a scene (e.g., average & variance)


### Visual Search

- The process of visually scanning an image to find items of interest
- We scan our attention over the scene to find things that are of interest
- **Salience:** How much something visually stands out
- We can manipulate salience to support visual search (e.g., through pop-out)

### Visual Clutter
![image](https://user-images.githubusercontent.com/92245436/157864392-c2faba2b-fc58-49fb-9002-dae3b734edf5.png)

## Uncertainty and Decision Making

### Uncertainty

Data are inherently a sample of the real world. Uncertainty lets us reason about what we don't know, like:

- 1) Problems or variance in how data was collected

- 2) Effects of transformations performed on the data

- 3) The data's suitability for the intended application

### Sources of Uncertainty

- **Measurement Uncertainty:** "We're not sure what the data are"

- **Model Uncertainty:** "We're not sure how the data fit together"

- **Decision Uncertainty:** "We're not sure what to do now that we have the data"
