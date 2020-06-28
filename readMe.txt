
Instructions for running demo:

Optional steps:

1. Open MuPAD notebook that models gantry crane: >> nb = mupad(‘gantryCrane.mn’)

2. Evaluate the notebook by selecting 'Notebook --> Evaluate All'

3. Use getVar command to read MLoutput variable from notebook: >> swingeq = getVar(nb,'MLoutput')

4. Generate MATLAB file from symbolic expression: >> f = matlabFunction(swingeq,'file','odeGen')

Required steps:

5. Open MATLAB script titled swingOptim.m

6. Evaluate each block of code contained in this script

Required products include:

Symbolic Math Toolbox, 
Optimization Toolbox, 
Global Optimization Toolbox, 
Parallel Computing Toolbox,
Curve Fitting Toolbox