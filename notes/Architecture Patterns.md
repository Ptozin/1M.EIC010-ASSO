## Architecture Patterns

Some important Do's and Don'ts on **patterns**:
- Do's:
    - Provide common vocabulary
    - Provide a "shorthand" solution to effectively explain complex systems/principles
    - Help document the architecture
    - Capture essential parts of a design in a compact and simple way
    - Describe abstractions (like layers, brokers...)
- Don'ts:
    - Provide an exact solution
    - Solve all design problems (we need more patterns)
    - only apply for certain designs (such as object-oriented programming ...)

We can divide the styles/patterns into three categories, which helps to codify and shared knowledge about the designs themselves:
- **Code Patterns**: Used in code, but not really necessary for us.
- **Architectural Style**: Consists of:
    - **a set of component types** (e.g., process, procedure) that perform some function at runtime
    - **a topological layout of the components** showing their runtime relationships
    - **a set of semantic constraints**
    - **a set of connectors** (e.g., data streams, sockets) that mediate communication among components
  Follow this [slide on page 4](../theory/4.3%20MEIC-ASSO-2024%20Architecture%20Styles.pdf) for examples of architecture styles.
- **Design Patterns** which is what matters more for us:
    - Follow [page 5 - 9](../theory/4.4%20MEIC-ASSO-2024%20Arch%20Patterns.pdf) for information on patterns. Remember that here you can find where they are used as well!
    - Follow [page 10+](../theory/4.4%20MEIC-ASSO-2024%20Arch%20Patterns.pdf) for pratical examples;
    - You can find Microkernel, Publish-Subscribe, Client-Server, P2P (and their advantages and disadvantages) [here](../theory/4.5%20MEIC-ASSO-2024%20More%20Arch%20Patterns.pdf). There is also Broker, Shared Repository, Blackboard, Model-View-Controller, C2 (Components and Connectors). On the end of the slide (page **67**) there's a list on the most common patterns and frequency of usage and pairings.

### Documenting Architectures

Try to follow UML rules for a good grade (I guess), use the correct symbols for a DB, servers, clients...

Remember of the 4+1 view model:
- **Logical View**: Describes the design of the system in terms of objects and classes. Uses UML diagrams such as class, object, composite structure. You can find an example on [page 53](../theory/5.1%20MEIC-ASSO-2024%20Documenting%20Architecture.pdf)
- **Process View**: Describes the dynamic aspects of the system, explains the system processes and how they communicate. You can find an example on [page 534](../theory/5.1%20MEIC-ASSO-2024%20Documenting%20Architecture.pdf)
- **Development/Implementation View**: Describes how the software is decomposed for development. You can find an example on [page 51](../theory/5.1%20MEIC-ASSO-2024%20Documenting%20Architecture.pdf)
- **Physical View**: Describes the mapping of the software onto the hardware and reflects its distributed aspect.
- **Use-cases View** (Scenarios): Describes the use cases of the system. You can find an example on [page 55](../theory/5.1%20MEIC-ASSO-2024%20Documenting%20Architecture.pdf)

Essentially, be consistent with the diagrams and do not mix multiple kinds on the same View. Just follow the homeworks and you are all set.