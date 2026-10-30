# List of Awesome A2A Agent2Agent Servers
This repo is intended for awesome list of A2A servers released by Google A2A protocal. [Google A2A](https://github.com/google/A2A)

[AI Agent Marketplace and Directory](http://www.deepnlp.org/store/ai-agent) <br>
[MCP Servers List](http://www.deepnlp.org/store/ai-agent/mcp-server) <br>
[Agent Search Engine](http://www.deepnlp.org/search/agent) Find Awesome AI Agent

![A2A Actors](https://github.com/google/A2A/blob/main/images/a2a_demo_arch.png))

## List of Awesome A2A Servers
[**Google ADK**](https://github.com/google/A2A/blob/main/samples/python/agents/google_adk) 
Sample agent to  fill out expense reports. Showcases multi-turn interactions and returning/replying to webforms through A2A.

[**LangGraph**](https://github.com/google/A2A/tree/main/samples/python/agents/langgraph)
Sample agent which can convert currency using tools. Showcases multi-turn interactions, tool usage, and streaming updates.

[**CrewAI**](https://github.com/google/A2A/tree/main/samples/python/agents/crewai) Sample agent which can generate images. Showcases multi-turn interactions and sending images through A2A.

[**A2A agent implementing OpenDeepResearch**](https://github.com/iamarcel/deep-research-agent)

[**a2a-agent-coder**](https://github.com/sing1ee/a2a-agent-coder)

[**Python A2A**](https://github.com/themanojdesai/python-a2a)
Python A2A is a powerful, easy-to-use library for implementing Google's [Agent-to-Agent (A2A) protocol](https://google.github.io/A2A/). It enables seamless communication between AI agents, creating interoperable agent ecosystems that can collaborate to solve complex problems.

[**SitePatent Listing Search Agent**](https://sitepatent.com)
Read-only, hosted A2A agent for the SitePatent directory of startups, SaaS and online products. Send a plain-text query via `SendMessage` (JSON-RPC, A2A protocol 1.0) and get back a completed task whose artifact lists the matching approved listings (title, slug, URL path, tagline, categories). No authentication, no API key. A2A endpoint at `https://sitepatent.com/api/a2a`. ([Agent card](https://sitepatent.com/.well-known/agent-card.json))



## Trust & Payment Infrastructure for A2A

Services that provide trust scoring, identity verification, and payment rails for agent-to-agent interactions.

[**TWZRD Agent Intel**](https://intel.twzrd.xyz)
Trust scoring and x402 micropayment verification for AI agents on Solana. When AI agents transact via A2A, use TWZRD to verify counterparty wallet reputation before transacting. Free: `resolve_agent`, `score_agent`, `preflight_check`. Paid: `get_trust_receipt` (HTTP 402 + USDC). Zero-install MCP: `{"mcpServers": {"twzrd-agent-intel": {"url": "https://intel.twzrd.xyz/mcp"}}}`. ([PyPI](https://pypi.org/project/twzrd-agent-intel/))

[**Steward**](https://pay.brianbooms.com)
Pay-per-call data tools for AI agents settled in USDC on Base via raw x402 v1: 92 endpoints (jokes, fortunes, weather, FX, crypto, geocode, sleep, and more) at $0.005–$0.99 per call — no accounts, no API keys. A2A endpoint at `https://pay.brianbooms.com/api/v1/a2a` with the a2a-x402 payment extension. ([Agent card](https://pay.brianbooms.com/.well-known/agent-card.json) | [Discovery](https://pay.brianbooms.com/.well-known/x402) | [MCP](https://github.com/brianbooms/steward-mcp))
