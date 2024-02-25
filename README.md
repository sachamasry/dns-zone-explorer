# DNS Zone Explorer

Queries and reconstructs a DNS zone tree, presenting the information
graphically, making it easy to grasp the extent of the zone and spot any
anomalies or vulnerabilities.

## To do

- Provide subdomains a record structure and type
- Calculate tree depth and store inside record
- Determine a scheme by which to present subdomains and the records emanating from them
  - Classify subdomains
  - Handle their subtrees
- Create a HTML, text-like presentation of the zone tree
  - Allow expansion of the branches of the tree
  - Present all interesting record information
- Create a flat record structure, which an administrator would use to reconstruct the zone
- Create a fully visual, tree-like graphic presentation of the tree, using Mermaid.js
- Clean up Livebook code
- Fully document code, write up decisions taken, with their reasons
- Fully document the project in this README file