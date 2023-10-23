# Steane-7

## Description
 - The Steane code is a quantum error-correcting code that encodes a single 
        logical qubit into seven physical qubits. It is designed to correct for any single qubit error, 
        which includes both bit-flip (analogous to classical bit errors) and phase-flip (a uniquely quantum error) errors.

## Example
Code Tableau:
___XXXX
        _XX__XX
        X_X_X_X
        ___ZZZZ
        _ZZ__ZZ
        Z_Z_Z_Z
- Number of qubits: N = 7
- Number of encoded bits: k = 1
### Syndrome Circuit:
![Steane-7 Syndrome Circuit](images\codeplots\Steane-7-codeplot.png)

## Benchmarking Results
This code was tested with the following decoders:
**Lookup table:** Ran in 0.389s
![Steane-7 Truth Table PP](images\performanceplots\Steane-7-lookuptable.png)
**Belief decoder:** Ran in 7.417s
![Steane-7 Belief Decoder PP](images\performanceplots\Steane-7-belief.png)

## 

## Similar Codes 
- **[]()**: 
- **[]()**: 

## References
, , 