# Homework assignment n.2
**Computational Visual Design Lab ([CVDLab](https://github.com/cvd-lab))**  
**DIA, "Roma Tre" University, Rome, Italy**  
**Computational Graphics 2012**  

# Introduction

This modeling task concerns the construction of a Javascript (simplified) model of an historical aircraft.  
The choice of the aircraft to be modeled is left to the student.  

A collection of aircraft can be found in [*The Shuttleworth Aircraft Collection*](http://www.shuttleworth.org/shuttleworth-collection/aircraft.asp)  
A description (and nomenclature) of airplane parts can be found in [http://www.grc.nasa.gov/WWW/k-12/airplane/airplane.html](http://www.grc.nasa.gov/WWW/k-12/airplane/airplane.html).  
(Other web resources are allowed.)

The programming assignment must be produced in JavaScript language using [`Plasm.js`](http://cvdlab.github.com/plasm.js/),  
and in particular using transfinite Bezier and/or transfinite Hermite and/or transfinite NUBS splines:  
`BEZIER`, `CUBIC_HERMITE`, `NUBS` (see [`Plasm.js` docs](https://github.com/cvdlab/plasm.js/blob/master/docs/Readme.md))

Start by looking at the whole collection, and choose an aircraft of your interest.  
An image of the chosen model must be enclosed in the project (see Assignment delivery).  
Plan carefully how to decompose the model into pieces to be modeled independently.  
Useful images and/or drawings should be enclosed in the project (see Assignment delivery).  
Start the programming works, item by item, only after careful planning and design of the model. (see Tips)


# Exercises

## Exercise 1

Produce the model of a single wing in a local coordinate system.

## Exercise 2

Produce the model of the fuselage (local coordinate system).

## Exercise 3

Produce the model of horizontal and vertical stabilizers (local coordinate system).

## Exercise 4

Assemble the various assemblies and/or subassemblies into a single model. 

## Exercise 5

Model a reasonably simplified airstrip, and put there your aircraft model.

# Assignment delivery

The project must be contained a directory entitled `2012-05-04`,  
pushed into your repository in cvdlab-cg organization [https://github.com/cvdlab-cg/xxxxxx](https://github.com/cvdlab-cg/)  
where `xxxxxx` is your student ID  (matricola).

For each exercise you must produce a corresponding file `exercise1.js`, `exercise2.js`, ... .  
All support material such as images of the aircraft, airplane parts, detail pictures, ...,  
must be put in a directory named `material` in the project directory.  
At least one picture of the selected aircraft must be included and named `aircraft.[png|jpg|jpeg]`.


```
XXXXXX
|
+- 2012-05-04
  |
  +- exercise1.js
  +- exercise2.js
  +- exercise3.js
  +- exercise4.js
  +- exercise5.js
  +- material
    |
    +- aircraft.png (or .jpg, or .jpeg)
    +- ...
```

> where `XXXXXX` is the name of your repository (your matricola)

The delivery is strictly required within 24 hours from the publication of the homework.

# Tips

#### Work with an updated local environment

#### Commit and push as frequently as you can

#### Work by iterations: first simple things

#### Higher marks for more detailed models