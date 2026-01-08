# Problem Statement

Sanctions screening operations generate a high volume of alerts as part of regulatory compliance requirements.  
In practice, a significant share of these alerts is driven by weak similarities and low-risk signals that rarely convert into true matches.

At the same time, sanctions screening processes often receive **additional identifying signals** from external screening sources that are not fully leveraged in decision-making.  
These signals are typically treated as contextual information for manual review rather than as structured inputs capable of informing early decisions.

This creates a structural inefficiency:
- Low-risk alerts continue to require manual review despite the availability of corroborating signals  
- Human capacity is consumed by cases with limited investigative value  
- Alerts with very different risk profiles follow the same operational path  

The core problem is not the existence of false positives, but the absence of a decision framework capable of **using existing screening signals to distinguish which alerts truly require human judgment**.

Without explicit decision boundaries, low-risk alerts are escalated by default, increasing operational cost and introducing variability in how cases are reviewed over time.

This problem is fundamentally a **decision design challenge**:  
how to structure and apply existing screening signals to reduce manual review of low-risk sanctions alerts while preserving regulatory rigor, explainability, and accountability.
