# Prompt Builder Test Hub

The Prompt Builder Hub is a centralized repository for prompt collections and nodes used by the Prompt Builder application. It provides a convenient way to organize and manage prompts for various tasks and domains.

### Prompt Builder Hub Structure:

```
pb-hub/
├── README.md
└── data/
    ├── collections/
    │   ├── collection1/
    │   │   │── pb-ce.json
    │   │   └── README.md
    │   ├── collection2/...
    │   └── collection3/...
    └── nodes/
        ├── node1/
        │   │── pb-ne.json
        │   └── README.md
        ├── node2/...
        └── node3/...
```

The main directory of the Prompt Builder Hub contains the following components:

- `README.md`: This file provides an overview and description of the Prompt Builder Hub.
- `data/collections/`: This directory contains individual prompt collections, each organized within its own subdirectory.
- `data/nodes/`: This directory contains individual prompt nodes, each organized within its own subdirectory.

Each prompt collection or node subdirectory typically contains the following components:

- `pb-ce.json`: An encrypted collection file in the Prompt Builder.
- `pb-ne.json`: An encrypted node file used in the Prompt Builder for collections of prompts.
- `README.md`: This file provides specific information about the prompt collection or node, including usage instructions, details about the prompts, and any additional relevant information.

#

<sub>Copyright © 2023 Prompt Builder, <a href="https://github.com/SoftwareResearchLab" >Lado Oniani Software Research</a>. All rights reserved.</sub>