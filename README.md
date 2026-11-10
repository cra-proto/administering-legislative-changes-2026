# administering-legislative-changes

*description of the project*

**Timeframe** 2026-10-27 - 2027-02-02

## Overview

This repository was created via the **Design Assistant**.  
It contains the template files and in-scope pages needed to get started.

GitHub Pages: [https://cra-test-arc.canada.ca/administering-legislative-changes-2026](https://cra-test-arc.canada.ca/administering-legislative-changes-2026)

---
## Update procedures

Add information on how to manage your repo here.

---
## Design phase roadmap:

- [x] Initial content inventory and repo setup
- [ ] Prototype: co-design navigation and content
- [ ] SME review and accuracy check
- [ ] Validation usability testing (including accessibility review)
- [ ] Refine prototype (if required)
- [ ] Spot check usability (if required)

**Updated:**  2026-11-10

## Information Architecture
```mermaid
flowchart TD;
    node1(Canada.ca)
    node2(Canada Revenue Agency #40;CRA#41;)
    node3(About the Canada Revenue Agency #40;CRA#41;)
    node4(How the CRA works)
    node5(Administering Proposed Legislation)
    node1 --x node2
    node2 --> node3
    node3 --> node4
    node4 --> node5

    classDef inscope stroke:#7636ab,stroke-width:3px
    class node4,node5 inscope
    classDef isnew fill:#00706f,color:#fff
    class node5 isnew
```
