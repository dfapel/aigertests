# aigertests
This is a collection of AIGER files as specified in http://fmv.jku.at/aiger/FORMAT .

# Filename convention
The first letter must be either `s` for a safe circuit (i.e., the single output will never be 1) or `f` followed by a decimal which is the minimum number of steps after which a bug can occur in the circuit (i.e., the output will be 1 for the first time). This is followed by a underscore (`_`) character, after which an additional description of the testcase has to be supplied. The file extension must be `.aig`. The filename must not contain spaces.

# Collaboration Policy
Feel free to add your own test cases
