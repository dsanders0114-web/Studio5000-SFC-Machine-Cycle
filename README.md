# Studio5000-SFC-Machine-Cycle
Sequential Function Chart machine cycle in Studio 5000 (Clamp → Drill → Retract → Eject)



# Studio 5000 Sequential Function Chart Machine Cycle

This project demonstrates a multi-step automated machine built using 
Sequential Function Chart (SFC) architecture in Studio 5000.

Sequence:

Idle  
Clamp  
Drill Forward  
Drill Retract  
Unclamp  
Eject Extend  
Eject Retract  
Return to Idle  

---

## Purpose

This project demonstrates:

• SFC-based machine sequencing  
• State-machine architecture  
• Simulated I/O logic  
• Timeout fault handling  
• Structured PLC design  
• Studio 5000 controls architecture  

---

## Machine Sequence

Clamp → Drill → Retract → Unclamp → Eject → Reset

The machine clamps a part, drills it, retracts, releases the clamp, ejects
the part, then returns to idle.

---

## SFC Overview

![SFC](images/sfc_overview.png)

---

## Unclamp Step

This step releases the clamp after drilling is complete.

![Unclamp](images/unclamp_step.png)

---

## Simulation Logic

Actuator motion is simulated using timers.

![Sim](images/sim_logic.png)

---

## Fault Handling

Timeout faults are generated if motion does not complete.

![Faults](images/fault_logic.png)

---

## Technologies Used

Studio 5000 Logix Designer  
Sequential Function Chart (SFC)  
Ladder Logic  
Timer Based Simulation  
State Machine Architecture  

---

## Author

Controls / Automation Portfolio Project
