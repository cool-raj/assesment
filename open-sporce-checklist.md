```mermaid
graph TB

  SubGraph1 --> SubGraph1Flow
  subgraph "SubGraph 1 Flow"
  SubGraph1Flow(SubNode 1)
  SubGraph1Flow -- Choice1 --> DoChoice1
  SubGraph1Flow -- Choice2 --> DoChoice2
  end

  subgraph "Main Graph"
  Node1[Node 1] --> Node2[Node 2]
  Node2 --> SubGraph1[Jump to SubGraph1]
  SubGraph1 --> FinalThing[Final Thing]
end
```

What criteria are used in deciding whether to use an open source component?

Popularity
Feature Set
Ease of integration
Security history (e.g. have there been multiple high-risk CVEs)
Rate of fixes (frequency of security and bug fixes)
OSS license
Commercial Support Available
Foundation/Corporate Sponsorship

options:
 Always Used
 Frequently Used
 Occasionally Used
 Rarely Used
 Never Used
