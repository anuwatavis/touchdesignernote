- A network is a group of inter-connected [[Nodes]] of Operators in one Component. Every component contains a network, and every network lives in a component.

- Network nodes are connected by colored wires showing the data flow from operator to operator of the same family (e.g. CHOP to CHOP), each operator cooking its inputs and generating its output.

- Some network elements may not be directly wired. Dashed straight gray lines indicate other connections:

- A Python or Tscript expression in a `parameter` that refers to `another operator`.
- A CHOP channel [[exports]] to a parameter of another operator.
- A parameter contains the path to another operator.
- Components contain their own networks that use their input nodes (In OPs) to generate its output (Out OPs).

- Some nodes may be referenced by scripts in DATs, between which where no connecting lines are drawn.

- Generally, nodes are wired together with data flowing from left to right.

