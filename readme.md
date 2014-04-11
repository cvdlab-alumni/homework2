# Homework assignment n.2
**Computational Visual Design Lab ([CVDLab](https://github.com/cvdlab))**  
**"Roma Tre" University, Rome, Italy**  
**Computational Graphics 2014**

## Introduction 

Take the building mock-up already developed for your first homework, and create ex-novo a more detailed  solid model, enriched on the outside by some neighbour roads and urban fittings ("arredo urbano").  The insertion of some (simplified) interior furniture would be also appreciated.

The goal of this homework is to assess the student ability to develop the model of a significant 3D construction, by (a) detailing a previously developed mock-up, (b) building an adeguate visual description of the exterior, and (c) choosing a suitable part decomposition and assembly.


## Notes

You may use either pyplasm operators or LAR objects, mixing-up both, or developing your own primitives.

The programming assignment must be produced in Python language,using the [`Pyplasm`](https://github.com/plasm-language/pyplasm) module for Python and/or the [`LAR`](https://github.com/cvdlab/lar-cc) prototype.


## Caveat

The continuation of the work carried on for the previous assignment is **strictly required**. To start working on a new building is not allowed.   

The homework is **strictly personal**, and must be worked out by a single student. Violations will be persecuted :o) 


# Exercises

## Exercise 0  (4/30 points)

Produce a HTML page with 

1.  Name of the building;

2.  Your name and surname;

3.  University ID (matricola);

and with:

* all the links to the web documentation used for your work;

* (b) a short description of the work done; 

* (c) some interesting images of the work;

* (d) links to `exercise1.py`, `exercise2.py`, etc. 

## Exercise 1   (10/30 points)

Generate a 3D model of the building floors, assemble the *horizontal partitions* ("di base, intermedie e di copertura") into a single 3D assembly, together with the building columns or the main walls;

## Exercise 2   (8/30 points)

Define, the 3D models of the *vertical enclosures* (the building envelope) ("le facciate esterne"), including the openings and the windows/doors, and producing a single model.

## Exercise 3   (6/30 points)

Insert your model of the building in a 3D "small-area plan", introducing (very simplified) models (parallelopipeds) of few *neighbouring buildings*.

## Exercise 4 (optional)   (8/30 points)

Insert several instances of elements of *urban fittings* ("arredo urbano") of your choice, including street lamps, bus shelters, benches, large flower containers, and/or simplified model of trees (made by cylinders, spheres and cones). 


# Assignment delivery

For each exercise you must produce a corresponding file `exercise1.py`, `exercise2.py`, etc.  
All the .py file must be enclosed within a directory `python`. The images within a directory `images`.    

Such directories must be contained in a directory entitled `2014-03-21`, pushed into the personal GitHub repository of the student: [https://github.com/cvdlab-cg/xxxxxx](https://github.com/cvdlab-cg/) where `xxxxxx` is the student ID  (matricola). 

```
─── xxxxxx
    └── 2014-04-11
        ├── images
        │   ├── fig01.png
        │   ├── fig02.png
        │   └── etc.
        ├── index.html
        └── python
            ├── exercise1.py
            ├── exercise2.py
            ├── exercise3.py
            └── exercise4.py
```

The delivery is strictly required within 24 hours from the publication of the homework.

# Tips

#### Commit and push as frequently as you can
