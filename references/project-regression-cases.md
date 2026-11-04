# Implementation-project regression cases

Use these cases when reviewing changes to the skill's implementation workflow. For each case, inspect the proposed next action, generated artifacts, and completion claims. A scenario walkthrough checks the guidance; a live learning session is needed to assess its practical effect.

| Situation | Expected observable behavior |
| --- | --- |
| A learner building a minimal agent asks to keep practice focused on functionality while adding tool-error feedback. | Explain and implement the smallest useful feedback path, validate a representative case, and return to the functional roadmap once necessary checks pass. Add further handling when required by the current function or a concrete risk. |
| The same learning project introduces commands with consequential side effects, or the learner requests a production deployment. | Reassess the actual use and risks and implement the necessary safeguards and validation; the learning-practice pacing rule does not waive reliability requirements. |
| The learner wants to discuss reasoning, flow, pseudocode, and complete code in chat, then write project files themselves. | Provide complete code for one agreed increment with its destination and invocation; leave core file writes to the learner. Read and review their files when appropriate and distinguish predicted output from observed execution. |
| With learner-led file writing established, the learner says "continue". | Continue the next relevant reasoning or code step in conversation; preserve the agreed writer and do not silently create or patch core code. |
| The learner later explicitly delegates writing or fixing the current component. | Write and verify the delegated component without another approval gate; honor its scope and retain the standing collaboration preference for other work. |
| Code has been shown in chat but has not been saved or run. | Record code as proposed, file creation and execution as pending, and avoid claiming implementation or learning completion. |
| A learner familiar with agent loops asks to progressively reproduce an open-source system. | Locate the first useful increment in the whole system; discuss material choices and build it in the project's main implementation. Preserve the learner's existing background. |
| The learner says “continue” after discussing one component. | Advance the next relevant increment according to the agreed division of work, show its essential evidence, and leave later learning stages for subsequent interaction. |
| The assistant has generated a sample and obtained a passing run, but the learner has not participated in its design or interpretation. | Report preparation and execution accurately; provide a concrete opportunity for participation and leave learning completion unclaimed. |
| The learner asks for a standalone illustration of one algorithm. | Provide the appropriately scoped demonstration; the evolving-project mode does not impose a production package or full reproduction. |
| The learner already understands the design and asks the assistant to implement the current component. | Write and verify that component without repeated design questions or line-by-line approvals. Explain consequential choices and actual results. |
| A learning target generates its own proposed improvements from execution feedback. | Implement the feedback-to-proposal path; distinguish the learner's evaluation choices from the system's inferred modification. |
| The learner authorizes a restart and removal of obsolete work. | Reconcile implementation, entrypoints, records, and authorized copies; verify removal and links before claiming cleanup complete. Respect unrelated work and authorization boundaries. |
| A required synchronization fails. | Diagnose transport or access, try an authorized safe alternative if available, verify the destination, and state any exact unresolved condition. |

## Scope of the update

The motivating observation was that assistant-prepared artifacts and narrated runs can leave a learner unable to trace or change the system, even when execution succeeds. This supports involving the learner in material decisions and building useful increments in one codebase for implementation projects. It does not establish that every learning task needs a repository, that the learner must type every line, or that later learning effectiveness has already been validated.

The execution hook is the implementation-project routing in **Start or Resume**, leading to **Build an Evolving Project**. Contract and session templates carry the same distinctions into persistent records. Isolated demonstrations and source-reading tasks retain their own scope.
