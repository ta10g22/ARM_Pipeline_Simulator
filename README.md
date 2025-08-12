# ARM_Pipeline_Simulator

AArch64 Pipeline Simulator
Cycle-accurate AArch64 (ARMv8-A) 5-stage CPU simulator in Python.
Implements data forwarding, load-use hazard detection, and branch prediction (static, 2-bit bimodal + BTB, optional gshare).

Features
Pipeline: IF → ID → EX → MEM → WB

ISA subset: Core integer ALU, branches, loads/stores

Branch prediction: Static, bimodal, gshare, BTB, RAS

Instrumentation: CPI, stalls, mispredict rate, instruction mix

Testing: Unit + integration tests with hand-assembled AArch64 programs
