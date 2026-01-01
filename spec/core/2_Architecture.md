## 2. Architecture

OpenUIR follows a producer–backend architecture.

- A **producer** generates OpenUIR instructions.
- A **backend** consumes instructions and renders UI.

The producer and backend MAY:
- Run in different threads
- Run in different processes
- Be implemented in different programming languages

Backends MUST maintain a retained UI tree derived solely from instructions.
