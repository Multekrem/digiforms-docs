# System Overview

Digiforms is built around a clear separation between design-time and runtime.

## Core Components

- **Digiforms Designer**  
  Used to define XML data models, templates and layout.

- **Digiforms Server**  
  Responsible for runtime execution, integrations and document processing.

Designer defines structure and presentation.  
Server executes, processes and integrates.

## Typical Flow

1. A document or web solution is created in Designer
2. It is published to Digiforms Server
3. Users interact with the solution
4. Server handles processing, integrations and output

To understand the distinction in more detail:

→ [Designer and Server](../designer-and-server/index.md)