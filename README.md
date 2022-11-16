# control_algorithms
LabVIEW control algortihms

PID control algorithm for LabVIEW
- it uses Simpson's 1/3 rule to integrate the error
- only process value is (pv(n)-pv(n-1)) is multiplied by derivative gain in order to avoid "derivative kicks" if high frequency signal is at the input
