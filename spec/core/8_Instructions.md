## 8. Instructions

Instructions mutate the retained UI tree.

### 8.1 Instruction Categories

Backends MUST support:

- CreateNode
- UpdateNode
- RemoveNode
- AppendChild
- RemoveChild

### 8.2 Instruction Ordering

Instructions MUST be applied in order.

Backends MUST NOT reorder instructions.

### 8.3 Atomicity

Instruction batches MUST be applied atomically.