# phys1470-qiskit

This repo contains mostly jupyter notebooks that are used in class to demonstrate IBM qiskit.

Note that if you are running these notebooks locally and would like the output to look like on IBM's website, you need to have a file named settings.conf in a folder  called .qiskit in your home directory. i.e ~/.qiskit/settings.conf

The contents of this file should be:
`[default]
circuit_drawer = mpl
circuit_mpl_style = default
circuit_mpl_style_path = ~:~/.qiskit
state_drawer = hinton
transpile_optimization_level = 3
parallel = False
num_processes = 15
` 
