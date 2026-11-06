# Business Process Diagnosis

## 1. Business Context

*Company:* Atlas Services (fictional company)

*Scenario:* Internal request management across multiple departments.

The company receives requests through different email channels, creating fragmented information and limited operational visibility.

## 2. Current State Analysis (AS IS)

The current process relies heavily on manual activities.

### Identified Challenges

| Process Area | Current Challenge | Business Impact |
|---|---|---|
| Request intake | Multiple email channels | Information fragmentation |
| Classification | Manual analysis | Processing delays |
| Prioritization | Inconsistent criteria | Operational inefficiency |
| Assignment | Manual routing | Increased workload |
| Monitoring | Limited visibility | Management difficulties |
| Reporting | Decentralized data | Weak performance analysis |

## 3. Current Workflow

```mermaid
flowchart TD
    A[Internal Request Received] --> B[Manual Email Review]
    B --> C[Manual Classification]
    C --> D[Manual Prioritization]
    D --> E[Manual Department Assignment]
    E --> F[Request Processing]
    F --> G[Manual Follow-up]
    G --> H[Request Closure]
