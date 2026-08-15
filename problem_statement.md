Problem Statement

Updated Problem Statement

Modern smart home appliances rely on manufacturer-defined fixed thresholds and whole-device monitoring to detect faults, which means failures are typically identified only after they occur — through generic error codes — rather than being predicted in advance. Existing systems cannot isolate which specific internal component (e.g., motor, bearing, compressor) is degrading, nor do they adapt to the appliance's individual operating behavior over time.


This project proposes a multi-sensor, component-level digital twin system for smart home appliances that continuously monitors electrical (current), mechanical (vibration), and thermal (temperature) signals from an individual component in real time. An AI-based anomaly detection model learns the component's normal operating pattern directly from real sensor data — rather than relying on fixed, manufacturer-set thresholds — and flags deviations as they emerge. The system further classifies detected anomalies into fault categories (mechanical, electrical, or thermal) based on which sensor signature deviates, enabling predictive fault isolation at low cost using accessible, open-source hardware and software.


Why This Matters


Prevents unexpected appliance breakdowns by catching early warning signs

Reduces unnecessary scheduled maintenance by enabling condition-based servicing

Brings component-level predictive maintenance — currently limited to expensive industrial systems — within reach of everyday consumer appliances


Important Boundary (Honest Scope Note)
The system classifies anomalies into a fault category (mechanical/electrical/thermal) based on which sensor deviates — it does not diagnose the exact root cause (e.g., specifically "bearing wear" vs. "imbalance"). This is analogous to a triage system directing attention to the right subsystem, not a full diagnostic replacing physical inspection. Root-cause-level diagnosis (e.g., via vibration frequency spectrum analysis) is noted as future scope.
