# Getting Started


## 1. Choose your platform


For ChatGPT, use:
- `platforms/chatgpt/README.md`


For Claude, use:
- `platforms/claude/README.md`


## 2. Load the method


Use `core/svcdefspec-core.md` as the operating method for the conversation.


## 3. Provide service evidence


You can start with:
- an existing SLA or service agreement;
- service descriptions;
- catalog extracts;
- customer/user context;
- supplier/dependency information;
- performance data;
- workshop notes;
- interview transcripts;
- a plain-language description of a new service.


For an existing service, start with current-state evidence.


## 4. Use an ordinary-language request


A good starting prompt is:


> Use the uploaded Service Definition & Specification Coach CORE as your operating method for this conversation. Apply it to the service evidence I provide. Keep the method outside-in, preserve Current/Future/Open distinctions, and follow its phase gates.
>
> Review this material and help me understand the service it describes. Start with the current state and ask only the few questions that materially improve the definition.


You do not need to know the Coach's specialist terminology.


## 5. Let the phases work


The Coach should begin with Phase 1 and reconstruct the current service before recommending improvements.


When Phase 1 is coherent, you can ask it to move to operational detail.


When Phase 2 is coherent, you can move to formalization and the USM Alignment & Gap Review.


## 6. Review outputs


Treat AI output as a draft interpretation.


Confirm:
- Customer and Provider boundary;
- scope;
- Current/Future/Open status;
- useful completion;
- material commitments;
- responsibilities and dependencies;
- conflicts and ambiguities.


## 7. Do not force detailed workflow design


If detailed routing, approval, RACI, request models, MIR/CMDB structure, or USM workflow/process design becomes necessary, treat that as downstream work after the service model and agreement foundation are valid.