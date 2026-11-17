# SvcDefSpec Coach CORE — Repository Manifest


**Release candidate:** v0.1.26


## Public repository


```text
/
├── README.md
├── LICENSE.md
├── PUBLIC-USE-NOTICE.md
├── SECURITY.md
├── CHANGELOG.md
├── REPOSITORY-MANIFEST.md
├── core/
│   └── svcdefspec-core.md
├── docs/
│   ├── getting-started.md
│   ├── core-vs-full.md
│   ├── full-available-upon-request.md
│   ├── end-user-guide.md
│   └── support-and-limitations.md
├── platforms/
│   ├── chatgpt/
│   │   └── README.md
│   └── claude/
│       └── README.md
├── templates/
│   ├── Service-Model-Map-Template.pptx
│   └── USM-Service-Model-Canvas.xlsx
└── validation/
    └── validation-summary.md
```


## Public release rules


The public repository contains CORE only.


Do not add:
- FULL method/reference assets;
- internal analyzer/rule catalogs designated FULL-only;
- regression operator guides or hidden answer material;
- private benchmark solutions;
- private plugin archives;
- artifact-field semantic maps designated FULL-only;
- execution contracts designated FULL-only;
- credentials, secrets, or private endpoints;
- third-party or USM-owned material without confirmed redistribution rights.


## Controlled FULL repository/package


FULL is maintained separately.


Typical FULL contents include:
- complete controlled method and reference material;
- advanced analyzer/rule catalogs;
- execution-ready artifact assets;
- semantic mappings;
- deployment and integration contracts;
- approved assurance/peer-review materials;
- host-specific FULL adapters;
- extension registration and entitlement records.


## Source-of-truth rule


The controlled Drive repository remains the release-authoring source until a formal GitHub release process is approved.


The public GitHub repository should be generated from a frozen controlled release, not edited independently in ways that create a method fork.