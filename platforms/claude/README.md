# Using SvcDefSpec Coach CORE in Claude


## What you need


- access to Claude with file upload support;
- `core/svcdefspec-core.md`;
- your service evidence.


The validated v0.1.26 method did not require a Claude Project.


## Start a new regular Claude chat


Upload:
1. `core/svcdefspec-core.md`
2. the service evidence you want analyzed


Then use:


> Use the uploaded Service Definition & Specification Coach CORE as your operating method for this conversation. Apply it to the service evidence I provide. Keep the method outside-in, preserve Current/Future/Open distinctions, and follow its phase gates.
>
> Review this material and help me understand the service it describes. Start with the current state and ask only the few questions that materially improve the definition.


## Expected behavior


The same method applies as on ChatGPT:
- Phase 1 reconstructs Current and does not redesign.
- Phase 2 uses a small representative interaction set and avoids detailed workflow design.
- Phase 3 begins with the Alignment & Gap Review.
- Open items remain Open until evidence or authorized human decision resolves them.


## Capacity note


In v0.1.26 validation:
- the Small case completed in one Claude Free usage window;
- the Medium case required a usage reset after Phase 1;
- the Large case required a later reset before optimization.


The same conversation resumed cleanly after reset. This was treated as a platform capacity constraint, not a methodological failure.


## Spreadsheets


The Large Orion validation used two spreadsheets together with the other service evidence. Claude successfully incorporated the spreadsheet evidence into the current-state model and conflict analysis.


## MCP / APIs


CORE does not require MCP or APIs.


Governed external integrations belong to FULL + Integration and are distributed separately.