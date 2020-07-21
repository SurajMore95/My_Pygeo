A Python package for three-dimensional geometry.
Software tools for CMS

Installation \n
Run

python -m pip install -e ".[dev]" \n
to install pygeo and all dependencies required for local development.\n

Testing \n
Run

pytest tests \n
to run all the tests for pygeo. \n

Tasks \n
\n Implement the missing Ray class. A ray may be represented as its origin and a direction. \n

Implement an __init__ method that takes the origin and direction as argument and stores them as attributes on the instance. \n
Implement a __repr__ method. \n
Implement an __eq__ method that works by comparing both the origin and direction of the other ray. Provide tests for this method. \n
Implement the missing Sphere class. A sphere may be represented by its center and a radius. \n

Implement an __init__ method that takes the center and radius as argument and stores them as attributes on the instance. \n
Implement a __repr__ method. \n
Implement an __eq__ method that works by comparing both the center and radius of the other sphere. Provide tests for this method. \n
Implement the missing _intersect_ray_and_sphere function. You may follow this article, but keep in mind that for a ray the parameter d mentioned in the article must be larger or equal to zero. Provide tests for this method. \n

As an optional extra exercise, implement \n

the missing Triangle class, \n
the missing _intersect_ray_and_triangle function and accompanying tests, \n
the missing intersect that calls either _intersect_ray_and_sphere or _intersect_ray_and_triangle depending on the arguments.