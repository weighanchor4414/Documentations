---
layout: default
title: "Basic Vector Mathematics"
permalink: /basic_vector_math/
use_mathjax: True
---
### Notation

Vectors are usually represented in this manner $$\overrightarrow{AB}$$

### Representation

Coordinate representation of vectors $$\overrightarrow{AB}=(x,y)$$

Matrix representation of vectors:
+ Column vector $$\overrightarrow{AB}=\begin{bmatrix} x \\ y \end{bmatrix}$$
+ Row Vector $$\overrightarrow{AB}=\begin{bmatrix} x & y \end{bmatrix}$$

### Special types of Vectors

Unit Vectors:
+ Has a length of 1 $$\; \therefore \|{\vec{v}}\| = 1$$

Standard Unit Vector:
+ Has a length of 1
+ Lies on one of the axes ( i.e. $$\vec{v}=\begin{bmatrix} 0 \\ 1 \end{bmatrix}$$ or $$\vec{v}=\begin{bmatrix} 1 \\ 0 \end{bmatrix}$$)

### Vector Operations

Addition and Subtraction $$\begin{bmatrix} x_1 \\ y_1 \end{bmatrix} \pm \begin{bmatrix} x_2 \\ y_2 \end{bmatrix} = \begin{bmatrix} x_1 \pm x_2 \\ y_1 \pm y_2\end{bmatrix}$$
+ Resultant vector is the vector if the 2 vectors were placed end to tip

Scalar Multiplication $$c\overrightarrow{AB}=c\begin{bmatrix} x \\ y \end{bmatrix}=\begin{bmatrix} cx \\ cy \end{bmatrix}$$
+ Stretches the vector in the direction it points by a factor of $$c$$

Dot Product $$\vec{u} \cdot \vec{v} = \begin{bmatrix} u_1 \\ u_2 \\ \vdots  \\ u_n \end{bmatrix} \cdot \begin{bmatrix} v_1 \\ v_2 \\ \vdots  \\ v_n \end{bmatrix} = u_1v_1 + u_2v_2 + \cdots + u_nv_n = \|\vec{u}\| \|\vec{v}\|\cos{\theta}$$
+ Gives the length of $$\vec{u}$$ in the direction of $$\vec{v}$$

Cross Product $$\vec{u} \times \vec{v} = \begin{bmatrix} u_1 \\ u_2 \\ u_3 \end{bmatrix} \times \begin{bmatrix} v_1 \\ v_2 \\ v_3 \end{bmatrix} = \begin{bmatrix} u_2v_3 - u_3v_2 \\ u_3v_1 - u_1v_3 \\ u_1v_2-u_2v_1 \end{bmatrix}$$
+ Only defined for 3D vectors
+ Results in a vector that extends perpendicularly to the plane in which $$\vec{u}$$ and $$\vec{v}$$ exist

### Usage of Vectors

Equation of a plane $$ax+by+cz=d$$ can be represented as $$\begin{bmatrix} a \\ b \\ c \end{bmatrix} \cdot \begin{bmatrix} x \\ y \\ z \end{bmatrix} = d$$, where $$\begin{bmatrix} a \\ b \\ c \end{bmatrix} = \vec{n}$$ the normal vector

Similarly, the equation of a line ax + by = c can be represented as $$\begin{bmatrix} a \\b\end{bmatrix}\cdot \begin{bmatrix} x\\y\end{bmatrix} = c$$

Cauchy-Schwarz inequality 
$$\vec{u}\cdot\vec{v}\ \leq |\vec{u}\| \|\vec{v}\|, \forall \; \vec{u} \; \vec{v} \in {\rm I\!R}^n$$ 
since 
$$\cos{\theta} \leq 1$$

Triangle Inequality $$\|\vec{u} + \vec{v}\| \leq \|\vec{u}\| + \|\vec{v}\| , \forall \; \vec{u} \; \vec{v} \in {\rm I\!R}^n$$