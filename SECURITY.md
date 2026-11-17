# Security and Data Handling


SvcDefSpec Coach CORE can be used without external integrations. You are responsible for the security and privacy of the environment in which you use it.


## Before uploading evidence


Confirm that you are authorized to provide the material to the selected AI platform.


Consider whether the evidence contains:
- personal information;
- confidential business information;
- regulated data;
- credentials or secrets;
- security-sensitive architecture;
- contractual restrictions;
- client information.


Do not upload information that your organization or client does not permit you to send to the chosen platform.


## Secrets


Never place API keys, passwords, tokens, client secrets, certificates, or other credentials in:
- Coach method files;
- prompts;
- public GitHub issues;
- templates;
- screenshots;
- examples.


## Connected systems


Public CORE does not require MCP, APIs, or connected applications.


If you need governed integrations, use the controlled FULL + Integration model. Connected deployments should apply:
- least privilege;
- separate read/write permissions where feasible;
- explicit approval for consequential actions;
- secrets management;
- audit logging;
- visible failure behavior;
- version compatibility controls.


## Reporting a security concern


Do not publish sensitive vulnerability details or secrets in a public issue.


Use the official SvcDefSpec distribution/contact channel to report a material security concern privately.