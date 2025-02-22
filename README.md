# nus-dsa5204-project
This repository hosts the code for our NUS DSA5204 Project (AY 2024/2025 Semester 2), which aims to reproduce and extend the work done in “NeRF: Representing Scenes as Neural Radiance Fields for View Synthesis”


# Proposal 
- latex: View: https://www.overleaf.com/read/nnztbwgjhwvr#354484, Edit: https://www.overleaf.com/9751462284vshtsqrjppdq#549c09
- google doc: https://docs.google.com/document/d/1idzk7gk3UN7QQ443OdZQLphe4bKbFsFoIqO9vaxwmLc/edit?usp=sharing

# fourier feature mapping

# multi-mlp to improve output

# speed up w/ hash mapping
Owen: 
found the code implementation for the extension regarding speeding up NeRF w/ Hash Mappings:
[Instant NGP in 100 lines of PyTorch code | NeRF #13](https://www.youtube.com/watch?v=PXbPeG5PJd0), can read up on this feature and get a suitable implementation

# TBD extention
[KiloNeRF: Speeding up Neural Radiance Fields with Thousands of Tiny MLPs](https://www.youtube.com/watch?v=pgIgj3so-Z8)


# Resources
Owen: amazing presentation by the original author of Instant NeRF (the one where they hash the input data to make training times super fast on the gpu)
learning points:
- neural network optimization: the usefulness of smaller neural networks, how to modify your data structure to optimize for training, and how to optimize your training algorithm to avoid unnecessary calculations
- how instant NeRF works in the abstract
- some really cool slides and demos, which we can use for our own presentation, (please see from 35:30 to 37:30 !)
-> to add on to this above point, we might be able to have some really cool results working with images that have mirrors, for example.
https://youtu.be/CGqhCc3BrKk?si=xV4lsjTYFxR4yrjw

