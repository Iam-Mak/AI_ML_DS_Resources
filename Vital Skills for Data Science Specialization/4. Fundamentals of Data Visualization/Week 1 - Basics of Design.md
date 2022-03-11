## Week 1 Anatomy of Visualization
### Why Visualization?
-  To see structure in data
-  To tell a story using data
-  Too much data to make sense of
-  To explore unfamiliar data
-  to answer a question 
-  Statistics are not enough/ are to complex

### What is an Information Visualisation ?
- Information Visualisation are visual representations of abstract data.
- They allow people to explore and interpret a data set visually.
- Visualizations represent data using **makrds**. **Marks** encode different attributes of each data point.

### How to we talk about visualization ?
- Abstract components of a visualisation
- Certain design components are common to almost all visualisations
- Can describe a visualisation through the *grammar of graphics*

### A Grammar of Graphics 
It divides a visualization into seven core pieces:
- **Data** - What data is being displayed? Includes specific target dimensions or attributes.
- **Aesthetics** - What are the visual elements of the visualization? Includes the axis , relative positions, & encoding channels (e.g., shape,size,color)
- **Scale** - What range of values is visualised?
- **Geometric Objects** - What shape do marks take? 
- **Statistics** - What computed information is presented? Includes how data is grouped
- **Facets** - How is the data broken into different visualizations?
- **Coordination System** -How are data values mapped to visual elements?

![image](https://user-images.githubusercontent.com/92245436/154855174-c63cfa3c-9afd-493d-bc3c-296b30225595.png)

### Mapping Basics
### What is a mapping?
A function that translate values from one space to another .

**Expressiveness:** The visual encoding should express all of, and only, the information in the dataset attributes.
**Effectiveness:** The importance of the attribute should match the salience of the channel.

### Introduction to Interaction
Visualization Mantra
- Overview First
- Zoom & Filter
- Details on Demand

Why Interaction ?
- Support new insights
- Explore different levels of detail
- Emphasize subsets of data
- Self - discovery & sensemaking 
- Scalability (reveal hidden or aggregated data)

Seven Types of Interactions
- **Select:** Mark something as interesting
- **Explore:** Show me something else
- **Abstract/Elaborate:** Show me more or less detail
- **Reconfigure:** Show me the same thing in a different order
- **Filter:** Show me a specific subset of something
- **Encode:**  Show me a specific thing in a different way
- **Connect:** Show me things like this
