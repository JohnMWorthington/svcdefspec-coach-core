# Using SvcDefSpec Coach CORE in Claude


## What you need


- access to Claude with file upload support;
- `core/svcdefspec-core.md`;
- your service evidence.


A Claude Project is not required for normal CORE use.


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


## Capacity and spreadsheet notes

Usage limits and spreadsheet handling vary with the account and host capabilities. For larger cases, include relevant evidence up front where supported. If a usage limit interrupts a session, resume in the same conversation when possible.

## MCP / APIs


CORE does not require MCP or APIs.


Governed external integrations belong to FULL + Integration and are distributed separately.