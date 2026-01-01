## 10. Diffing and Identity

OpenUIR enables diffing through stable identity.

### 10.1 Producer Responsibility

Producers MUST:
- Preserve NodeIDs across updates
- Reuse NodeIDs for logically identical nodes

### 10.2 Backend Responsibility

Backends MUST:
- Apply updates by NodeID
- Avoid full tree reconstruction when possible

Diffing algorithms are explicitly outside the scope of this specification.