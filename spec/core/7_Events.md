## 7. Events

Events represent user interaction.

### 7.1 Event Model

- Events originate from backend input
- Events reference a NodeID
- Events are dispatched to the producer

### 7.2 Core Events

The Core Profile defines:

- onTap
- onInput
- onFocus
- onBlur

### 7.3 Event Semantics

- Events MUST reference stable NodeIDs
- Event payloads MUST be backend-agnostic
- Coordinate systems are backend-defined