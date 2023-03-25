# TIA Portal

Siemens TIA Portal project for a CPU 1516-3 PN/DP (S7-1500). Speed preselection, motor control, and measurement with up/down counter logic.

## PLC Program

- `Main [OB1]` - main cycle
- `1_Geschwindigkeitsvorwahl [FC1]` - speed preselection
- `2_Ansteuerung Motor [FC2]` - motor actuation
- `6_Test Messung [FC6]` - test measurement
- `UNSCALE [FC106]` - analog value unscaling
- `Zähler Up Down Test Messung [DB2]` - up/down counter data block

## Hardware

- CPU 1516-3 PN/DP
- DI 32x24VDC HF (digital inputs)
- DQ 32x24VDC/0.5A ST (digital outputs)
- AI 8xU/I/RTD/TC ST (analog inputs)
- AQ 4xU/I ST (analog outputs)

Full project export (109 pages) in `docs/Projekt-Export.pdf`.
