# OEPDE: Online Encyclopedia of Partial Differential Equations

This project is inspired by the OEIS (On-line Encyclopedia of Integer Sequences) which is a website that allows users to search and submit integer sequences of mathematical interest. The OEIS is often very useful for collaboration and discovery as the same integer sequences may come up in different contexts. In these cases, there is often a deeper connection between the contexts that produce these sequences.

The goal of this project is to produce a similar encyclopedia for partial differential equations to encourage collaboration between mathematicians by providing a common interface for mathematicians and scientists to discover and publish information on partial differential equations. As a Ph.D. student in the field of partial differential equations, to understand an equation of interest it is not sufficient to simply specify the equation to begin a literature search. As there is no standard language to describe a partial differential equation in mathematical terms, one needs to know the 'name' of the equation to get useful results about the equation. For example, suppose one was interested in the equation $u_tt - u_xx + u = 0$. This is of course the Klein-Gordon equation but it is of course conceivable that one could imagine this equation as a simple extension of the wave equation and without knowing the proper nomenclature it would be difficult for them to find out more about the equation without proper mentorship. It is of course natural for knowledge of the names of equations to be limited to those with knowledge of the subject but it is the goal of this project to make the field more accessible.

Compared to the OEIS however, this is a very difficult task. While integer sequences may be complictated, their representation is concrete, a sequence is nothing but a list of numbers. On the other hand, it takes a huge amount of notational choices to even represent a partial differential equation in symbolic form. Furthermore, an equation is not fully specified without a domain, a range and perhaps initial conditions, boundary conditions and a plethora of other conditions that are either specified or even assumed when writing an equation.

As such, it will be very difficult to ensure the scope of this project does not explode in complexity. On the other hand, with a limited scope, the project may not achieve its goals. Let us try and understand these goals below.

## Goals

- The project must provide a standard programmic interface to search the database of equations.
- The project must provide a interface for researchers to submit equations as well as results related to equations.
- The project may allow users to describe links between equations.

## Questions
- Should the project allow users to describe families of equations in a single entry? For example, $-\Delta u = f$ is the Poisson equation but it actually describes a family of equations, i.e. each choice of $f$ gives a new equation.

## Ideas
- The problem seems to suggest using an unstructured database with links between entries, i.e. a web. For example, someone could submit a link between the Schrödinger equation and the Boltzmann equation to note that they are connected via. the Wigner transform.
