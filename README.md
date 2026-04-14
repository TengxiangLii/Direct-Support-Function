# Direct-Support-Function

## Atomic\_Orbital\_Restart  
The energy of restart calculation (from atomic-like orbital) jumps a lot, comparing to the standard calculation.
Through the result of claculation with `experimental mode = off` and `orthogonalization = off`, the issue seems because 
the restarting procedure simply take the SF and continue the loop "`SF_opt` $\leftrightarrow$ `kernel_opt`".
