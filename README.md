# Lens Docs

Documentation repository for the Lens content-aware feed aggregator project.

## Repository Structure

```ascii
lens-docs/
├── README.md                      # Project overview, navigation guide
├── CONTRIBUTING.md                # Contribution guidelines
├── project/                       # Top-level project documents
│   ├── overview.md                # High-level vision for entire Lens project
│   ├── user-personas.md           # Target users and use cases
│   ├── feature-roadmap.md         # Cross-project roadmap and timeline
│   ├── architecture.md            # System-wide architecture
│   ├── integration.md             # Cross-component integration specs
│   └── metrics.md                 # Project-wide success metrics and KPIs
├── subprojects/                   # Subproject-specific documentation
│   ├── lens-engine/               # Content processing engine docs
│   │   ├── README.md              # Overview of lens-engine
│   │   ├── prd/                   # Engine-specific PRD docs
│   │   │   ├── requirements.md    # Engine requirements
│   │   │   └── roadmap.md         # Engine-specific roadmap
│   │   ├── design/                # Engine design docs
│   │   │   ├── architecture.md    # Engine architecture
│   │   │   └── data-flow.md       # Engine data flow diagrams
│   │   ├── specs/                 # Engine specifications
│   │   │   ├── api.md             # Engine API specification
│   │   │   └── data-models.md     # Engine data models
│   │   ├── models.md              # AI models integration details
│   │   └── content-processing.md  # Content processing pipeline
│   ├── lens-mcp/                  # Model Context Protocol docs
│   │   ├── README.md              # Overview of lens-mcp
│   │   ├── prd/                   # MCP-specific PRD docs
│   │   │   ├── requirements.md    # MCP requirements
│   │   │   └── roadmap.md         # MCP-specific roadmap
│   │   ├── design/                # MCP design docs
│   │   │   ├── architecture.md    # MCP architecture
│   │   │   └── integration.md     # Integration with other components
│   │   ├── specs/                 # MCP specifications
│   │   │   ├── api.md             # MCP API specification
│   │   │   └── protocols.md       # MCP communication protocols
│   │   ├── orchestration.md       # System orchestration details
│   │   └── monitoring.md          # Monitoring and alerting
│   └── lens-ui/                   # User Interface docs
│       ├── README.md              # Overview of lens-ui
│       ├── prd/                   # UI-specific PRD docs
│       │   ├── requirements.md    # UI requirements
│       │   └── roadmap.md         # UI-specific roadmap
│       ├── design/                # UI design docs
│       │   ├── wireframes.md      # Link to wireframes/mockups
│       │   └── design-system.md   # UI component system
│       ├── specs/                 # UI specifications
│       │   ├── api.md             # UI API specification (if applicable)
│       │   └── component-specs.md # UI component specifications
│       ├── components.md          # UI component library
│       └── screens.md             # Screen descriptions
├── common/                        # Cross-project shared resources
│   ├── data-schemas/              # Common data schemas shared across subprojects
│   │   ├── feed-schema.md         # Schema for RSS feed data
│   │   └── content-schema.md      # Schema for processed content
│   └── protocols/                 # Common communication protocols
│       └── interservice-comms.md  # Inter-service communication protocols
├── guides/                        # Developer and user guides
│   ├── developers/                # Developer guides
│   │   ├── getting-started.md     # Developer onboarding
│   │   ├── environment-setup.md   # Development environment setup
│   │   ├── testing.md             # Testing guidelines
│   │   └── debugging.md           # Debugging tips
│   └── users/                     # End-user documentation
│       ├── installation.md        # Installation instructions
│       ├── configuration.md       # Configuration guide
│       └── usage.md               # Usage instructions
├── resources/                     # Additional resources
│   ├── glossary.md                # Project terminology
│   └── faq.md                     # Frequently asked questions
└── meta/                          # Documentation about the docs
    ├── conventions.md             # Documentation conventions and standards
    └── templates/                 # Document templates
        ├── prd-template.md        # Template for PRDs
        ├── design-doc-template.md # Template for design docs
        └── readme-template.md     # Template for README files
```