# OpenUIR 1.0 Core Profile

Status: Draft  
Version: 1.0  
Profile: Core  

The OpenUIR Core Profile defines the minimal, mandatory specification required for all OpenUIR-compliant backends.

The Core Profile specifies:
- A retained UI tree model
- Stable node identity
- A minimal set of core elements
- Core layouts
- Core modifiers
- Core events
- Instruction-based UI mutation

The Core Profile intentionally excludes:
- Animations
- Theming systems
- Platform-specific widgets
- Complex form controls
- Styling inheritance mechanisms

All higher-level functionality MUST be defined in additional profiles or extensions.

This profile is designed to be implementable across:
HTML, native UI frameworks, embedded systems, and headless backends.
