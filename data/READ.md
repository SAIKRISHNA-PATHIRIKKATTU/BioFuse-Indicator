# Thermal Dynamics & Simulation Data

This folder contains the core datasets modeling the physical and chemical reaction thresholds of the BioFuse indicator. The primary data tracks how environmental temperature correlates with the structural integrity of the internal wax barrier and the subsequent mixing rate of the reactive solutions.

### Dataset Overview: `biofuse_thermal_analysis_v1.csv`
- **Temperature_Celsius:** The simulated ambient temperature range (20°C to 50°C).
- **Wax_State:** Tracks the physical phase transition of the calibrated barrier layer (Solid → Softening → Liquid).
- **Reaction_Time_Seconds:** Models the time window required for Solution A and Solution B to mix completely and generate a permanent visual color change once the barrier fails.
- **Safety_Status:** Categorizes the state of the vial environment into actionable thresholds (Optimal, Warning, Critical, or DANGER).

*Note: This data serves as the foundation for the digital twin simulation and establishes the technical parameters for non-invasive, external product safety tracking.*
