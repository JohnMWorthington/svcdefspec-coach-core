# Using SvcDefSpec Coach CORE in ChatGPT


## What you need


- access to ChatGPT with file upload support;
- `core/svcdefspec-core.md`;
- your service evidence.


Editable binary artifact automation is optional.


## Start a new chat


For a clean engagement, start a new chat for the service you want to analyze.


Upload:
1. `core/svcdefspec-core.md`
2. the service evidence you want analyzed


Then use:


> Use the uploaded Service Definition & Specification Coach CORE as your operating method for this conversation. Apply it to the service evidence I provide. Keep the method outside-in, preserve Current/Future/Open distinctions, and follow its phase gates.
>
> Review this material and help me understand the service it describes. Start with the current state and ask only the few questions that materially improve the definition.


## Expected behavior


Phase 1 should:
- reconstruct the Current service;
- produce a logical Service Model Map and Canvas;
- distinguish evidenced, inferred, conflicting, and Open;
- ask only a few material questions;
- avoid recommendations.


Phase 2 should begin only after transition/consent and should stay at representative interaction / high-level responsibility level.


Phase 3 should begin with the USM Alignment & Gap Review before rewriting or redesign.


## Files and templates


If your ChatGPT environment can edit PowerPoint/Excel, you may use the public templates in `templates/`.


If it cannot, the Coach should continue using structured text/tables.


## Connected apps / MCP / APIs


CORE does not require connected apps, MCP, or APIs.


Governed MCP/API deployment is a FULL + Integration capability and is subject to controlled extension/deployment terms.