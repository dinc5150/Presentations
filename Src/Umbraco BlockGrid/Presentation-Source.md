---
marp: false
theme: digital-momentum
_class: lead
header: '![Digital Momentum](https://www.digitalmomentum.com.au/Images/logos/Digital-Momentum.svg)' 


---


# **Umbraco Block Grid**

<quote>"Launched with Umbraco 11 the Block Grid Editor brings new ways of structuring content, a smoother editing interface, and improved configuration and developer experience"</quote>


<!-- 

 1. Introduce the block grid
 2. How to get setup
 3. Rendering in onto the website
 4. Basic in creating backoffice views
 5. Wireframing components
 6. Qustions / Advanced stuff if we have time

-->
---

##### BlockGrid Vs Block

### Structure and Layout Capabilities
<center>

![w:900px](img/Comparison_1.png)

</center>


---
##### BlockGrid Vs Block

### Block Size
<center>

![w:900px](img/Comparison_2.png)

</center>


---
##### BlockGrid Vs Block

### Block Areas
<center>

![w:900px](img/Comparison_3.png)

</center>


---

### Setting up a Block Editor

1. Recommend starting with [Umbraco.BlockGrid.Example.Website](http://Umbraco.BlockGrid.Example.Website) Nuget Package
2. Create the document types for each available block
3. Create a Block Grid Datatype
    1. Add Layouts Blocks
    2. Add Content Blocks
4. Add the datatype to you page document types
5. Create the page


<!--

run though demo of:
- Doc types
- block grid DataType
    - Layouts / Areas
    - Blocks / Areas

- Create basic page with simple blocks
- Demo resizing columns

-->

---

### Rendering Content blocks

Layout (Items) → Areas → Area → Content Blocks (Items) → Areas → Area

<!-- 

Show how views are setup and run though grid

-->

---

### Create Custom Backoffice Views

1. Create App Plugin
2. Create the html view with:
    1. Edit command 
    2. Data bindings
    3. Areas

---

### Custom wireframing component

<center>

![w:1150px](img/wireframe.png)

</center>

---

### My 2c

1. Use Compositions for common settings (Like BgImage, Padding)
2. Use Tag Helpers for common block settings
3. Consistent Naming Convention
    1. Layouts “[Layout] 1 column”
    2. Blocks “[Block] Heading”
    3. Settings “[Setting] Background Colour”

---
# **Thanks**


<div style="columns: 2">
<div>

Presentation :  https://bit.ly/block-grid-editor

Sample Code: 
https://bit.ly/block-grid-editor-project



</div>
<div>

This Presentation:
![w:300px](img/qr.png)

</div>
</div>

References:
https://umbraco.com/blog/deep-dive-block-grid-editor-part-1/
