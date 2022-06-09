Fig2Cpp has two input files:
- one in Figaro0 containing a model of system in Figaro0
- an XML file containing, among other things, the definition of target states by Figaro0 expressions.

The sample model Miniplant is a simple multistate system with various levels of production, depending on the functioning or failure of its building blocks.
Its advantage for testing Fig2Cpp is that it contains state variables of all types existing in Figaro: Boolean, integer, enumerated, real. 