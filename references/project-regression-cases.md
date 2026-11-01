# Implementation-project regression cases

Use these cases when reviewing changes to the skill's implementation workflow. For each case, inspect the proposed next action, generated artifacts, and completion claims. A scenario walkthrough checks the guidance; a live learning session is needed to assess its practical effect.

| Situation | Expected observable behavior |
| --- | --- |
| A learner familiar with agent loops asks to progressively reproduce an open-source system. | Locate the first useful increment in the whole system; discuss material choices and build it in the project's main implementation. Preserve the learner's existing background. |
| The learner says “continue” after discussing one component. | Implement or inspect the next relevant increment, show its essential evidence, and leave later learning stages for subsequent interaction. |
| The assistant has generated a sample and obtained a passing run, but the learner has not participated in its design or interpretation. | Report preparation and execution accurately; provide a concrete opportunity for participation and leave learning completion unclaimed. |
| The learner asks for a standalone illustration of one algorithm. | Provide the appropriately scoped demonstration; the evolving-project mode does not impose a production package or full reproduction. |
| The learner already understands the design and asks the assistant to implement the current component. | Write and verify that component without repeated design questions or line-by-line approvals. Explain consequential choices and actual results. |
| A learning target generates its own proposed improvements from execution feedback. | Implement the feedback-to-proposal path; distinguish the learner's evaluation choices from the system's inferred modification. |
| The learner authorizes a restart and removal of obsolete work. | Reconcile implementation, entrypoints, records, and authorized copies; verify removal and links before claiming cleanup complete. Respect unrelated work and authorization boundaries. |
| A required synchronization fails. | Diagnose transport or access, try an authorized safe alternative if available, verify the destination, and state any exact unresolved condition. |

## Scope of the update

The motivating observation was that assistant-prepared artifacts and narrated runs can leave a learner unable to trace or change the system, even when execution succeeds. This supports involving the learner in material decisions and building useful increments in one codebase for implementation projects. It does not establish that every learning task needs a repository, that the learner must type every line, or that later learning effectiveness has already been validated.

The execution hook is the implementation-project routing in **Start or Resume**, leading to **Build an Evolving Project**. Contract and session templates carry the same distinctions into persistent records. Isolated demonstrations and source-reading tasks retain their own scope.
