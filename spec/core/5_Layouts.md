## 5. Layouts

The Core Profile defines three layouts.

### 5.1 Row

Arranges child nodes horizontally.

Children are laid out in insertion order.

### 5.2 Column

Arranges child nodes vertically.

Children are laid out in insertion order.

### 5.3 Stack

Arranges child nodes in z-order.

Later children MUST be rendered above earlier children.

### 5.4 Layout Rules

- Layouts MUST be deterministic
- Layout behavior MUST NOT depend on backend heuristics
- Overflow behavior is backend-defined unless specified by modifiers