# Homework assignment n.2
**Computational Visual Design Lab ([CVDLab](https://github.com/cvdlab))**   
**"Roma Tre" University, Rome, Italy**   
**Computational Graphics 2013**   

# Introduction

The requirement is to produce a very simplified digital mock-up of a racing car.

(From [Wikipedia, the free encyclopedia: Automotive design](http://en.wikipedia.org/wiki/Automotive_design))
The functional design and development of a modern motor vehicle is typically done by a large team from many different disciplines included in automotive engineering. Automotive design in this context is primarily concerned with developing the visual appearance or aesthetics of the vehicle, though it is also involved in the creation of the product concept.
The stylist responsible for the design of the exterior of the vehicle develops the proportions, shape, and surfaces of the vehicle. Exterior design is first done by a series of digital or manual drawings. Progressively more detailed drawings are executed and approved.


# Notes

Useful links are [here](https://www.google.it/search?q=draw+ferrari+cars&source=lnms&tbm=isch&sa=X&ei=u_mMUdWWC8nBswbQuYHYBg&ved=0CAoQ_AUoAQ), [here](http://store.ferrari.com/it/collezionismo/modelli-da-collezione/) and [here](https://www.facebook.com/media/set/?set=a.10150411004934780.375266.239718954779&type=3).
First spend time to look carefully to how a complex shape is built by a sequence of shape refinements, using sketches and paper drawings. Only later start the modeling work, **item by item** (exercise by exercise).
The programming assignment must be produced in *Python*, using the the [`Pyplasm`](https://github.com/plasm-language/pyplasm) module for Python.

## Remark

The solutions to the homework assignment are strictly personal. Group work is not allowed.

# Exercises

## Exercise 1

Choose, searching on the web, a set of reference sketches and drawings for the car model you want to produce, and store their images in a directory (do not forget to add the images that drive your development of the exercises below).

## Exercise 2

Generate the 2D profile curves of the car envelope in three orthogonal planes, embed them in 3D (in the x=0, y=0 and z=0 planes, respectively, with the reference frame origin set approximately at the car centroid) and mount them together in a "two-and-a-half-dimensional" (2.5D) or "pseudo-3D" model.

![img src=2.5Dimage.png alt=foobar](http://www.dia.uniroma3.it/~paoluzzi/web/pao/fig/2.5Dimage.png)

Just make a 3D structure including 2D models embedded in 3D planes.
Use at least 3 planes (usually x=0,y=0,z=0), but adding more planes may be visually useful.

## Exercise 3

Generate a 3D model of a racing car wheel (see, e.g. [here](https://www.google.it/search?hl=en&site=imghp&tbm=isch&source=hp&biw=968&bih=606&q=racing+car+wheels&oq=racing+car+wheels)),
and mount four wheel instances in the 2.5D car mock-up.

## Exercise 4

Generate the 3D model of a steering wheel (volante :o) specifically designed for Formula and Sport cars (look on the web for common shapes). Mount it the the 2.5D mock-up.

## Exercise 5

Create **at least** two *interesting* car surfaces and add them to the mock-up.

# Assignment delivery

For each exercise you must produce a corresponding file `exercise1.py`, etc.   
All the .py file must be enclosed within a directory `python`.   
Such directories must be contained in a directory entitled `2013-05-10`,   
pushed into the personal GitHub repository of the student: [https://github.com/cvdlab-cg/xxxxxx](https://github.com/cvdlab-cg/)   
where `xxxxxx` is the student ID  (matricola).

```
+- xxxxxx
|
+- 2013-05-10
  |
  +- images
  | |
  | +- image1.jpeg
  | +- image2.png
  | +- etc.
  | +- ....
  |
  +- python
    |
    +- exercise1.py
    +- exercise2.py
    +- exercise3.py
    +- exercise4.py
    +- exercise5.py
```

The delivery is strictly required within 24 hours from the publication of the homework (by 7:00 PM of Saturday May 11th 2013).

# Tips

#### Commit and push as frequently as you can


