---
slug: "pangolinfo-amazon-data-mcp"
name: "Pangolinfo Amazon Data MCP"
description: "A hosted MCP service providing structured Amazon product, search, review, seller, and category data for agent-led e-commerce research."
category: "web-crawling-data-extraction"
tags: ["mcp", "amazon", "ecommerce", "data-extraction", "market-research"]
websiteUrl: "https://www.pangolinfo.com/amazon-data-mcp/"
githubUrl: "https://github.com/Pangolin-spg/amazon-data-mcp"
pricing: "paid"
classification: "agent-enabling"
entityType: "service"
developerName: "Pangolinfo"
docsUrl: "https://docs.pangolinfo.com/en-help-center/mcp/overview"
interfaces: ["MCP", "Streamable HTTP", "stdio"]
deploymentModes: ["Hosted service", "Local stdio bridge"]
verificationLevel: "documentation-reviewed"
classificationRationaleMd: "Structured e-commerce data and discoverable MCP tools let agents combine product, review, seller, and category research."
inclusionRationaleMd: "The listed product is the hosted data service, not just its bridge: it retrieves Amazon data for documented ASIN audits, seller-catalog analysis, and keyword research."
bestForMd: "Agent builders conducting Amazon product research and market analysis."
limitationsMd: "Requires a Pangolinfo account and API key. Backend calls are usage-billed after limited free testing. The MIT-licensed local bridge requires Node.js 18+ and does not make the hosted service free."
unknownsMd: "No independent performance, data-accuracy, or cross-client compatibility testing was performed for this submission."
evidenceSources:
  - title: "Pangolinfo Amazon Data MCP product page"
    url: "https://www.pangolinfo.com/amazon-data-mcp/"
    claim: "Documents Amazon product, search, review, seller and category tools, agent research workflows, remote MCP access, and per-call billing with free testing."
    accessedAt: "2026-10-02"
    sourceType: "official-product-page"
  - title: "Pangolinfo Amazon Data MCP repository"
    url: "https://github.com/Pangolin-spg/amazon-data-mcp"
    claim: "Documents the Node.js 18+ stdio bridge, hosted Streamable HTTP connection, API-key requirement, tool discovery and forwarding, and MIT licensing of bridge source."
    accessedAt: "2026-10-02"
    sourceType: "official-repository"
---
Pangolinfo Amazon Data MCP exposes structured e-commerce data to MCP-capable agents through a hosted endpoint. A local stdio bridge is available for clients that need it. Users supply their own Pangolinfo API key; ongoing hosted data access is usage-billed.

## So agents can...

- Retrieve Amazon search results and product details to investigate a set of ASINs.
- Combine review data with product information for evidence-based product research.
- Inspect seller catalogs and category data as inputs to market and competitor analysis.

This listing describes documented capabilities, not an independent hands-on test or an endorsement by Amazon. The bridge's open-source license is distinct from the hosted service's pricing.
