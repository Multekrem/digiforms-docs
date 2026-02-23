# Build Web Applications

In Digiforms, a web application is a server-driven digital service built on XML-based document templates.

This can range from simple forms to complete self-service portals and case-handling solutions.

A typical web solution may include:

- Multi-step forms or wizards
- "Min side" functionality
- Integration with authentication providers
- Integration with signing and payment services
- Integration with archive and external systems
- Automated PDF generation
- Server-side process flow and business logic

Digiforms Server acts as the runtime environment that connects templates, XML data, integrations and process logic into a cohesive service.

---

## What you are actually building

A web solution in Digiforms is not just a form.

It is typically:

- A defined XML data model
- One or more Page Templates
- Form controls bound to XML using XPath
- Server-side process flow
- Integrations to external systems
- Document generation when needed

Even when the final output is a PDF, the primary interaction often happens in the browser.

---

## Typical architecture

At a high level:

1. The user accesses the service
2. The solution renders one or more templates
3. User input updates the XML document
4. The server processes the XML
5. The process flow triggers:
   - Validation
   - Integration calls
   - Data storage
   - PDF generation
   - Workflow progression

Understanding this XML-driven lifecycle is essential when building larger web services.

---

## Common solution types

- Application portals
- Case submission systems
- Self-service solutions
- Signing workflows
- Payment-enabled services
- Automated document production services
- Integration-heavy e-services

---

TODO:
- Add example architecture diagram
- Add example of a multi-step solution
- Document recommended structure for large solutions