# Problem Context

## General Description

The company operates a critical industrial asset used in a continuous production process.  
The process has a prolonged duration and does not allow interruptions without generating significant economic losses.

The asset exhibits behavior typical of complex industrial systems:
- it operates correctly most of the time,
- it shows progressive degradation of key components,
- and it may fail in a non-deterministic manner during operation.

When the asset fails during a production cycle, the process in progress is completely lost and operations must stop in an unplanned manner.

---

## Operational Characteristics of the System

- Long-duration continuous process  
- Production cycles lasting between **48 and 96 hours**  
- Unplanned interruptions generate:
  - total loss of in-process product,
  - recovery costs,
  - impact on delivery commitments  
- Information about the actual condition of the asset is partial and incomplete

---

## Organizational Context

The company includes the following functional areas:

- Operations  
- Maintenance  
- Quality / Compliance  

These areas often have partially conflicting objectives:

- Operations prioritizes continuity and adherence to the production plan  
- Maintenance prioritizes reduction of technical risk  
- Quality prioritizes avoidance of critical events and non-conformities  

The decision must be made under time pressure, with incomplete information and with significant business consequences.

---

## Nature of the Problem

The problem is not technical, but **decisional under uncertainty**.

There is no certainty as to whether the asset will fail during the current production cycle.  
However, historical records and indirect signals allow for estimation of the risk.

The company must decide how to balance:

- operational continuity,  
- failure risk,  
- economic impact,  
- and risk tolerance.

This type of decision recurs across multiple industries and operational contexts.
